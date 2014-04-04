all:
	latex pract10.tex
	latex pract10.tex
	bibtex pract10
	latex pract10.tex
	latex pract10.tex
	dvips -o pract10.ps pract10.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true pract10.ps pract10.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl
