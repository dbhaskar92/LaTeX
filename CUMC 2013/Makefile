ALL: CUMC2013.pdf

%.pdf: CUMC2013.tex Makefile graph
	pdflatex CUMC2013.tex && pdflatex CUMC2013.tex
	
graph:
	neato -x -Tpng graph.gv > neatograph.png

clean:
	rm -f *.pdf *.ps *.aux *.log *.nav *.out *.snm *.toc neatograph.png
