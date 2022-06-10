SHELL=/bin/bash
DOK=presentation

.SUFFIXES:
.SUFFIXES: .bib .pdf .tex
.PHONY: clean

run: $(DOK).pdf


$(DOK).pdf:  $(DOK).tex
	latex $(DOK).tex

clean:
	rm -f *.{aux,lof,log,lot,lol,,bcf,toc,bbl,blg,run.xml,out,nav,snm}
