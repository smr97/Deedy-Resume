.SUFFIXES:
.SUFFIXES: .aux .bib .tex .pdf
FILENAME=smresume
all: $(FILENAME).pdf

$(FILENAME).pdf: $(FILENAME).aux $(FILENAME).tex
	xelatex smresume

$(FILENAME).aux: publications.bib 
	xelatex smresume ; bibtex smresume
