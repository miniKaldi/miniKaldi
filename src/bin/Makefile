
all:
	-rm -f arpa2fst
EXTRA_CXXFLAGS = -Wno-sign-compare
include ../kaldi.mk

BINFILES = acc-tree-stats align-equal-compiled align-text am-info build-tree cluster-phones compile-questions \
		   compile-train-graphs compute-wer compute-wer-bootci convert-ali copy-matrix sum-tree-stats


OBJFILES =

ADDLIBS = ../decoder/kaldi-decoder.a ../lat/kaldi-lat.a ../lm/kaldi-lm.a \
          ../fstext/kaldi-fstext.a ../hmm/kaldi-hmm.a \
          ../transform/kaldi-transform.a ../gmm/kaldi-gmm.a \
          ../tree/kaldi-tree.a ../util/kaldi-util.a ../matrix/kaldi-matrix.a \
          ../base/kaldi-base.a


TESTFILES =

include ../makefiles/default_rules.mk
