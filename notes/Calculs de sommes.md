### Le symbole $\sum$

Le symbole de somme ou $\sum$ permet d'additionner des nombres d'un manière déterminée. C'est une forme simple d'algorithme. On peut le considérer comme une boucle `for`.

### Définition formelle

Soient $n$ un entier de $\mathbb{N}^{\star}$ et $a_1,a_2,\dots,a_n$ des réels.
On appelle **somme des $a_k$ pour $k$ allant de $1$ à $n$ le réel, noté $\displaystyle\sum_{k=0}^{n}$ défini par :** 
$$ \sum_{k=0}^{n} = a_1 + a_2 + \cdots+ a_n$$
Soient $m,n$ des entiers de $\mathbb{Z}$ tels que $m \leq n$ et $a_m,a_{m+1},\dots,a_n$ des réels.
On appelle **somme des $a_k$ pour $k$ allant de $m$ à $n$ le réel noté $\displaystyle\sum_{k=m}^{n}$ défini par :**
$$\sum_{k=m}^{n} = a_m + a_{m+1} + \cdots + a_n$$

Aussi notée :
$$\sum_{m \leq k \leq n} a_k$$ 
ou
$$ \sum_{k \in [m;n]} a_k$$
#### Représentation algorithmique

Une somme **pour $k$ allant de $m$ à $n$** correspond au code suivant : 
```c
for (int k = m; k <= n; k++) {
	s += a(k)
}
```
`s` représente ici la valeur finale du programme, et `a(x)` la fonction qui associe $k$ à $a_k$ 

### Règles de calculs

#### Relation de Chasles

Soient $m,n,p$ des entiers de $\mathbb{Z}$ tels que $m \leq p \leq n$ et $a_m, a_{m+1},\dots,a_n$ des réels :
$$\sum_{k=m}^n = \sum_{k=m}^p + \sum_{k=p+1}^n$$
#### Découpage

Soient $m,n$ des entiers de $\mathbb{Z}$ tels que $m \leq n$, $a_m,a_{m+1},\dots,a_n$, $b_m,b_{m+1},\dots,b_m$ des réels et $\lambda$ un réel.
On a : $$\sum_{k=m}^n (a_k + b_k) = \sum_{k=m}^n a_k + \sum_{k=m}^n b_k$$ 
et $$\sum_{k=m}^n (\lambda a_k) = \lambda \sum_{k=m}^n a_k$$
*On ne peut néanmoins pas calculer de la même manière des sommes de produits ou de quotients.*

#### Changement d'indice

Soient $m,n,r$ des entiers de $\mathbb{Z}$ tels que $m \leq n$ et $(a_k)_{k \in \mathbb{Z}}$ une famille de réels.
On a : $$\sum_{k=m}^n a_{k+r} = \sum_{l=m+r}^{n+r} a_l = \sum_{k=m+r}^{n+r} a_k$$
On dit que l'on a effectué le **changement d'indice** $l = k + r$. 
On a aussi: $$\sum_{k=m}^n a_{r-k} = \sum_{l=r-n}^{r-m} a_l = \sum_{k=r-n}^{r-m} a_k$$

Cette méthode de changement d'indice peut servir à simplifier des sommes pour en faire apparaître certaine propriétés.  Elle peut aussi servir à faire apparaître des sommes télescopiques.

#### Sommes télescopiques

Soient $m,n$ des entiers de $\mathbb{Z}$ tels que $m \leq n$ et $a_m,a_{m+1},\dots,a_n,a_{n+1}$ des réels.
On a : $$ \sum_{k=m}^n (a_k - a_{k+1})  = a_m - a_{n+1}$$
