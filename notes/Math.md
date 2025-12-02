
### Calculs de sommes et de produits

1. [[Calculs de sommes]]
2. [[Calculs de produits]]
3. [[Sommes et produits classiques]]

### Nombres Réels

1. [[Manipulation de réels]]

### Bijections et infinis

#### Égalités d'ensembles

Deux ensembles sont égaux si on peut établir une [[bijection]] entre leur composants. 
#### Infinis

Cantor démontre des égalités entre des infinis. Ainsi il prouve  par exemple que l'ensemble des entier pairs est aussi grand que l'ensemble des entiers naturels. Il va aussi prouver que l'ensemble des réels dépasse l'ensemble des entiers.

Il existe une infinité d'infinis et certains sont plus grand que d'autres.

#### Systèmes mathématiques

Kurt Gödel démontre qu'un système axiomatique qui contient au moins l’arithmétique, il existe des proposition qui sont vraies mais indémontrables. [Démonstration incompréhensible](https://fr.wikipedia.org/wiki/Th%C3%A9or%C3%A8mes_d%27incompl%C3%A9tude_de_G%C3%B6del)


Ainsi, il distingue le **vrai** du **démontrable**.

Dans tout système axiomatique il existe des proposition invérifiables, que l'ont peut ajouter ou pas au système axiomatique. 

### Suites

#### Analyse asymptotique

| nom                                    | symbole          | signification                                          | interprétation                                       |
| -------------------------------------- | ---------------- | ------------------------------------------------------ | ---------------------------------------------------- |
| $(U_n)$ **négligeable** devant $(V_n)$ | $U_n = o(V_n)$   | $\frac{U_n}{V_n} \xrightarrow{n  \rightarrow\infty} 0$ | $U_n \ll V_n$                                        |
| $(U_n)$ est **équivalente** à $V_n$    | $U_n \sim V_{n}$ | $\frac{U_n}{V_n} \xrightarrow{n  \rightarrow\infty} 1$ | $U_n -V_{n} = o(V_n) \text{ et }V_n -U_{n} = o(U_n)$ |
| $(U_n)$ est **dominée** par $(V_n)$    | $U_n = O(V_n)$   | $\frac{U_n}{V_n}$ *bornée*                             | $\|\frac{U_n}{V_n}\| \leq A$                         |

### Systèmes linéaires

$$
\begin{cases}
a_{1,j_1}  + \cdots + \cdots + \cdots a_{1,p}x_p = b_1 \\
x-3y &=4
\end{cases}
$$

#### Solutions d'un système

#### Pivot de Gauss

### Polynômes

1. [[factorisation de polynômes]]


# Analysis Essentials

## Intégrales de Riemann (CRITICAL)

$$\int_1^{+\infty} \frac{dt}{t^\alpha} \begin{cases} \text{converge} \iff \alpha > 1 & \text{valeur: } \frac{1}{\alpha-1} \ \text{diverge} \iff \alpha \leq 1 \end{cases}$$

$$\int_0^1 \frac{dt}{t^\alpha} \begin{cases} \text{converge} \iff \alpha < 1 & \text{valeur: } \frac{1}{1-\alpha} \ \text{diverge} \iff \alpha \geq 1 \end{cases}$$

## Équivalents usuels (quand $x \to 0$)

$$e^x - 1 \sim x \qquad \ln(1+x) \sim x \qquad (1+x)^\alpha - 1 \sim \alpha x$$

$$\sin x \sim x \qquad \tan x \sim x \qquad 1 - \cos x \sim \frac{x^2}{2} \qquad \arctan x \sim x$$

## Développements limités en 0

$$e^x = \sum_{k=0}^n \frac{x^k}{k!} + o(x^n) \qquad \ln(1+x) = \sum_{k=1}^n \frac{(-1)^{k+1}}{k} x^k + o(x^n)$$

$$\sin x = \sum_{k=0}^n \frac{(-1)^k}{(2k+1)!} x^{2k+1} + o(x^{2n+2}) \qquad \cos x = \sum_{k=0}^n \frac{(-1)^k}{(2k)!} x^{2k} + o(x^{2n+1})$$

$$\frac{1}{1+x} = \sum_{k=0}^n (-1)^k x^k + o(x^n) \qquad (1+x)^\alpha = 1 + \sum_{k=1}^n \frac{\alpha(\alpha-1)\cdots(\alpha-k+1)}{k!} x^k + o(x^n)$$

## Équations différentielles

**Ordre 1:** $y' + b(x)y = f(x)$

- Solution homogène: $y_h = \lambda e^{-B(x)}$ où $B' = b$
- Solution générale: $y = y_h + y_p$

**Ordre 2 à coefficients constants:** $ay'' + by' + cy = 0$

- Équation caractéristique: $ar^2 + br + c = 0$
- Si $\Delta > 0$, racines $r_1, r_2$ réelles: $y = \alpha e^{r_1 x} + \beta e^{r_2 x}$
- Si $\Delta = 0$, racine double $r_0$: $y = (\alpha x + \beta)e^{r_0 x}$
- Si $\Delta < 0$, racines $r \pm i\omega$: $y = e^{rx}(A\cos(\omega x) + B\sin(\omega x))$

## Intégrales généralisées (fonctions positives)

**Comparaison:** Si $0 \leq f \leq g$ sur $[a,b[$: $$\int_a^b g \text{ converge} \implies \int_a^b f \text{ converge}$$

**Équivalents:** Si $f(x) \sim_{x \to b} g(x)$ (avec $f,g > 0$): $$\int_a^b f \text{ et } \int_a^b g \text{ même nature}$$

**Absolue convergence:** $\int_a^b |f|$ converge $\implies$ $\int_a^b f$ converge

## Calcul différentiel (2 variables)

**Gradient:** $\nabla f(a) = \left(\frac{\partial f}{\partial x}(a), \frac{\partial f}{\partial y}(a)\right)$

**DL ordre 1:** $f(a+h) = f(a) + \langle h | \nabla f(a) \rangle + o(|h|)$

**Règle de la chaîne:** Si $\Psi(t) = f(x(t), y(t))$: $$\Psi'(t) = \frac{\partial f}{\partial x} \cdot x'(t) + \frac{\partial f}{\partial y} \cdot y'(t)$$

**Extrema:** Point critique: $\nabla f(a) = 0$. Poser: $$r = \frac{\partial^2 f}{\partial x^2}(a), \quad s = \frac{\partial^2 f}{\partial x \partial y}(a), \quad t = \frac{\partial^2 f}{\partial y^2}(a)$$

- $s^2 - rt < 0$ et $r > 0$: minimum local
- $s^2 - rt < 0$ et $r < 0$: maximum local
- $s^2 - rt > 0$: point col

## Intégrales doubles

**Fubini (rectangle):** $\iint_{[a,b]\times[c,d]} f(x,y),dx,dy = \int_a^b \left(\int_c^d f(x,y),dy\right)dx$

**Domaine général:** Si $D = {(x,y) : a \leq x \leq b, \varphi_1(x) \leq y \leq \varphi_2(x)}$: $$\iint_D f(x,y),dx,dy = \int_a^b \left(\int_{\varphi_1(x)}^{\varphi_2(x)} f(x,y),dy\right)dx$$

**Polaires:** $x = \rho\cos\theta$, $y = \rho\sin\theta$, avec $dx,dy = \rho,d\rho,d\theta$

**Jacobien:** Pour $\Phi(u,v) = (x(u,v), y(u,v))$: $$J_\Phi = \begin{vmatrix} \frac{\partial x}{\partial u} & \frac{\partial x}{\partial v} \\ \frac{\partial y}{\partial u} & \frac{\partial y}{\partial v} \end{vmatrix}$$ $$\iint_\Delta f(x,y),dx,dy = \iint_D f(\Phi(u,v)) |\det J_\Phi|,du,dv$$

## Séries (si jamais)

$$\sum_{n=0}^{+\infty} q^n = \frac{1}{1-q} \quad (|q| < 1) \qquad \sum \frac{1}{n^\alpha} \text{ converge} \iff \alpha > 1$$

---

# Problems (exam-style)



## Problème 1: Intégrales généralisées mixées

Soit $\alpha \in \mathbb{R}$.

1. Étudier la convergence de $I_\alpha = \int_0^{+\infty} \frac{x^\alpha}{(1+x)^3},dx$
    
2. Calculer $I_0$ et $I_1$.
    
3. Soit $D = {(x,y) \in \mathbb{R}^2 : x \geq 0, 0 \leq y \leq e^{-x}}$. Calculer: $$J = \iint_D \frac{1}{(1+x+y)^2},dx,dy$$
    

## Problème 2: Équation différentielle contextuelle

On modélise la vitesse $v(t)$ d'un objet en chute avec résistance de l'air par: $$(1 + e^{-kt})v'(t) + kv(t) = g(1 + e^{-kt})$$ où $g > 0$ et $k > 0$ sont des constantes.

1. Résoudre l'équation homogène associée.
    
2. Trouver une solution particulière (essayer une constante).
    
3. Résoudre l'équation avec $v(0) = 0$.
    
4. Calculer $\lim_{t \to +\infty} v(t)$. Interpréter physiquement.
    
5. Montrer que $\int_0^{+\infty} (g - v(t)),dt$ est convergente et la calculer.
    

## Problème 3: Système dynamique

Deux espèces interagissent selon: $$\begin{cases} x'(t) = x(t)(2 - y(t)) \ y'(t) = y(t)(x(t) - 3) \end{cases}$$

On définit $\Phi(x,y) = x - 2\ln x + y - 3\ln y$ pour $x,y > 0$.

1. Calculer $\nabla \Phi(x,y)$ et trouver le point critique.
    
2. Déterminer la nature de ce point critique.
    
3. Si $(x(t), y(t))$ est solution du système, montrer que $\frac{d}{dt}\Phi(x(t), y(t)) = 0$.
    
4. Que peut-on en déduire sur les trajectoires du système?
    

## Problème 4: Intégrale double technique

Soit $D = {(x,y) : 1 \leq x \leq e, 1 \leq y \leq x^2}$.

1. Représenter $D$.
    
2. Calculer $\iint_D \frac{\ln x}{xy},dx,dy$ (deux méthodes possibles).
    
3. Soit $D_\infty = {(x,y) : x \geq 1, \frac{1}{x^2} \leq y \leq \frac{1}{x}}$. Pour quels $\alpha > 0$ l'intégrale $$\iint_{D_\infty} \frac{1}{x^\alpha y^2},dx,dy$$ est-elle convergente? Calculer sa valeur dans ce cas.
    

---

want me to provide solutions/hints for any of these? or you want more problems first?