.PHONY: all
all: msbintro.pdf

FILES=		msbintro.tex literature.tex msbintro.bib
FILES+= 	infosak-levels.png infosak-pdca.png infosak-process.png
FILES+= 	infosak-struktur.png lis.png metodstod-overview.png
FILES+= 	miun-atgard.png miun-hot.png miun-klassificering.png
FILES+= 	miun-klassresultat.png miun-riktighet.png miun-riskmatris.png
FILES+= 	miun-tillganglighet.png msb-klassificering.png
FILES+= 	msb-organisation.png riskmatris.png

msbintro.pdf: ${FILES}


.PHONY: clean
clean:
	${RM} msbintro.pdf


INCLUDE_MAKEFILES=../../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
