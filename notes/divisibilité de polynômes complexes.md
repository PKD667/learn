#### Définition :
Soit $P_1$ et $P_2$ deux fonctions polynômes.
on dit que $P_1$ **est divisible par** $P_2$ ou que $P_1(z)$ **est factorisable par** $P_2(z)$ s'il existe une fonction polynôme $P_3$ tel que, pour tout complexe $z$ : $P_1(z)=P_2(z)\cdot P_3(z)$. 

#### Théorème 1 :
Soient $z$ et $a$ deux nombres [complexes](complexe) :
$$
\begin{align}
\forall n\in\mathbb N: z^n-a^n &= (z-a)(z^{n-1}+az^{n-2}+\cdots+a^{n-2}z+a^{n-1}) \\ \\
&=(z-a)\sum_{k=0}^{n-1}a^kz^{n-1-k}
\end{align}
$$
##### Démonstration :
On pose :$(z-a)(z^{n-1}+az^{n-2}+\cdots+a^{n-2}z+a^{n-1})=P(z)$. 
$$
\begin {align}
P(z) &= (z^{n}+\cancel{az^{n-1}}+\cancel{\cdots}+\cancel{a^{n-2}z^2}+\cancel{a^{n-1}z}-\cancel{az^{n-1}}-\cancel{a^2z^{n-2}}+\cancel{\cdots}+\cancel{a^{n-1}z}+a^{n})\\
P(z) &= z^n-a^n
\end{align}
$$
#### Théorème 2 :
Soit $P$ une fonction polynôme.
$$
\begin{cases}
\text{P(z) est divisible par (z-a)} \\
\Updownarrow \\
\text{P(a) = 0} \\
\Updownarrow \\
\text{a est une racine de P}
\end{cases}
$$
### Démonstration

#### $P(z) \text{ divisible par } (z-a) \implies P(a) = 0$
Supposons que P(z) soit factorisable par (z-a). Alors :
- $\exists R(z)$ polynôme tel que :
$$
\forall z\in\mathbb{C},~P(z)=R(z)\cdot(z-a)
$$
- En évaluant en a :
$$P
(a)=R(a)\cdot(a-a)=R(a)\cdot 0=0
$$
Donc a est une racine de P.

#### $P(a) = 0 \implies P(z) \text{ divisible par } (z-a)$
Soit $P$ le polynôme défini sur $\mathbb{C}$ par :
$$
P(z)=b_nz^n+b_{n-1}z^{n-1}+\cdots+b_1z+b_0
$$
avec $(b_0,b_1,\ldots,b_n)\in\mathbb{C}^{n+1}$ et $b_n\neq 0$

On a $P(a) = 0$, donc :
$$
b_na^n+b_{n-1}a^{n-1}+\cdots+b_1a+b_0=0
$$

On peut écrire :
$$
P(z)-P(a)=P(z)
$$

Donc :
$$
P(z)=b_n(z^n-a^n)+b_{n-1}(z^{n-1}-a^{n-1})+\cdots+b_1(z-a)
$$