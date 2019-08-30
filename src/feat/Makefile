

all:

include ../kaldi.mk

TESTFILES = feature-mfcc-test  \
         feature-functions-test \
         resample-test  wave-reader-test

OBJFILES = feature-functions.o feature-mfcc.o \
           mel-computations.o wave-reader.o \
           resample.o \
           feature-window.o

LIBNAME = kaldi-feat

ADDLIBS = ../transform/kaldi-transform.a ../gmm/kaldi-gmm.a \
          ../tree/kaldi-tree.a ../util/kaldi-util.a ../matrix/kaldi-matrix.a \
          ../base/kaldi-base.a 

include ../makefiles/default_rules.mk
