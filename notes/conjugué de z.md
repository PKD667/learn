#### Définition : 
Soit $z\in\mathbb C$ tel que $z=x+yi$, où $(x,y)\in\mathbb R^2$.
On appel **complexe conjugué** de $z$ le complexe $\bar z$ défini par : $$\bar z=a-yi$$
#### Propriétés :
Soit $z\in\mathbb C$ tel que $z=x+yi$, où $(x,y)\in\mathbb R^2$.
- $\bar{\bar z}=z$ 
- $z+\bar z = 2Re(z) = 2x$
	- $x+yi+x-yi = 2x$ 
- $z-\bar z = 2Im(z) = 2y$
	-  $x+yi-(x-yi) = 2y$ 
- $\bar z = z \iff z$ est réel
-  $\bar z = -z \iff z$ est un imaginaire pur
- $z\bar z = x^2 +y^2$ 
	 $(x+yi)(x-yi)= x^2 \cancel{-xyi+xyi}-(yi)^2 = x^2 -i^2 y^2 = x^2 -(-1)y^2 = x^2 + y^2$ 

Soient $(z,z')\in\mathbb C^2$ et $n\in\mathbb N$  
On pose $z=a+bi$ et $\bar {z'}= a'+b'i$ où $(a,b,a',b')\in\mathbb R^4$ 

- $\overline{z+z'}= \bar z+\bar {z'}$ 
	- $\overline{z+z'}= \overline {a+bi+a'+b'i}=\overline{a+a'+(b+b')i}=a+a'-(b+b')i$ 
	- $\bar z +\bar z' = \overline {a+bi} +\overline{a'+b'i}= a-bi + a'-b'i=a+a'-(b+b')i$ 
- $\overline {zz'} = \bar z \cdot\bar{z'}$ 	 
	- $\overline{zz'}=\overline{(x+yi)(x'+y'i)}= \overline {xx'+xy'i+yix'+yiy'i}$
	 $=\overline{xx'-yy'+i(xy'+yx')} =xx'-yy'-i(xy'+yx'$
	- $\bar z\cdot\bar {z'}=\overline{(x+yi)}\cdot\overline{(x'+y'i)}=(x-yi)\cdot (x'-y'i)$   
- $\overline{z^n}=(\bar z)^n$ 
	Soit $P_n$ : $\forall n\in\mathbb N^*, \overline{z^n}=(\bar z)^n$ 
	**Initialisation :**
		On teste si la propriété est vraie pour la première valeur de $n$ soit $n=1$ $$\left.
		\begin{array}
		\overline{z^1}=\bar z\\
		\bar z^1 =\bar z\\
		\end{array}\
		\right\}\
		\text{la propriété est vraie pour $n=1$} 
		$$
	**Hérédité :** 
		Soit $p\in\mathbb N^*$ 
		Supposons que $\overline{z^p}=\bar z^p$ 
		Montrons que $\overline{z^{p+1}}=\bar z^{p+1}$ $$\overline{z^{p+1}}=\overline{z^p\cdot z^1}=\overline{z^p}\cdot\overline{z^1}=\bar z^p\cdot\bar z =\bar z^{p+1}$$
	**Conclusion :**
		Comme la propriété est vraie pour $n=1$ et héréditaire, d'après le principe de [[récurrence]], elle est vraie pour tout $n\in\mathbb N^*$. 
- $\overline{\left(\dfrac{1}{z}\right)}= \dfrac{1}{\bar z}$  avec $z\ne 0$ 
	$\overline{\left(\dfrac{1}{z}\right)}=\overline{\left(\dfrac{\bar z}{\bar zz}\right)}=\bar{\bar z}\cdot\overline{\left(\dfrac{1}{\bar zz}\right)}= z\cdot\dfrac{1}{\bar zz}=\dfrac{1}{\bar z}$ car $\dfrac{1}{\bar zz}$ est un [[réel]] donc $\overline{\left(\dfrac{1}{\bar zz}\right)}=\dfrac{1}{\bar zz}$ 
- $\overline{\left(\dfrac{z'}{z}\right)}= \dfrac{z'}{\bar z}$  avec $z\ne 0$ 
	$\overline{\dfrac{z'}{z}}=\overline{\left(z'\cdot\dfrac{1}{z}\right)}= \overline{z'}\cdot\overline{\dfrac{1}{z}} =\overline{z'}\cdot\dfrac{1}{\bar z}=\dfrac{\overline{z'}}{\bar z}$ 