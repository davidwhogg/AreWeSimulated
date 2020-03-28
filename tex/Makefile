.SUFFIXES: .tex .pdf

all: $(patsubst %.tex,%.pdf,$(wildcard *.tex))

.tex.pdf:
	pdflatex $*
