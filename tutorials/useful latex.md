# Useful `LaTeX` Equations



## General
Name | Code | Result
| :- | :- | :- |
therefore | `\therefore` | $\therefore$
equivalent to | `\equiv` | $\equiv$
square root | `\sqrt{x}` | $\sqrt{x}$
n-th root | `\sqrt[n]{x}` | $\sqrt[n]{x}$
times | `\times` *or* `\cdot` | "$\times$" *or* " $\cdot$ "
not equals | `\neq` | $\neq$
exponent | `x^{something}` | $x^{something}$
subscript | `x_{something}` | $x_{something}$
sumation | `\sum_{i=0}^{100}f(i)` | $$\sum_{i=0}^{100}f(i)$$
limit | `\lim_{x\rightarrow\infty}x` | $$\lim_{x\rightarrow\infty}x$$
fraction | `\frac{x}{y}` | $$\frac{x}{y}$$

## Domains 
Name | Code | Result | Values
| :- | :- | :- | :- |
Natural Numbers | `\mathbb{N}` | $\mathbb{N}$ | $0,1,2,3,\ldots$
Whole Numbers | `\mathbb{W}` | $\mathbb{W}$ | Same as Natural for CS2050 purposes
Positive Integers | `\mathbb{Z}^+` | $\mathbb{Z}^+$ | $1,2,3,\ldots$
Integers | `\mathbb{Z}` | $\mathbb{Z}$ | $\ldots,-2,-1,0,1,2,\ldots$
Rational Numbers | `\mathbb{Q}` | $\mathbb{Q}$ | Anyting expressible as a fraction
Irrational Numbers | `\mathbb{I}` | $\mathbb{I}$ | Anything real that isn't rational i.e. $\mathbb{R}-\mathbb{Q}$
Complex Numbers | `\mathbb{C}` | $\mathbb{C}$ | *Imaginaryyyyy*
Real Numbers | `\mathbb{R}` | $\mathbb{R}$ | Everything not complex

*The definition of Natural Numbers varies a lot. For CS 2050, we consider 0 to be a natural number. Some consider 0 not to be, and have $\mathbb{W}$ represent $0,1,2,\ldots$ instead.*

## Logical Equivalences

Name | Code | Alt Code | Result
| :- | :- | :- | :- |
Negation | `\neg` | `lnot` | $\neg$
AND | `\wedge` | `\land` | $\wedge$
OR | `\vee` | `\lor` | $\vee$
XOR | `\oplus` |  | $\oplus$
Implies | `\rightarrow` | `\Rightarrow` | $\rightarrow, \Rightarrow$
Biconditional / IFF | `\leftrightarrow` |  | $\leftrightarrow$


## Quantifiers
Name | Code | Alt Code | Result
| :- | :- | :- | :- |
Forall | `\forall` |  | $\forall$
Exists | `\exists` |  | $\exists$

*Make sure to have a space after each command since `\forallx` for instance will cause errors.*



## Sets

Name | Code | Result
| :- | :- | :- |
Union | `\cup` | $\cup$
Intersection | `\cap` | $\cap$
Complement (c) | `S^c` | $S^c$
Complement (bar) | `\bar{S}` | $\bar{S}$
Difference | `\setminus` `\\` | $\setminus$ (backslash is a special operator) *or* </br>`-` just use a minus sign
Empty set | `\empty` `\emptyset` `\{\}`| $\emptyset$ *or* { }
Power set | `\mathbb{P}(S)` | $\mathbb{P}(S)$
Element of / in | `\in` | $\in$
Not element of / not in | `\notin` | $\notin$




powerset
empty set 
showing the {} brackets
element of 
not element of / not in


## Counting

Name | Code | Alt Code | Result
| :- | :- | :- | :- |
Binomial Coefficient | `{n \atop c}` | `\binom{n}{c}` | $$\binom{n}{c}$$
Multinomial Coefficient | `{n \atop a,b,c,d}` | `\binom{n}{a,b,c,d}` | $$\binom{n}{a,b,c,d}$$

> *Note that `\binom{n}{c}` requires the import `\usepackage{amsmath}` . It is already included in our provided templates.*


