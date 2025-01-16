### Sommes usuelles

#### Somme de constante

Soit $\lambda$ un réel.
Pour tout $n \in \mathbb{N}^\star$, $\displaystyle\sum_{k=1}^{n} \lambda = n \times \lambda$.
Plus généralement, pour tout $m,n$ de $\mathbb{Z}$ tels que $m \leq n$, $\displaystyle\sum_{k=m}^{n} \lambda = (n-m+1) \times \lambda$
*Attention aux off-by-one errors. On oublie pas le $+1$*


#### Somme arithmétique 
*Somme de gauss*

Pour tout $n \in \mathbb{N}^\star$, $\displaystyle\sum_{k=0}^{n} k = \frac{n(n+1)}{2}$ 
Plus généralement, pour tout $m,n$ de $\mathbb{Z}$ tels que $m \leq n$ :
$$
\displaystyle\sum_{k=m}^{n}k = \frac{(n-m+1)(n+m)}{2}
$$

#### Somme géométrique

Soient $n,m \in \mathbb{N}$ tels que $m \leq n$, $q \in \mathbb{R}$,  
$$
\begin{equation}
\sum_{k=m}^{n}q^k = 
\begin{cases} 
q^m \times \frac{1-q^{n-m+1}}{1-q}\\
n-m+1 \\
\end{cases}
\end{equation}
$$

#### Sommes d'Euler

$$\sum_{k=0}^n k^2 = \frac{n(n+1)(2n+1)}{6}$$
$$\sum_{k=0}^n k^3 = \left( \frac{n(n+1)}{2} \right)^2$$


### Produits Usuels

#### factorielle
*La factorielle est un produit utilisé dans de nombreux domaines comme le dénombrement*

Soit $n \in \mathbb{N}^\star$, on définit $\displaystyle n! = \prod_{k=1}^n k$
Par convention on définit aussi $0! = 1$

#### Coefficient binomial

Soient $n,p \in \mathbb{N}, p \leq n$, on définit $\displaystyle\binom{n}{p} = \frac{p!}{p!(n-p)!}$

 - Pour tout $n \in \mathbb{N}$, $\displaystyle\binom{n}{0} = \binom{n}{n} = 1$
 - Pour tout $n \in \mathbb{N}^\star$, $\displaystyle\binom{n}{1} = \binom{n}{n-1} = n$
 - Pour tout $n \in \mathbb{N}, n \geq 2$, $\displaystyle\binom{n}{2} = \binom{n}{n-2} = \frac{n(n-1)}{2}$
 - Pour tout $n,p \in \mathbb{N}, n \geq p$, $\displaystyle\binom{n}{p} = \binom{n}{n-p}$  
 - Pour tout $n,p \in \mathbb{N}, 1 \leq p \leq n$, $\displaystyle\binom{n}{p} = n\binom{n-1}{p-1}$
*Formule de pascal*
 - Pour tout $n,p \in \mathbb{N}, 1 \leq p \leq n-1$, $\displaystyle\binom{n-1}{p-1} + \binom{n-1}{p} = \binom{n}{p}$

#### Formule du binôme

Soient $a,b$ deux réels et $n$ un entier de $\mathbb{N}$
$$ (a + b)^n = \sum_{k=0}^{n} \binom{n}{k} a^k b^{n-k} = \sum_{k=0}^{n} \binom{n}{k} b^k a^{n-k}$$








