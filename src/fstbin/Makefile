
# make "all" the target.
all:

# Disable linking math libs because  not needed here.  Just for compilation speed.
# no, it's now needed for context-fst-test.
# MATHLIB = NONE

EXTRA_CXXFLAGS = -Wno-sign-compare

include ../kaldi.mk

BINFILES = fstaddselfloops

OBJFILES =

TESTFILES =

# actually, this library is currently empty.  Everything is a header.
LIBFILE =

ADDLIBS = ../decoder/kaldi-decoder.a ../fstext/kaldi-fstext.a \
          ../util/kaldi-util.a ../matrix/kaldi-matrix.a ../base/kaldi-base.a 

include ../makefiles/default_rules.mk
