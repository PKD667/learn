#### Définition :
La fonction valeur absolue est la fonction qui a $x\rightarrow |x|$ 
Elle est définie pour tout $x\in\mathbb R$ : 
- $|x|\rightarrow x$ si $x\ge 0$ 
- $|x|\rightarrow -x$ sinon 
$|x|$ est défini et continue sur $\mathbb R$ on a  $f(\mathbb R)\rightarrow\mathbb R+$ 
#### Apparence :

#### Propriétés :
  Soient $(x,y)\in\mathbb R$ 
  On dit que $|x-y|$ correspond à la **distance** entre les points $x$ et $y$, indépendamment de leur position respectives.

#### Technique 1
Pour montrer$$\lvert a\rvert<b$$ on montre $$a<b$$et $$-a<b$$
#### Technique 2
Pour montrer $$|a|=|b|$$on montre $$a²=b²$$ ou $$a=b~~\text{ou}~~a=-b$$
#### Inégalités triangulaires :
On remarque tout t'abord que, pour tout $a\in\mathbb R$, on a l'inégalité : $$a\le|a|$$ Elle est évidente si $a$ est positif (alors $|a|=a$) et évidente si $a$ est négatif ($-a\le a$) 
- $|x+y| \le |x| + |y|$ 
	Si $x+y$ est positif, d'après la remarque précédente, $$|x+y|=x+y\le |x| +|y|$$Si au contraire $x+y$ est négatif on a : $$x+y=-(x+y)=-x-y\le|-x|+|-y|=|x|+|y|.$$
- $|x-y|\le|x|+|y|$ 
	On applique la première inégalité à $x$ et à $-y$.
- $|x-y|\ge \lvert\lvert x\rvert-\lvert y\rvert\rvert$ 
	D'après la [[#Technique 1]], on commence par montrer l'inégalité$$|x|-|y|\le |x-y|$$On utilise pour cela l'[[#Inégalités triangulaires]] de manière astucieuse :$$|x|=|(x-y)+y|\le ||x-y|+|y|$$qui  nous donne bien $$|x|-|y|\le |x-y|$$En échangeant le rôle de $x$ et $y$, on trouve également $$|x|-|y|\le |x-y|=|y-x|$$Les 2 inégalités conjointes montrent l'inégalité triangulaire inverse voulue. 
 
 