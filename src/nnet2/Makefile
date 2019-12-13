

all:

include ../kaldi.mk

LDFLAGS += $(CUDA_LDFLAGS)
LDLIBS += $(CUDA_LDLIBS)


TESTFILES = nnet-component-test nnet-precondition-test \
	nnet-precondition-online-test  \
    nnet-nnet-test am-nnet-test online-nnet2-decodable-test \
    nnet-compute-test

OBJFILES = nnet-component.o nnet-nnet.o  \
     nnet-compute.o am-nnet.o   \
     nnet-precondition.o nnet-precondition-online.o \
     nnet-example-functions.o nnet-compute-discriminative.o \
     online-nnet2-decodable.o \

LIBNAME = kaldi-nnet2

ADDLIBS = ../cudamatrix/kaldi-cudamatrix.a ../lat/kaldi-lat.a \
          ../hmm/kaldi-hmm.a ../transform/kaldi-transform.a ../gmm/kaldi-gmm.a \
          ../tree/kaldi-tree.a ../util/kaldi-util.a ../matrix/kaldi-matrix.a \
          ../base/kaldi-base.a 

include ../makefiles/default_rules.mk
