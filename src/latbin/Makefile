
all:

EXTRA_CXXFLAGS = -Wno-sign-compare
include ../kaldi.mk

LDFLAGS += $(CUDA_LDFLAGS)
LDLIBS += $(CUDA_LDLIBS)

BINFILES = lattice-add-penalty lattice-align-words lattice-best-path lattice-mbr-decode \
		   lattice-prune lattice-scale nbest-to-ctm

OBJFILES =


TESTFILES =

ADDLIBS = ../lat/kaldi-lat.a  \
          ../fstext/kaldi-fstext.a ../hmm/kaldi-hmm.a ../tree/kaldi-tree.a \
          ../util/kaldi-util.a ../matrix/kaldi-matrix.a ../base/kaldi-base.a 

include ../makefiles/default_rules.mk
