all:
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex

clean:
	rm -rf *.aux *.bbl *.log *.blg main.pdf
