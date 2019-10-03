set(PACKAGE "${PACKAGE}.nnet1")

add_pyclif_library("_nnet_nnet1" nnet-nnet.clif
  CLIF_DEPS _cu_matrix _iostream
  LIBRARIES kaldi-nnet
)
