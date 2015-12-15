
FILE=personal-statement

build: $(FILE).tex
	pdflatex $(FILE)
	pdflatex $(FILE)
	bibtex $(FILE)
	pdflatex $(FILE)
	pdflatex $(FILE)
	pdflatex $(FILE)

clean:
	$(RM) *.aux *.bbl *.blg *.dvi *.idx *.log *.lol *.t1 *.toc *.acn *.glo *.ist *~
