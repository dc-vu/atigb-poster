# ATIGB Poster Project

This project contains the LaTeX source code and resources for generating an academic poster using the Beamer class, suitable for conferences or scientific presentations.


## 📌 Requirements

To compile the poster, you will need:
- LaTeX distribution (e.g. TeX Live or MikTeX)
- PDFLaTeX or LuaLaTeX
- `beamerposter` package
- `biblatex` or `natbib` (depending on the citation setup)

## 🚀 Build Instructions

You can compile the poster using the following commands:

```bash
pdflatex poster.tex
bibtex poster
pdflatex poster.tex
pdflatex poster.tex

