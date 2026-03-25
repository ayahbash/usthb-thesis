# usthb-thesis

a simplified latex thesis template adapted for usthb requirements, based on the [original template](https://github.com/Yacine-Bouali/USTHB-Thesis) by [Yacine Bouali](https://github.com/Yacine-Bouali).

intended mostly for students from the **faculty of computer science (usthb)** writing a **bachelor's or master's thesis (pfe)** or an **internship report**, but can be adapted for other departments as well.

## structure

```
usthb-thesis/
├── chapters/
│   ├── abstract.tex
│   ├── acknowledgements.tex
│   ├── appendix.tex
│   ├── chapter1.tex
│   ├── chapter2.tex
│   ├── chapter3.tex
│   ├── conclusion.tex
│   └── introduction.tex
├── images/
├── LICENSE
├── main.tex
├── preamble.tex
├── README.md
├── references.bib
└── titlepage.tex
```

## what changed from the original

- simpler and flatter file structure - all chapters in one folder
- preamble cleaned up and adapted for licence/master level (no phd-specific packages)
- title page adapted for internship reports and pfe (licence/master)
- english as default language, easy to switch to french
- example files updated with more relevant and practical examples

## usage

1. clone or download the repo
2. edit `titlepage.tex` with your info
3. fill in your chapters under `chapters/`
4. add your references to `references.bib`
5. compile `main.tex` with your latex compiler (overleaf, texlive, etc.)

> tip: the easiest way is to upload the repo directly to [overleaf](https://www.overleaf.com)

## useful resources
- [latex cheat sheet (pdf)](https://wch.github.io/latexsheet/latexsheet-a4.pdf) - one-page reference for common latex commands  
- [overleaf](https://www.overleaf.com) – online latex editor and documentation

## credits
forked and adapted from [Yacine Bouali](https://github.com/Yacine-Bouali)'s original template - also available on [overleaf](https://www.overleaf.com/latex/templates/usthb-thesis/jwbcnbcgrkdq).

## license

MIT - feel free to use, modify, and share!