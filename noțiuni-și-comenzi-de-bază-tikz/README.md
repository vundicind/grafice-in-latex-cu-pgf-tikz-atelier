Noțiuni și comenzi de bază TikZ
===============================

Instrucțiuni
------------

1. Descărcați fișierul `noțiuni-și-comenzi-de-bază-tikz.tex` (sau copiati conținutul acestuia într-un fișier) și deschideți-l într-un editor LaTeX (de exemplu, [Texmaker](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier#editoare-latex)).

2. Compilați fișierul local cu `pdflatex`. În rezultat trebuie să obțineți un fișier PDF asemănător cu `noțiuni-și-comenzi-de-bază-tikz.pdf`.

Explicații
----------

### Trasee

În TikZ orice desen se construiește pornind de la noțiunea de **traseu** [en. path]. Prin **traseu** înțelegm - șiruri de segmente și curbe conectate.

Cu traseele putem face 3 operații de bază: **desenare**, **umplere** și **decupare**.

Desenarea se face cu ajutorul comenzii `\draw` care are următorul format general:

    \draw[<opțiuni>] <traseu>;

Opțiunile pot fi: culoarea liniei (color), grosimea liniei (line width), forma capetelor (->,-] etc) etc.
Orice opțiune se specifică folosind fomatul: `<opțiune>=<valoare>` sau, putem scrie doar `<opțiune>`, ceea ce este echivalent cu `<opțiune>=<valoare implicită>`.

Traseul se definește prin puncte și operații de extindere (creștere) a traseului [en. path extension operations].

Operații standard de extindere a traseelor sînt urmatoarele:

* segment; fomatul general: `(<punc de început>) -- (<punct de sfîrșit>)`.
* dreptunghi; fomatul general: `(<colț stînga-jos>) rectangle (<colț dreapta-sus>)`.
* cerc; format general: `(<centru>) circle (<raza>)`.
* elipsă; format general: `(<centru>) ellipse (<semiaxa mare> and <semiaxa mică>)`
* arc de cerc; format general: `(<centru cercului>) arc (<unghi început>:<unghi sfîrsit>:<raza>)`.
* grilă; format general: `(<colt stînga-jos>) grid (<colț dreapta-sus>)`.

### Puncte (coordonate)

În TikZ putem da nume la puncte pentru ca ulterior să folosim aceste nume în loc să scriem direct coordonatele punctelor.

Comanda pentru asocierea punctelor cu nume are formatul:

    \coordinate[<opțiuni>] (<nume punct>) at (<coordonate punct>);

De exemplu

    \begin{tikzpicture}    
      \coordinate (A) at (0,0);
      \coordinate (B) at (45:1);
            
      \draw (A) -- (B);
    \begin{tikzpicture}
    
### Modalități de specificare a coordonatelor

TikZ oferă mai multe modalități de speficiare a coordonatelor:

* coordonate carteziene: `(<x>,<y>)` sau `(<x>,<y>,<z>)`.

* coordonate polare: `(<unghi>,<rază>)`.

* coordonate relative: `+(<x>,<y>)`, `-(<x>,<y>)` sau `++(<x>,<y>)`, `--(<x>,<y>)`.
