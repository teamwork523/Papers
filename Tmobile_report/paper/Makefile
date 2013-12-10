BIB = bib.bib

all:
	pdflatex -shell-escape paper
	pdflatex -shell-escape paper
	bibtex paper
	pdflatex -shell-escape paper

clean:
	/bin/rm -f paper.pdf *.dvi *.aux *.ps *~ *.log *.out *.ent
	/bin/rm -f *.lot *.lof *.toc *.blg *.bbl url.sty
