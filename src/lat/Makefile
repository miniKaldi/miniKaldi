
all:

include ../kaldi.mk

EXTRA_CXXFLAGS += -Wno-sign-compare

TESTFILES = kaldi-lattice-test  push-lattice-test minimize-lattice-test \
      determinize-lattice-pruned-test

OBJFILES = kaldi-lattice.o lattice-functions.o word-align-lattice.o \
	   sausages.o \
       push-lattice.o minimize-lattice.o determinize-lattice-pruned.o 

LIBNAME = kaldi-lat

ADDLIBS = ../hmm/kaldi-hmm.a ../tree/kaldi-tree.a ../util/kaldi-util.a \
          ../matrix/kaldi-matrix.a ../base/kaldi-base.a 


include ../makefiles/default_rules.mk

