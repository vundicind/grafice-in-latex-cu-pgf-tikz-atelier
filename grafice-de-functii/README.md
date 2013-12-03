Grafice de funcții
==================

Instrucțiuni
------------

1. Descărcați fișierul `grafice-de-functii.tex` (sau copiati conținutul acestuia într-un fișier local) și deschideți-l într-un editor LaTeX (de exemplu, [Texmaker](https://github.com/vundicind/grafice-in-latex-cu-pgf-tikz-atelier#editoare-latex)).

2. Compilați fișierul local cu `pdflatex`. În rezultat trebuie să obțineți un fișier PDF asemănător cu `grafice-de-functii.pdf`.

Explicații
----------

Trasarea graficelor de funcții în TikZ poate fi realizată folosind operația (de extindere a traseului) `plot`[1, p. 233].

Acestă operație poate trasa grafice de funcții pornind de la 

1. un set de puncte;

2. fișier cu coordonatele punctelor în formă tabelară;

3. formulă PGF (expresie matematică pentru motorul matematic din PGF);

4. formulă [Gnuplot](http://gnuplot.info/).

Pentru fiecare dintre cazurile de mai sus, formatul de „apelare” a operației `plot` este diferit. 
În cazul cînd vrem să trasăm un grafic avînd: 

1.  un set de puncte, formatul operației este:

    plot[\<opțiuni\>] coordinates {(\<punct 1\>) (\<punct 2\>) ... (\<punct n\>)}

2. un set de puncte într-un fișier, formatul operației este:

    plot[\<opțiuni\>] file {\<cale fișier\>}

3. o formula, formatul operației este:

    plot[\<opțiuni\>] (\<formula pentru x\>,\<formula pentru y\>)

4. o formulă Gnuplot, formatul operației este:

    plot[\<opțiuni\>] function {\<formulă Gnuplot\>}

### Motorul matematic PGF

Motorul matematic al PGF-ului recunoaște următoarele operații[1, p. 527] și funcții[1, p.529].

#### Operații

* x+y 
* x-y
* -x 
* x*y
* x/y
* x^y (x la puterea y) 
* x! (x factorial) 
* xr (convertește x din radiani în grade)

#### Funcții

<table>
<tr>
<td>
* abs
* acos
* add
* and
* array
* asin
* atan
* atan2
* bin
* ceil
* cos
</td>
<td>
cosec
cosh
cot
deg
depth
div
divide
e
equal
factorial
false
</td>
<td>
floor
frac
greater
height
hex
Hex
int
ifthenelse
less
ln
log10
</td>
<td>
log2
max
min
mod
Mod
multiply
neg
not
notequal
notgreater
notless
</td>
<td>
oct
or
pi
pow
rad
rand
random
real
rnd
round
sec
</td>
<td>
sin
sinh
sqrt
subtract
tan
tanh
true
veclen
width
</td>
</tr>
</table>
