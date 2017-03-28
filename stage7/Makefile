texname = assignment

assignment: $(texname).tex $(wildcard *.tex) $(texname).bib
	rubber --pdf $(texname).tex

glossary: $(texname).tex $(wildcard *.tex) $(texname).bib
	pdflatex $(texname)
	makeglossaries $(texname)
	pdflatex $(texname)
	pdflatex $(texname)

clean: $(texname).tex
	rubber --clean $(texname).tex
