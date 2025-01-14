#### ==Définition :== 
Soient $(a,b)\in\mathbb Z^*$
On dit que "$a$ divise $b$" **si et seulement si** il existe $k\in\mathbb Z^*$ tel que $ak=b$ 
On note "$a$ divise $b$" : $$a\mid b$$
#### ==Propriétés :==
1. Si $a$ divise $b$ **alors** $-a$ divise $b$ 
	Si $a$ divise $b$, il existe $k\in\mathbb Z$ tel que $b=ka$ 
	Donc $b=(-a)\cdot (-k)$, où $(-k)\in\mathbb Z$ 
	Ainsi $-a\mid b$ 
2. Si $a$ divise $b$, **alors** $|a| \le |b|$ 
	Si $a\mid b$ alors il existe $k\in\mathbb Z^*$ tel que $b=ka$ 
	Ainsi $|b| = |ka|\iff |b|=|k|\cdot |a|$ 
	Or $b\ne 0$ et $|k|\ge 1$
	Ainsi $|a|\cdot |k|\ge 1\cdot |a|\iff |b|\ge |a|$ 
3. Si $a$ divise $b$ et $b$ divise $a$, **alors** $a=b$ ou $a=-b$ 
	$a\mid b$ donc $|a|\le |b|$ **et** $b\mid a$ donc $|b|\le |a|$ 
	ainsi $|a|=|b|$, d'où  $a=b$ ou $a=-b$ 
4. Si $a$ divise $b$ et si $b$ divise $c$, **alors** $a$ divise $c$
	$a\mid b$ donc il existe $k_1$ tel que $b=a\cdot k_1$
	$b\mid c$ donc il existe $k_2$  tel que $c=b\cdot k_2$ 
	donc $c=a\cdot k_1\cdot k_2$, où $k_1\cdot k_2\in\mathbb Z$ 
	ainsi $a\mid c$ 
5. Si $a$ divise $b$ **alors** $ac$ divise $bc$ 
	$a\mid b$ donc il existe $k\in\mathbb Z$ tel que $b=ak$ 
	donc $b\cdot c=a\cdot c\cdot k$ 
	ainsi $ac\mid bc$ 
6. Si $a$ divise $b$ et si $a$ divise $c$ **alors**, pour tout $(u,v)\in\mathbb Z$, $a$ divise $bu+cv$ 
	$a\mid b$ donc il existe $k_1$ tel que $b=a\cdot k_1$
	$a\mid c$ donc il existe $k_2$  tel que $c=a\cdot k_2$ 
	$bu+cv=k_1a\cdot u + k_2a\cdot v=a(k_1\cdot u+k_2\cdot v)$ 
	où $(k_1\cdot u+k_2\cdot v)\in\mathbb Z$
	ainsi $a\mid bu +cv$ 
