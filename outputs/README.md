# Compiled Outputs

This directory contains compiled PDF documents from the dissertation.

## Directory Structure

```
outputs/
├── thesis.pdf              # Complete dissertation (when compiled)
├── chapters/               # Individual chapter PDFs
│   ├── ch1-introduction.pdf
│   ├── ch2-hmarl.pdf
│   ├── ch3-feature-evaluation.pdf
│   ├── ch4-distribution.pdf
│   └── ch5-llm-based.pdf
└── papers/                 # Published/submitted conference papers
    ├── hmarl-paper.pdf
    ├── feature-eval-paper.pdf
    ├── model-based-paper.pdf
    ├── flow-rl-paper.pdf
    └── survey-paper.pdf
```

## Building

To regenerate these PDFs, access the private source repository and run:

```bash
cd private-source/Thesis
pdflatex main.tex && bibtex main && pdflatex main.tex && pdflatex main.tex
```

## Notes

- PDFs are generated from the LaTeX source in the private repository
- Individual chapter PDFs may require separate compilation
- Conference papers are in their respective submission formats
