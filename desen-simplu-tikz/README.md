Desen simplu cu TikZ
====================

Instrucțiuni
------------

1. Descărcați fișierul `desen-simplu-tikz.tex` (sau copiati conținutul acestuia într-un fișier) și deschideți-l într-un editor LaTeX (de exemplu, [Texmaker](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier#editoare-latex)).

2. Compilați fișierul local cu `pdflatex`. În rezultat trebuie să obțineți un fișier PDF asemănător cu `desen-simplu-tikz.tex.pdf`.

Explicații
----------

Comanda `\usepackage[utf8x]{inputenc}` este necesară pentru a introduce literele cu diacritice în format unicode.

Un desen TikZ se programează înăuntrul cadrului `tikzpicture`:

    \begin{tikzpicture}
    ...
    \end{tikzpicture}    
