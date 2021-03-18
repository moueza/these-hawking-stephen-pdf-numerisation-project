all :
	latex  *.tex
	dvips  *.dvi
	ps2pdf  *.ps
init :
	sudo apt install texlive-base texlive-latex-recommended texlive texlive-latex-extra texlive-full texlive-publishers texlive-science texlive-pstricks texlive-pictures

#anyway in .gitignore nessessaire : nec plus ultra
nec :
	find . -name "*~"  -exec  rm {} \;
	find . -name "*#*" -exec rm {} \;


clean :
	find . -name "*~"  -exec  rm {} ; rm *.ps *.dvi *.log *.out *.aux *#* \;
	find . -name "*#*" -exec rm {} ; rm  *.ps *.dvi *.log *~ *.out *.aux \;

speed :
	pdflatex *.tex
Clean :
	make clean ; 	rm *.pdf
