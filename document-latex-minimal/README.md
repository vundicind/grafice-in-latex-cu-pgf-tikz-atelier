Exemplu de document LaTeX minimal
=================================

Descărcați fișierul `document-latex-minimal.tex` (sau copiati conținutul acestuia) și deschideți-l într-un editor LaTeX (de exemplu, [Texmaker](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier#editoare-latex)).
 
După compilare trebuie să obțineți un fișier PDF asemănător cu `document-latex-minimal.pdf`.

Structura unui document LaTeX
-----------------------------

Un document LaTeX se începe cu comanda `\documentclass{<tipul documentului>}`, în cazul nostru `<tipul documentului>` este `article`(articol). Alte valori posibile sînt: `book` (carte), `letter`(scrisoare) etc.

Conținutul documentului se pune înăuntrul cadrului `document`, adică între comenzile `\begin{document}` și `\end{document}`.

Înainte de începutul cadrului `document` putem indica de ce pachete LaTeX avem nevoie folosind comanda `\usepackage`.
