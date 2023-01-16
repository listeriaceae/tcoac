# [The Cost of a Cloud: Research Problems in Data Center Networks][TCOAC]

This repository contains the slides for a presentation on the article written
by Albert Greenberg, James Hamilton, David A. Maltz and Parveen Patel on 2008.

## Build

 - Requires `pandoc(1)` and a PDF engine.

```sh
$ pandoc cost.md --bibliography=references.bib --biblatex -t beamer -o pres.pdf
```

[TCOAC]: https://dl.acm.org/doi/pdf/10.1145/1496091.1496103
