Grafice în LaTeX cu PGF+TikZ
============================

Bine ați venit la atelier!

Ce sînt PGF și TikZ?
--------------------
**PGF** este un pachet de grafică vectorială pentru **LaTeX**.
Denumirea este o abreviere pentru **P**ortable **G**raphic **F**ormat (Format Grafic Portabil).
PGF oferă două seturi de comenzi pentru producerea imaginilor, numite **PGF** și **TikZ**.
Din acest motiv în literatură, deseori, pachetul PGF este referit prin tandemul de nume **PGF/TikZ** sau **PGF+TikZ**.

Comenzile PGF sînt comenzi obișnuite LaTeX.
Pe cînd comenzile TikZ au o sintaxă diferită - mai compactă, respectiv mai comodă pentru utilizatori.
Însă din punct de vedere tehnic comenzile TikZ nu sînt altceva decît scurtături pentru comenzile PGF.

Cu ajutorul PGF+TikZ se pot realiza imagini în formatele PDF, PostScript, DVI și SVG.
Mai mult, acest pachet este compatibil cu toate distribuțiile LaTeX pentru sisteme de operare GNU/Linux, Unix, MS Windows și OSX [1].

Ce este LaTeX?
--------------

**LaTeX** este un sistem de tehnoredactare bazat pe **TeX**. Procesul de tehnoredactare a unui document în LaTeX constă de fapt în programarea aspectului documentului cu ajutorul macroinstrucțiunilor (comenzilor) oferite de LaTeX.

**TeX**, la rîndul său, este la fel un sistem de tehnoredactare, doar că limbajul (setul de comenzi) pus la dispoziție pentru tehnoredactare este de nivel mai scăzut decît cel oferit de LaTeX.

Atît setul de comenzi TeX cît și comenzile LaTeX pot fi extinse prin așa numitele pachete. Cea mai mare bază de date de pachete libere pentru LaTeX se asflă pe [The Comprehensive TeX Archive Network](http://ctan.org/).

Programul (agenda) atelierului
------------------------------

1. Vom începe cu un [exemplu de document latex minimal](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier/tree/master/document-latex-minimal).
2. Apoi vom examina un [desen simplu realizat cu TikZ](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier/tree/master/desen-simplu-tikz).
3. Pentru a purcede mai departe cu celelate lucrări trebuie să facem cunoștință cu [noțiunile și comenzile de bază ale TikZ](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier/tree/master/notiuni-si-comenzi-de-baza-tikz).
4. Să vedem acum cum putem [determina și eticheta punctele de intersecție a două drepte](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier/tree/master/puncte-de-intersectie-si-noduri).
5. Iarși determinarea punctelor folosind [biblioteca calc](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier/tree/master/biblioteca-tikz-calc).
6. Finalizăm cu [grafice de funcții](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier/tree/master/grafice-de-functii).

Adrese recomandate pentru cei care doresc să studieze mai departe PGF+TikZ sau chiar LaTeX
------------------------------------------------------------------------------------

* Diverse [exemple de desene realizate cu PGF+TikZ](http://www.texample.net/tikz/examples/) pe situl http://www.texample.net/.
 
* [Articol introductiv privind TikZ](http://cremeronline.com/LaTeX/minimaltikz.pdf).
 
* [Breviar de comenzi TikZ](http://wwwp.cord.edu/faculty/ahendric/tex/TikZcheatsheet.pdf).
 
* [Pachete pentru reprezentarea grafurilor și figurilor geometrice](http://altermundus.fr/pages/tkz.html) bazate pe TikZ. 

* [Diapozitive pentru cursul de teoria grafurilor în care reprezentările grafurile sînt realizate cu pachetul tkz-graph ](https://github.com/vundicind/grafuri-note-de-curs).

* Diverse [exemple de grafice de funcții realizate cu pachetul PGFPlots](http://pgfplots.sourceforge.net/gallery.html).
 
* [Articol introductiv privind trasarea graficelor de funcții cu pachetul PGFPlots](http://www.math.ufl.edu/~mgluck/GraphingInLatex.pdf).

* [O trecere în revistă a principalelor instrumente LaTeX pentru realizarea de reprezentări  grafice](http://www.latex-project.org/guides/lgc2-excerpts.pdf).

* Ghidul [LaTeX prin exemple](http://www.math.md/files/download/epublications/latex_prin_exemple.pdf).
 
* [Resurse legate de LaTeX selectate de mine](http://vundicind.blogspot.com/2013/02/latex-adrese-cu-continut-interesant.html).

Editoare LaTeX
--------------

* [Texmaker](http://www.xm1math.net/texmaker/), disponibul sub licența [GPL](https://www.gnu.org/licenses/gpl.html) pentru Linux, Windows, MacOS și OS/2.

Editoare LaTeX online
---------------------

* [ShareLaTeX](https://www.sharelatex.com/).
* [writeLaTeX](https://www.writelatex.com/).
 
Referințe bibliogarfice
-----------------------

[1] Tantau T. **The Tik Z and PGF Packages**. Manual for Version 2.10. Institut für Theoretische Informatik. Universität zu Lübeck, Germany: 2010. Disponibil pe Internet: ftp://ftp.gust.org.pl/TeX/graphics/pgf/base/doc/generic/pgf/pgfmanual.pdf. Consultat la 26.10.2012.

Licența atelierului
-------------------

Materialele acestui atelier sînt puse la dispoziţie sub licența [Atribuire - Distribuire-în-condiţii-identice 3.0 Ne-adaptată (CC BY-SA 3.0)](https://creativecommons.org/licenses/by-sa/3.0/deed.ro).
