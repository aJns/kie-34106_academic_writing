texname = assignment

tyoselostus: $(texname).tex $(wildcard *.tex) $(texname).bib
	rubber --pdf $(texname).tex

clean: $(texname).tex
	rubber --clean $(texname).tex
