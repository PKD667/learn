#### Définition :
Soient $(a,b)\in\mathbb Z^{*2}$ 
$PGCD(a;b)=1 \iff$ il existe $(u,v)\in\mathbb Z^2$ tel que : $au+bv=1$ 

#### Démonstration : 
- Soient $(a,b)\in\mathbb Z^{*2}$ tel que $PGCD(a;b)=1$ 
	D'après l'[[identité de Bézout]], il existe $(u,v)\in\mathbb Z^2$ tel que : $au+bv=PGCD(a;b)$ 
	Donc : $au +bv=1$ 
- Soient  $(u,v)\in\mathbb Z^2$ tel que : $au+bv=1$
	Soit $d=PGCD(a;b)$ 
	$d\mid a$ et $d\mid b\Rightarrow d\mid au+bv$ donc $d\mid 1$
	Comme d est positif, $d=1$ donc $PGCD(a;b) = 1$ 

