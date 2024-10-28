[homepage](index.md)

# Inserarea ecuatiilor si formulelor `Mathjax`

**sintaxa**

Formulele `Mathjax` sunt inserate in acceasi linie daca sunt plasate intr-o pereche de simbpluri '$'

Exemplu: Aceasta este o ecuatie $a=bc$

Formule 'Latex'(prin mathjax) se introduc pe rand 2 perechi de simboluri '$$'

*Exemplu:* 
$$a=b^c$$

# Ridicarea la putere

Se foloseste meta-caracterul `latex` 

Exemplu:

$$a=10^7$$

# `Subscript` 

Se foloseste meta-caracterul `latexl "_"

*Exemplu:* 

$$a_i=b^c$$

# Grpuarea elementelor din fprmule

Elementele din formule se grupeaza prin meta-caracterele `{` si `}`

$$ 10^{10} $$

# Litere grecesti

*Exemple:*

"\alpha" -alfa mic $$\alpha$$

"\Alpha" -alfa mare $$\Alpha$$

# Parantezele 

- Parantezelerotunde se scriu direct(nu au inteles special 'Latex")

- Parantezelerotunde se scriu drepte(nu au inteles special 'Latex")

-Acoladele , deoarece sunt caractere de grupare, vor di renderizare corect daca sunt "escapade" de la intelesul lor special punand in fata iar

*Exemplu:*

"\frac" 

$$a=\frac((a+bc)(d-e))$$

# Semnele de multiplicare si respectiv diviziune

*Exemplu:*

$$ a=c +10\times x $$

$$ a=c +10\cdot x $$

$$ a=b\div c $$

# Suma de la i=0 la n

**Exemplu:**

$$\sum_{i=0}^n i^2 = \frac {(a+b)\times (b+c)} {6} $$

# Integrale

**Exemple:**

$$ \int _0^1 x^4 dx $$
