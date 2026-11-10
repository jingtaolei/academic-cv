# Jingtao Lei — Academic CV

LaTeX source and the latest PDF of my academic CV.

- [View / download the CV](Jingtao_Lei_CV.pdf)
- [LaTeX source](Jingtao_Lei_CV.tex)
- [Personal website](https://jingtaolei.github.io/)

## Compile

Use **pdfLaTeX** with a full TeX Live or MacTeX installation. From this directory:

```sh
pdflatex -interaction=nonstopmode -halt-on-error Jingtao_Lei_CV.tex
pdflatex -interaction=nonstopmode -halt-on-error Jingtao_Lei_CV.tex
```

This produces `Jingtao_Lei_CV.pdf`. Required packages include `academicons`,
`fontawesome5`, `cfr-lm`, `tcolorbox`, `geometry`, `titlesec`, and `hyperref`,
along with the other packages listed in the source.

For Overleaf, upload `Jingtao_Lei_CV.tex`, select it as the main document, and
choose pdfLaTeX as the compiler.

The design uses A4 paper, 11 pt Palatino, and dark-blue hyperlinks
(`RGB 0, 70, 140`).

## Update

Edit `Jingtao_Lei_CV.tex`, recompile, and commit both the source and the updated
PDF. The checked-in PDF is the version approved on 10 November 2026.

## Template attribution

Adapted from [Rui Wu's research CV template](https://github.com/RuiWu1123/Rui_CV_Research).
The source credits Dubasi Pavan Kumar as the template author; the existing
attribution is preserved in the LaTeX file.
