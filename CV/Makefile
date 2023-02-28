ALL: Curriculum_Vitae_DB.pdf 

%.pdf: %.tex Makefile
	pdflatex $<
	pdflatex $<
	
clean:
	rm -f *.aux *.log *.pdf
