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

1. **un set de puncte**;

2. **fișier cu coordonatele punctelor în formă tabelară**;

3. **formulă PGF** (expresie matematică pentru motorul matematic din PGF);

4. **formulă [Gnuplot](http://gnuplot.info/)**.

Pentru fiecare dintre cazurile de mai sus, formatul de „apelare” a operației `plot` este diferit. 
În cazul cînd vrem să trasăm un grafic avînd: 

1.  **un set de puncte**; formatul de folosire a operației este:

    `plot[<opțiuni>] coordinates {(<punct 1>) (<punct 2>) ... (<punct n>)}`

2. **un set de puncte într-un fișier**; formatul de folosire a operației este:

    `plot[<opțiuni>] file {<cale fișier>}`

3. **o formulă PGF**; formatul de folosire a operației este:

    `plot[<opțiuni>] (<formula pentru x>,<formula pentru y>)`

4. **o formulă Gnuplot**; formatul de folosire a operației este:

    `plot[<opțiuni>] function {<formulă Gnuplot>}`

### Motorul matematic PGF

Motorul matematic al PGF-ului recunoaște următoarele **operații**[1, p. 527] și **funcții**[1, p.529].

#### Operații

* `x+y`
* `x-y`
* `-x` 
* `x*y`
* `x/y`
* `x^y` (`x` la puterea `y`) 
* `x!` (`x` factorial) 
* `xr` (convertește `x` din radiani în grade)

#### Funcții

* `abs` (valoarea absolută)
* `acos` (arc cosinus, argumentul se dă în grade)
* `asin` 
* `atan`
* `atan2` (`atan2(x,y)`=`atan(x/y)`)
* `bin` (convertește în baza 2)
* `ceil` (`ceil(x)` - cel mai mic număr întreg mai mare decît `x`)
* `cos`
* `cosec`
* `cosh`
* `cot`
* `deg` (`deg(x)` - convertește `x` în grade din radiani)
* `div` (`div(x,y)` - împarte `x` la `y` și rotungește rezultatul pînă la cel mai apropiat număr întreg)
* `divide` (`div(x,y)` - împarte `x` la `y`)
* `e` (constanata E)
* `factorial`
* `floor`
* `frac` (partea fracționară)
* `hex` (convertește în baza 16 folosind minusculele)
* `Hex`
* `ln` (logaritm natural)
* `log10`
* `log2`
* `max` (`max(x1,x2,...,xn)` - argumentul maximal)
* `min`
* `mod` 
* `Mod`
* `oct` (convertește în baza 8)
* `pi` (constanta PI)
* `pow` (`pow(x,y)` - `x` ridicat la puerea `y`)
* `rad` (`rad(x)` - convertește `x` în radiani din grade)
* `rand` (generează un număr aleator între -1 și 1)
* `random` (`random(x,y)` - generează un număr aleator întreg între `x` și `y`)
* `rnd`
* `round`
* `sec`
* `sin`
* `sinh`
* `sqrt`
* `tan`
* `tanh`
