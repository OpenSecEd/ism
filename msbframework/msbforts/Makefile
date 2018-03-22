.PHONY: all
all: msbforts.pdf

FILES=		msbforts.tex literature.tex msbforts.bib
FILES+= 	gap-betyg.png gap-kapitel.png gap-nivafragor.png
FILES+= 	gap-sammanstallning.png infora.png infosak-levels.png
FILES+= 	infosak-process.png miun-klassificering.png
FILES+= 	miun-klassresultat.png msb-atgarder.png
FILES+= 	msb-klassificering.png overvakning.png riskmatris.png

msbforts.pdf: ${FILES}


.PHONY: clean
clean:
	${RM} msbforts.pdf


INCLUDE_MAKEFILES=../../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
