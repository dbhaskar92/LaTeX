ALL: Math256Tutorial1.pdf Math256Tutorial2.pdf

%.pdf: %.tex Makefile
	pdflatex $<
	
clean:
	rm -f *.aux *.log *.pdf
