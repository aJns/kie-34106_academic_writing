texname = outline

tyoselostus: $(texname).tex sisalto.tex $(texname).bib
	rubber --pdf $(texname).tex

clean: $(texname).tex
	rubber --clean $(texname).tex
