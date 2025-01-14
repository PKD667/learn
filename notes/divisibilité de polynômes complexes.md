#### Définition :
Soit $P_1$ et $P_2$ deux fonctions polynômes.
on dit que $P_1$ **est divisible par** $P_2$ ou que $P_1(z)$ **est factorisable par** $P_2(z)$ s'il existe une fonction polynôme $P_3$ tel que, pour tout complexe $z$ : $P_1(z)=P_2(z)\cdot P_3(z)$. 

#### Théorème 1 :
Soient $z$ et $a$ deux nombres [[complexe]]s :$$\forall n\in\mathbb N: z^n-a^n=(z-a)(z^{n-1}+az^{n-2}+\cdots+a^{n-2}z+a^{n-1})$$$$=(z-a)\sum_{k=0}^{n-1}a^kz^{n-1-k}$$
##### Démonstration :
On pose :$(z-a)(z^{n-1}+az^{n-2}+\cdots+a^{n-2}z+a^{n-1})=P(z)$. $$\begin {array}
PP(z)=(z^{n}+\cancel{az^{n-1}}+\cancel{\cdots}+\cancel{a^{n-2}z^2}+\cancel{a^{n-1}z}-\cancel{az^{n-1}}-\cancel{a^2z^{n-2}}+\cancel{\cdots}+\cancel{a^{n-1}z}+a^{n})\\
P(z)=z^n-a^n
\end{array}
$$
#### Théorème 2 :
Soit $P$ une fonction polynôme.$$
\begin {array}
\left
P~\text{est divisible par}~z\rightarrow z-a\\
{\text{ou}}\\
P(z)~\text{est divisible par}~z-a
\end {array}
\iff
\begin {array}
\left
P(a)=0\\
\text{ou}\\
a~\text{est une racine de}~P(z)\\
\end {array}$$
##### Démonstration :
- Supposons que $P(z)$ soit factorisable par $z-a$, i.e. $Q(z)$, il existe une fonction polynôme tel que $$\forall z\in\mathbb C : P(z)=R(z)\cdot Q(z)$$**Ainsi $P(a)=R(a)\cdot Q(a)$, or $Q(a)=a-a =0$ ,finalement** $P(a)=R(a)\cdot 0$, $a$ est bien une racine de $0$. 
- Soit $P$ la fonction définie sur $\mathbb C$ par : $$P(z)=b_nz^n+b_{n-1}z^{n-1}+\cdots+b_1z+b_0$$où  $(b_0,b_1,b_2,\cdots,b_n)\in\mathbb C^{n+1}, b_n\ne 0$. On sait que : $$P(a)=0$$Donc :$$b_na^n+b_{n-1}a^{n-1}+\cdots+b_1a+b_0=0\iff P(z)-P(a)=P(z)$$$$P(z)=b_nz^n+b_{n-1}z^{n-1}+\cdots+b_1z+\cancel{b_0}-b_na^n-b_{n-1}a^{n-1}-\cdots-b_1a-\cancel{b_0}$$$$P(z)=P(z)=b_n(z^n-a^n)+b_{n-1}(z^{n-1}-a^{n-1})+\cdots+b_1(z-a)$$Chaque terme de cette somme est factorisable par $z-a$ ([[#Théorème 1]])
