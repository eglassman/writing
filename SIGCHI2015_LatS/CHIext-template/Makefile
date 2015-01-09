all:
	python gdoc2latex.py https://docs.google.com/document/d/1aJOtVy1wv6uqNu-CGHPLwfFXLajeHBFPRrzBfBS3m5M/edit?usp=sharing > paper.tex
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	pdflatex paper.tex
