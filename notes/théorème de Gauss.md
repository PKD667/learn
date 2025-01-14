####  Définition : 
Soient $(a,b,c)\in\mathbb Z^{*3}$ **si** $a\mid bc$ **et** $PGCD(a ; b)=1$ **alors** $a\mid c$ 

#### Démonstration : 
- $PGCD(a;b)=1$ donc d'après le [[théorème de Bézout]], il existe $(u,v)\in\mathbb Z^2$ tel que $$au+bv=1\iff c\cdot au+ c\cdot bv =c$$
- $a\mid bc\Rightarrow ak=bc$, où $k\in\mathbb Z$ 
- $acu+akv=c\iff a(cu+kv)=c$, où $(cu+kv)\in\mathbb Z$ 
- donc :$$a\mid c$$ 

