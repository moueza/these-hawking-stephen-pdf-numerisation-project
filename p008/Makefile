init :
	sudo apt install texlive-base texlive-latex-recommended texlive texlive-latex-extra texlive-full texlive-publishers texlive-science texlive-pstricks texlive-pictures
all :
	pdflatex p008.tex
clean :
	find . -name "*~"  -exec  rm {} ; rm *.ps *.dvi *.log *.out *.aux *#* \;
	find . -name "*#*" -exec rm {} ; rm  *.ps *.dvi *.log *~ *.out *.aux \;

roots :
	latex  p008.tex
	dvips  p008.dvi
	ps2pdf  p008.ps
Clean :
	make clean ; 	rm p008.pdf
