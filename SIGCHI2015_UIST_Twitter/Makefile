all:
	python gdoc2latex.py https://docs.google.com/document/d/16m5ItmaCl2I4lrD4tmrrCopcZBA7zqQqEtAfoJ_ic0s/edit?usp=sharing > paper.tex
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	pdflatex paper.tex
