Exemplu de document LaTeX minimal
=================================

Instrucțiuni
------------

1. Descărcați fișierul `document-latex-minimal.tex` (sau copiati conținutul acestuia într-un fișier) și deschideți-l într-un editor LaTeX (de exemplu, [Texmaker](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier#editoare-latex)).

2. Compilați fișierul local cu `pdflatex`. În rezultat trebuie să obțineți un fișier PDF asemănător cu `document-latex-minimal.pdf`.

Explicații
----------

Un document LaTeX se începe cu comanda `\documentclass{<tipul documentului>}`, în cazul nostru `<tipul documentului>` este `article`(articol). Alte valori posibile sînt: `book` (carte), `letter`(scrisoare) etc.

Conținutul documentului se pune înăuntrul cadrului `document`, adică între comenzile `\begin{document}` și `\end{document}`.

Înainte de începutul cadrului `document` putem indica de ce pachete LaTeX avem nevoie folosind comanda `\usepackage`.
