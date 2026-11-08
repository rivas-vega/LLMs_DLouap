LECTURE 3 - PRETRAINING
Lecture notes for the 2026 MVA course on large language models.
Lecture 3: Pretraining. David Louapre, Hugging Face.

Optimization, scaling laws, data curation, and computational efficiency.

Repository: https://github.com/rivas-vega/LLMs_DLouap

CONTENTS
- main.tex: main LaTeX document.
- 01_*.tex through 13_*.tex: chapters and appendices.
- references.bib: 34 primary papers, reports, and technical references.
- main.bbl: prebuilt bibliography for convenience.
- figures/: 67 original figure crops from the supplied slides.
- evidence/figure_manifest.json: source PDF part, one-based page, and crop
  rectangle in PDF points for each figure.

BUILD
Unzip this archive and run from this directory:
    latexmk -pdf main.tex
Alternatively:
    pdflatex main.tex
    bibtex main
    pdflatex main.tex
    pdflatex main.tex
Use a current TeX Live or MiKTeX installation with the common packages listed in
main.tex. On Overleaf, upload this archive and select main.tex as the main file;
use pdfLaTeX. All files needed to compile the manuscript are included.

SOURCE CONVENTIONS
P1 is lecture03 part1.pdf (90 pages); P2 is lecture03 part2.pdf (33 pages).
The chapters state concepts and experimental results directly, with mathematical
derivations and context from primary sources. Appendix A documents substantive clarifications,
uncertain figures, figure provenance, and the blank plot on P1:88.
The original experiments have not been rerun. Added explanations are
independent study material. Original figure labels are retained; duplicate
slide appearances are consolidated.

The final PDF was compiled, checked for unresolved references and overflow,
and rendered for visual review. The source package was compiled independently.
