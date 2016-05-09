ALL: poster.pdf 

%.pdf: %.tex Makefile
	pdflatex --enable-write18 $<

clean:
	rm -f *.aux *.bib *.bbl *.blg *.log poster.pdf 
