all:
	-pdflatex -interaction=batchmode MURC_poster.tex > output.log 2>&1
	pdftk MURC_poster.pdf cat 2 output MURC_poster_page2.pdf
clean:
	rm -rf *.aux *.nav *.out *.log *.toc *.snm *.pdf 
