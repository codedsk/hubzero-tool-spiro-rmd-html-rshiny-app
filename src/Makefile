BINDIR = ../bin

RMDFILE = spirograph_embedded_shiny_app.Rmd

all:

install:
	install --mode 0444 -D ${RMDFILE} ${BINDIR}/${RMDFILE}

clean:

distclean: clean
	rm -rf ${BINDIR}/${RMDFILE}

.PHONY: all install clean distclean

