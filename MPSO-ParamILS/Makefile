ALL: Paper.pdf 

Paper.pdf: Paper.tex Intro.tex PSO.tex Bench.tex Configure.tex ResDiscuss.tex BestPractice.tex Challenges.tex FutureWork.tex Makefile
	pdflatex Paper.tex
	
clean:
	rm -f *.aux *.bbl *.blg *.log Paper.pdf
