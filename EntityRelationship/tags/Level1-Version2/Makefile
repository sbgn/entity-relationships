# =============================================================================
# Top-level Makefile for the SBGN Entity Relationship specification.
#
# $HeadURL: https://sbgn.svn.sourceforge.net/svnroot/sbgn/trunk/documents/specifications/EntityRelationship/Level1/Makefile $
# =============================================================================

MAIN   = sbgn_ER-level1

LATEX  = pdflatex
BIBTEX = bibtex

all default:
	$(LATEX) $(MAIN).tex
	$(LATEX) $(MAIN).tex
	$(BIBTEX) $(MAIN)
	$(LATEX) $(MAIN).tex

# Clean up temporary files
clean:
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.log
	rm -f *.lox
	rm -f *.out
	rm -f *.toc

# Clean up temporary files and PDF output
distclean:
		rm -f *.aux
		rm -f *.bbl
		rm -f *.blg
		rm -f *.log
		rm -f *.lox
		rm -f *.out
		rm -f *.toc
		rm -f *.pdf
