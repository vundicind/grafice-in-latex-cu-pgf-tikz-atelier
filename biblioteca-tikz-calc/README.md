Biblioteca **calc**
===================

Instrucțiuni
------------

1. Descărcați fișierul `biblioteca-tikz-calc.tex` (sau copiati conținutul acestuia într-un fișier local) și deschideți-l într-un editor LaTeX (de exemplu, [Texmaker](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier#editoare-latex)).

2. Compilați fișierul local cu `pdflatex`. În rezultat trebuie să obțineți un fișier PDF asemănător cu `biblioteca-tikz-calc.pdf`.

Explicații
----------

Facilitățile standard TikZ pot fi extinse cu ajutorul bibliotecilor TikZ și a altor pachete bazate pe PGF+TikZ.
Bibliotecile TikZ se includ în documentul LaTeX cu ajutorul comenzii `\usetikzlibrary`. 
Evident, nu putem folosi `\usetikzlibrary` fără a fi apelat preventiv `\usepackage{tikz}`.
Specificul bibliotecilor `TikZ` este că pot extinde lista parametrilor și valorile acestora pentru comenzile TikZ existente.

O bibliotecă utilă în construcția de figuri geometrice este biblioteca `calc`.
Această bibliotecă oferă suport pentru efectuarea operațiilor cu coordonatele punctelor.
Se include cu `usetikzlibrary{calc}`.
