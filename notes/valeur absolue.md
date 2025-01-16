#### Définition
La fonction valeur absolue est la fonction qui a $x\rightarrow |x|$ 
Elle est définie pour tout $x\in\mathbb R$ : 
- $|x|\rightarrow x$ si $x\ge 0$ 
- $|x|\rightarrow -x$ sinon 
$|x|$ est défini et continue sur $\mathbb R$ on a  $f(\mathbb R)\rightarrow\mathbb R+$ 
#### Apparence

![[abs-val-graph.svg]]

#### Propriétés
  Soient $(x,y)\in\mathbb R$ 
  On dit que $|x-y|$ correspond à la **distance** entre les points $x$ et $y$, indépendamment de leur position respectives.

### Inégalités triangulaires

#### Remarque préliminaire
Pour tout $a\in\mathbb{R}$, on a l'inégalité :

$$
a\leq|a|
$$

Cette inégalité est évidente car :
- Si $a\geq 0$ : alors $|a|=a$
- Si $a<0$ : alors $|a|=-a>a$

#### Première inégalité triangulaire
**Proposition :** $|x+y| \leq |x| + |y|$

**Démonstration :**
- Si $x+y\geq 0$ : alors $|x+y|=x+y\leq |x|+|y|$
- Si $x+y<0$ : alors $|x+y|=-(x+y)=-x-y\leq |x|+|y|$

#### Deuxième inégalité triangulaire
**Proposition :** $|x-y|\leq|x|+|y|$

**Démonstration :** On applique la première inégalité à $x$ et $-y$.

#### Inégalité triangulaire inverse
**Proposition :** $|x-y|\geq \big||x|-|y|\big|$

**Démonstration :**
1. Montrons d'abord que $|x|-|y|\leq |x-y|$ :

$$
|x|=|(x-y)+y|\leq |x-y|+|y|
$$

Donc :

$$
|x|-|y|\leq |x-y|
$$

2. En échangeant $x$ et $y$ :

$$
|y|-|x|\leq |y-x|=|x-y|
$$

3. Ces deux inégalités impliquent :

$$
|x-y|\geq \big||x|-|y|\big|
$$


