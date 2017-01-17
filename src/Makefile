BINDIR = ../bin

all:

install:
	install --mode 0444 -D runRMarkdown.R ${BINDIR}/runRMarkdown.R
	install --mode 0444 -D spirograph_embedded_shiny_app.Rmd ${BINDIR}/spirograph_embedded_shiny_app.Rmd

clean:

distclean: clean
	rm -rf ${BINDIR}/runRMarkdown.R
	rm -rf ${BINDIR}/spirograph_embedded_shiny_app.Rmd

.PHONY: all install clean distclean

