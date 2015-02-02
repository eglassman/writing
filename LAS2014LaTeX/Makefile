all:
	python gdoc2latex.py https://docs.google.com/document/d/1D95mJ9IZv2oCBGZWisUcVHGeSMGh6RlQCL-Z6bmNNLA/edit?usp=sharing > paper.tex
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	pdflatex paper.tex
