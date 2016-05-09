ALL: poster.pdf 

%.pdf: %.tex Makefile
	pdflatex $<
	
clean:
	rm -f *.aux *.out *.bbl *.blg *.log poster.pdf
