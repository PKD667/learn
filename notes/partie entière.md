#### Définition :
Soit $x \in \mathbb{R}$, il existe un unique [[entier relatif]] $n \in \mathbb{Z}$ tel que $n \leq x < n+1$. Cet entier $n$ est appelé **partie entière** de $x$ notée $\lfloor x \rfloor$. 
$$
n = \lfloor x \rfloor \iff
\begin{cases}
n \in \mathbb{Z} \\
n \leq x < n+1
\end{cases}
$$
##### Démonstration : 
Montrons l'existence d'un tel entier :
- Si $x = 0$, $n = 0 \in \mathbb{Z}$ vérifie bien $n \leq x < n+1$.
- Si $x > 0$, on pose $n = \min\{p \in \mathbb{N} \mid p > x\} - 1$.
- D'après l'[[Axiome d'Archimède]], cet ensemble est non vide et admet un [[minimum]]. Par définition du minimum, $n+1 \in \{ p \in \mathbb{N} \mid p > x \}$.
- Donc $n+1 > x$ et comme $n < n+1$, pour ne pas contredire la définition du minimum, on a forcément $n \notin \{ p \in \mathbb{N} \mid p > x \}$.
- Donc $n \leq x$. D'où $n \leq x < n+1$. Finalement, $n$ convient bien.
- Si $x < 0$, on définit $n = -\min\{p \in \mathbb{N} \mid p \geq -x\}$. Même démonstration qu'au-dessus.

Il reste à démontrer l'unicité de cet entier :
Supposons qu'il existe $(n, m) \in \mathbb{Z}^2$ tel que 
$$
n \leq x < n+1 \qquad \text{et} \qquad m \leq x < m+1
$$ 
Ainsi, $n \leq x$ et $x < n+1 \iff x-1 < n$.
On a donc :
$$
x-1 < n \leq x
$$
Également :
$$
-x \leq -m < -x + 1
$$
En additionnant les deux inégalités, on obtient :
$$
x-1 - x < n - m < x - x + 1 \iff -1 < n - m < 1
$$
Comme $n - m \in \mathbb{Z}$, on a forcément $n - m = 0$, d'où **l'unicité**.