URL:=http://www.udialogue.org/download/VCTK-Corpus.tar.gz
URL:=https://datashare.ed.ac.uk/bitstream/handle/10283/2119/VCTK-Corpus.tar.gz


# ----------------------------------------------------------------------------
# load corpus

all:
	make VCTK-Corpus

VCTK-Corpus: VCTK-Corpus.tar.gz
	tar -zxvf $<

VCTK-Corpus.tar.gz:
	wget -c $(URL) --no-check-certificate
