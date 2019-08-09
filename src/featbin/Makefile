
all:
EXTRA_CXXFLAGS = -Wno-sign-compare
include ../kaldi.mk

BINFILES = add-deltas apply-cmvn compute-cmvn-stats compute-cmvn-stats-two-channel compute-mfcc-feats \
		   copy-feats extract-segments feat-to-dim modify-cmvn-stats

OBJFILES =

TESTFILES =

ADDLIBS = ../hmm/kaldi-hmm.a ../feat/kaldi-feat.a \
          ../transform/kaldi-transform.a ../gmm/kaldi-gmm.a \
          ../tree/kaldi-tree.a ../util/kaldi-util.a ../matrix/kaldi-matrix.a \
          ../base/kaldi-base.a 

include ../makefiles/default_rules.mk
