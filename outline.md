# IEB VADR talk 01/16/20
* Indexing 
  - GenBank has a lot of data
  - Manual GenBank indexing does not scale
  - Sequence submissions are handled by indexers
  - NCBI GenBank indexers use BLAST
* Viruses
  - list of viruses with most seqs
  - viral sequences are not systematically or thoroughly annotated
  - annotation and validation should be coupled
  - VADR uses RefSeqs to validate and annotate viral sequences
  - Norovirus and Dengue selected as first two viruses
* VADR implementation
  - v-build.pl builds a homology model and stores feature info
  - VADR schematic (Figure 1 from VADR paper)
  - VADR 1.0 library
* v-annotate
  - overview: 4 stages
  - stage 1: classification
  - stage 2: coverage determination
  - stage 3: alignment and feature mapping
  - stage 4: protein validation
* VADR results on Norovirus and Dengue
  - pass/fail numbers
  - number of each alert
  - VAPiD
  - VIGOR
  - Summary of VAPiD, VIGOR, VADR on 200 seq test sets
  - Comparison of VAPiD and VIGOR
  - Comparison of VIGOR and VAPiD
  - 35 sequences only fail VADR
* VADR is general
* Limitations
* Future directions
