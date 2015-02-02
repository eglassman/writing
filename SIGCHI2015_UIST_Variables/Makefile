all:
	python gdoc2latex.py https://docs.google.com/document/d/1zcPkT8xmerhUgeLKRt8rMDJFDXBijXCIyGbixD5caIU/edit?usp=sharing > paper.tex
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	pdflatex paper.tex
