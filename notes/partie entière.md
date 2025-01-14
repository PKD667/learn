#### Définition :
Soit $x\in\mathbb R$, il existe un unique [[entier relatif]] $n\in\mathbb Z$ tel que $n\le x<n+1$. Cette entier $n$ est appelé **partie entière** de $x$ noté $\lfloor x\rfloor$. $$n=\lfloor x\rfloor\iff\left\{\begin {array}
\left
n\in\mathbb Z\\
n\le x < n+1\\
\end {array}
\right.
$$
##### Démonstration : 
Montrons l'existence d'un tel entier :
- Si $x=0$, $n=0\in\mathbb Z$ vérifie bien $n\le x < n+1$.
- Si $x>0$, on pose $$n=\text{min}\{p\in\mathbb N|p>x\}-1$$ . D'après la l'[[Axiome d'Archimède]], cet ensemble est non vide donc admet bien un [[minimum]]. Par définition du minimum, $$n+1\in\{p\in\mathbb N|p>x\}$$donc $n+1>x$ et comme $n<n+1$, pour ne pas contredire la définition du minimum, on a forcément $$n\notin\{p\in\mathbb N|p>x\}$$ donc $n\le x$. D'où $n\le x<n+1$.   Finalement, $n$ convient bien.  
- Si $x<0$, on définit $n=-min\{p\in\mathbb N|p\ge -x\}$. Même démonstration qu'au dessus. 

Il reste à démontrer l'unicité de cet entier :
Supposons qu'il existe $(n,m)\in\mathbb Z²$ tel que $$n\le x<n+1\qquad\text{et}\qquad m\le x<m+1$$ Ainsi, $n\le x$ et $x<n+1\iff x-1<n$ 
On a donc :$$x-1<n\le x$$Egalement :  $$-x\le-m<-x+1$$ En additionnant les 2 inégalités, on obtient : $$x-1-x<n-m<x-x+1\iff -1<n-m<1$$ Comme $n-m\in\mathbb Z$, on a forcément $n-m=0$, d'où **l'unicité**. 
