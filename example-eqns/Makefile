DOC = example-eqns

TEX = $(wildcard *.tex)
PDF = $(DOC).pdf

TMP := $(DOC).aux $(DOC).log $(DOC).nav $(DOC).out $(DOC).snm $(DOC).toc

all: $(PDF)

$(PDF): $(TEX) $(IMG)
	@xelatex $<
	@xelatex $<
	@xelatex $<

clean:
	@rm -f $(TMP)

distclean: clean
	@rm -f $(PDF)

.PHONY: all clean distclean
