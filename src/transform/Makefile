all:

include ../kaldi.mk

TESTFILES = regtree-fmllr-diag-gmm-test  \
      regression-tree-test  \
      regtree-mllr-diag-gmm-test 

OBJFILES = regression-tree.o regtree-mllr-diag-gmm.o  \
    regtree-fmllr-diag-gmm.o cmvn.o transform-common.o 


LIBNAME = kaldi-transform

ADDLIBS = ../gmm/kaldi-gmm.a ../tree/kaldi-tree.a ../util/kaldi-util.a \
          ../matrix/kaldi-matrix.a ../base/kaldi-base.a 

include ../makefiles/default_rules.mk
