# Academic Report Template

This repository contains the source code for a template style academic report (forked from Michae Gale's CS310 report repository and combined with elements of his haskell guide).

It contains:
1. Automatic code highlighting
2. Maths syntax support
3. Automatic referencing from a bibliography file
4. An example timeline

To generate the pdf similar to the example please use:
`pdflatex [-shell-escape] progress-report.tex`\\
`bibtex progress-report.aux`\\
`pdflatex [-shell-escape] progress-report.tex`\\
`pdflatex [-shell-escape] progress-report.tex`\\

`-shell-escape` is used if the document contains code
