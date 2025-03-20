all: pdf clean

pdf: SwissRepro24-Samuel-Pawel.Rnw
	R -e 'knitr::knit2pdf("SwissRepro24-Samuel-Pawel.Rnw")'

clean:
	-rm *.tex *.aux  *.blg  *.log  *.bbl *.out *.brf *.synctex.gz
	#-rm -r ./figure/
