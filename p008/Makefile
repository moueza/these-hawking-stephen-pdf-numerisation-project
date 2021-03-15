all :
	latex  p008.tex
	dvips  p008.dvi
	ps2pdf  p008.ps

init :
	sudo apt install texlive-base texlive-latex-recommended texlive texlive-latex-extra texlive-full texlive-publishers texlive-science texlive-pstricks texlive-pictures

clean :
	find . -name "*~"  -exec rm {} \;
	find . -name "*#*" -exec rm {}  \;
	find . -name "*"   -exec rm *.ps *.dvi *.log *~ *.out *.aux \;
easy:
	pdflatex p008.tex
Clean :
	make clean ; 	rm p008.pdf
