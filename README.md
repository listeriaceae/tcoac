# [The Cost of a Cloud: Research Problems in Data Center Networks][TCOAC]

This repository contains the slides for a presentation on the article written
by Albert Greenberg, James Hamilton, David A. Maltz and Parveen Patel on 2008.

## Requirements

 - `pandoc(1)`.
 - a PDF engine (e.g., `tectonic`).
 - a BibLaTeX processor (for bibliography, e.g., `biber(1)`).

## Build

```sh
pandoc cost.md --bibliography=references.bib --biblatex --pdf-engine=tectonic -t beamer -o presentation.pdf
```

[TCOAC]: https://dl.acm.org/doi/pdf/10.1145/1496091.1496103
