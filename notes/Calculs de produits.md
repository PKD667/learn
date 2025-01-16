### Le symbole $\prod$ 

Le symbole $\prod$ (Pi majuscule) représente le produit, il permet de multiplier une suite de nombres. 

### Définition formelle
Soient $n$ un entier de $\mathbb{N}^{\star}$ et $a_1,a_2,...,a_n$ des réels.
On appelle **produit des $a_k$ pour $k$ allant de $1$ à $n$** le réel, noté $\displaystyle\prod_{k=0}^{n}$ défini par :
$$ \prod_{k=0}^{n} = a_1 \times a_2 \times \cdots \times a_n$$
Soient $m,n$ des entiers de $\mathbb{Z}$ tels que $m \leq n$ et $a_m,a_{m+1},...,a_n$ des réels.
On appelle **prod des $a_k$ pour $k$ allant de $m$ à $n$** le réel noté $\displaystyle\prod_{k=m}^{n}$ défini par :
$$
\prod_{k=m}^{n} = a_m \times a_{m+1} \times \cdots \times a_n*
$$

Aussi notée $\displaystyle \prod_{m \leq k \leq n} a_k$ ou $\displaystyle\prod_{k \in [m;n]} a_k$

**Par convention, on considère que $\displaystyle\prod_{k=m}^{n}$ est nul si $n \leq m$**
#### Représentation algorithmique
Une somme **pour $k$ allant de $m$ à $n$** correspond au code suivant : 
```c
for (int k = m; k <= n; k++) {
	s *= a(k)
}
```
`s` représente ici la valeur finale du programme, et `a(x)` la fonction qui associe $k$ à $a_k$ 

### Règles de calculs

#### Relation de Chasles

Soient $m,n,p$ des entiers de $\mathbb{Z}$ tels que $m \leq p \leq n$ et $a_m, a_{m+1},\dots,a_n$ des réels :
$$
\prod_{k=m}^n = \prod_{k=m}^p \times \prod_{k=p+1}^n
$$
#### Découpage

Soient $m,n$ des entiers de $\mathbb{Z}$ tels que $m \leq n$, $a_m,a_{m+1},\dots,a_n$, $b_m,b_{m+1},\dots,b_m$ des réels et $\lambda$ un réel.
On a : 
$$
\prod_{k=m}^n (a_k \times b_k) = \prod_{k=m}^n a_k \times \prod_{k=m}^n b_k
$$ 
et 
$$
\prod_{k=m}^n (\lambda a_k) = \lambda^{n-m+1} \prod_{k=m}^n a_k
$$
*Il n'existe pas de formule pour calculer un produit de sommes .*

#### Produits télescopiques

Soient $m,n$ des entiers de $\mathbb{Z}$ tels que $m \leq n$ et $a_m,a_{m+1},\dots,a_n,a_{n+1}$ des réels.
On a : 
$$
\prod_{k=m}^n \frac{a_k}{a_{k+1}}  = \frac{a_m}{a_{n+1}}
$$
#### Logarithme d'un produit

Soient $m,n$ des entiers de $\mathbb{Z}$ tels que $m \leq n$ et $a_m,a_{m+1},\dots,a_n$ des réels.
On à : 
$$
\ln \left( \prod_{k=m}^{n} a_k \right) = \sum_{k=m}^n \ln(a_k)
$$