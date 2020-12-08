# natsci
LaTeX Natural Sciences and Mathematics typesetting package

This package assumes that the documents are compiled using XeLaTeX and biblatex 
with biber backend for bibliography.

All that is needed to use the package is to copy natsci.sty into tha same folder
as your .tex file, or into the central location where your LaTeX distribution
looks for packages.

For the list of packages and short descriptions, see the documentation. For some
examples and advice on typesetting, see the style guide.

## LaTeX compatibility
If compiled with LaTeX, natsci package should have similar functionality to the natsci package compiled using XeLaTeX, with following changes:

-   Upright small Greek letters are provided by the package upgreek.
-   Package bm is used for consistent boldening of symbols
-   babel is used instead of polyglossia
-   The standard symbol macro is missing

Tested with the TeXlive 2019.20200218-1.
