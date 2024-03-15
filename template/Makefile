.PHONY: clean all
template.pdf: template.tex
	pdflatex $^

clean:
	rm -f *.aux *.out *.log

all: template.pdf