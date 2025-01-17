#### Définition : 

Soit $n\in\mathbb N$, on appel racine $n^{\text {ieme}}$ de l'unité, l'ensemble des $z\in\mathbb C$ tels que : $$z^n=1$$

#### Résolution de l'équation :

Comme $z\in\mathbb C$, il peut s'écrire de la forme : 

$$
z=re^{i\theta}
$$ où $r\ge 0$ et $\theta\in [0;2\pi[$ 

On a donc :

$$
(re^{i\theta})^n=e^{i0}\iff re^{i\theta n}=e^{i0}
\iff\left\{\begin{array}l

r=1\\
\theta n=0+2k\pi\\
\end {array}
\right.
\iff\left\{\begin{array}l
r=1\\
\theta=\dfrac{2k\pi}{n}\\
\end {array}
\right.
$$

Où $k\in\mathbb Z$ 

Ainsi, les solutions de $z^n=1$ sont de la forme $z=1\cdot e^{i\frac{2k\pi}{n}}$
#### Propriétés :

- La racine $n^{\text nieme}$ de l'unité admet exactement $n$ solutions distinctes.

 Faisons la division euclidienne de $k$ par $n$ : 
 $$
 k=nq+r
$$où $q\in\mathbb Z$ et $r\in [\![0;n-1]\!]$ 

On a :

$$
 z=e^{i\frac{2(nq+r)\pi}{n}}=e^{i\frac{2\pi nq+2r\pi }{n}}=e^{i2\pi q}\cdot e^{i\frac{2r\pi }{n}}, q \in \mathbb Z
$$

Or $e^{i2q\pi}=e^{i0}=1$
Ainsi : $$z=e^{i\frac{2r\pi}{n}}$$or, $r\in [\![0;n-1]\!]$, ainsi, $k\in [\![0;n-1]\!]$ 
$k$ peut donc prendre $n$ valeurs.
L'équation $z^n=0$ admet donc au maximum $n$ solutions.
Prouvons maintenant que, pour chaque valeur possible de $k$, $z$ est différent.
Prenons $(k_1, k_2)\in\mathbb [\![0;n-1]\!]$ solutions de $e^{i\frac{2k\pi}{n}}=z$ 
$$
e^{i\frac{2k_1\pi}{n}}=e^{i\frac{2k_2\pi}{n}}\iff \frac{2k_1\pi}{n}=\frac{2k_2\pi}{n}+2k\pi\
$$$$
\frac{k_1}{n}=\frac{k_2}{n}+k\iff k_1 = k_2 + kn\iff k_1-k_2 = kn
$$or : 
$$
-n<-(n-1)\le k_1-k_2\le n-1<n 
$$
La seule possibilité est $k=0$ 
Ainsi, $k_1-k_2=0$ 
Donc, $k_1=k_2$ 
Finalement, si $k_1\ne k_2$ **alors** $e^{i\cdots}\ne e^{i\cdots}$ 
On a donc ***prouvé*** que l'équation $z^n=1$ admet **exactement** $n$ solutions. 