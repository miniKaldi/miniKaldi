all:

OPENFST_CXXFLAGS =
OPENFST_LDLIBS =
include ../kaldi.mk

TESTFILES = diag-gmm-test mle-diag-gmm-test full-gmm-test mle-full-gmm-test \
		am-diag-gmm-test mle-am-diag-gmm-test 

OBJFILES = diag-gmm.o diag-gmm-normal.o mle-diag-gmm.o am-diag-gmm.o \
           mle-am-diag-gmm.o full-gmm.o full-gmm-normal.o mle-full-gmm.o \
					 model-common.o decodable-am-diag-gmm.o model-test-common.o  gmm-info.o

LIBNAME = kaldi-gmm

ADDLIBS = ../tree/kaldi-tree.a ../util/kaldi-util.a ../matrix/kaldi-matrix.a \
          ../base/kaldi-base.a 



include ../makefiles/default_rules.mk
