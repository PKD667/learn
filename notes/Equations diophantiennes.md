#### Définition : 
 Équation polynomiale d'entiers naturels à plusieurs variables dont il faut trouver l'ensemble des solutions. 

 Une équation diophantiennes s'écrit sous la forme : $$\displaystyle ax + by=c$$où, $\displaystyle(a,b,c)\in\mathbb Z^3$

#### résolution d'un équation diophantienne
1. recherche d'une solution particulière :
	1. méthode calculatrice :
		a.  Exprimer $y$ en fonction de $x$ 
		b. Poser $y=f(x)$ dans la calculatrice avec un pas de 1 et trouver une solution entière. 
	2. méthode congruence :
		a. 
1. recherche d'une solution générale 
		a. On note $(x_1,y_1)$ le couple de solution trouvé. On a donc $c=ax_1+by_1$ 
		b. On pose l'équation : $ax+by=ax_1+by_1$ 
	or : $$ ax+by=ax_1+by_1\iff ax-ax_1=by_1-by\iff a(x-x_1)=b(y_1-y)$$on pose : $$x-x_1 = k$$ 
	ainsi on a : $$ak=b(y_1-y)\iff a\mid b(y_1-y)$$ or si $a$ et $b$ sont premiers entre eux, alors, d'après le [[théorème de Gauss]], si $a$ et $b$ sont premiers entre aux alors : $$a\mid y_1-y$$ donc : $$aq= y_1-y\iff y=y_1-aq$$où $q\in\mathbb Z$ 
	Ainsi : $$a(x-x_1)=b(y_1-(y_1-aq))\iff ax-ax_1=b\cdot aq$$$$ax=b\cdot aq+ax_1\iff x=bq+x_1$$où $q\in\mathbb Z$ 

	**Finalement**, l'ensemble des couples $(x,y)$ solution de l'équation $ax+by=c$ correspond à $$(bq+x_1,y_1-aq)$$Où $q\in\mathbb Z$ 




 