
all:

EXTRA_CXXFLAGS = -Wno-sign-compare
include ../kaldi.mk

BINFILES = gmm-acc-stats-ali gmm-align-compiled gmm-boost-silence gmm-est gmm-init-model \
		   gmm-init-mono gmm-latgen-faster gmm-latgen-faster-parallel gmm-mixup gmm-sum-accs

OBJFILES =



TESTFILES =

ADDLIBS = ../decoder/kaldi-decoder.a ../lat/kaldi-lat.a \
          ../fstext/kaldi-fstext.a ../hmm/kaldi-hmm.a ../feat/kaldi-feat.a \
          ../transform/kaldi-transform.a ../gmm/kaldi-gmm.a \
          ../tree/kaldi-tree.a ../util/kaldi-util.a ../matrix/kaldi-matrix.a \
          ../base/kaldi-base.a 


include ../makefiles/default_rules.mk
