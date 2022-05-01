SHELL = /bin/sh

PREFIX = /usr
NAME = xshbar

help:
	@echo "make install          Install xshbar."
	@echo "make uninstall        Remove xshbar."

install:
	cp ${NAME} ${DESTDIR}${PREFIX}/bin
	chmod +x ${DESTDIR}${PREFIX}/bin/${NAME}

uninstall:
	rm -f ${DESTDIR}${PREFIX}/bin/${NAME}
