
LAB    = DNS_Local
LABPDF = $(LAB).pdf


all: $(LABPDF)


%.pdf: %.tex
	pdflatex $<
	pdflatex $<


clean:
	rm -f *.log *.dvi *.aux *.bbl *.blg *~ *.out *.det 
	@@rm -f *~

