SRCS = paper.tex abstract.tex clientresults.tex conclusion.tex  insights.tex intro.tex methodology.tex overview.tex qxdmresults.tex related.tex eval.tex
BIB = robustnet.bib

all: paper.pdf

pdf: paper.pdf

paper.pdf: $(SRCS)
	pdflatex -shell-escape paper
	bibtex paper
	pdflatex -shell-escape paper
	pdflatex -shell-escape paper

clean: 
	\rm -f *.dvi *.aux *.ps *~ *.log *.blg *.bbl *.pdf *.eps figs/*-eps-converted-to.pdf

