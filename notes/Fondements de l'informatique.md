### Plan 
 - Automates finis / Languages rationnels
 - Automates à piles - grammaires algébriques
 - Machines de Turing 
 - Problèmes de décidabilité
 - Lambda-calcul

# Automates finis

Les automates lisent des mots sur un **alphabet**.  Les entrées correspondent à des lectures. Ils sont composés de règles qui sont dépendantes de leur alphabet d'entrée. Ces règles agissent sur l'état de l'automate, et sur la position de sa *tête de lecture*.



>[!Définition]
> Un automate fini est un $5$-uplet $M = (Q,\Sigma, \delta, q_i, F)$
> - $Q$ est *l'ensemble fini des états*
> - $\Sigma$ est la *l'alphabet d'entrée*
> - $\delta: Q \times \Sigma \rightarrow Q$ est la *fonction de transition*
> - $q_i$ est *l'état initial*
> - $F \subset Q$ est l'ensemble des états finaux

On appelle **mot** une suite de caractères issus de l'*alphabet*. Le **language** de l'automate représente l'ensemble des mots acceptés par l'automate. 

Ces automates sont dits finis car ils présentent des *propriétés de cloture* assez sympathiques. Un language reconnaissable par un automate fini s'appelle un *language rationnel* on peut faire des opération sur les languages et rester dans la classe des languages rationnels. 

Par exemple, on peut prendre le **complémentaire** d'un language, c'est à dire $A' : \forall w, w \in A' \iff w \not\in a$ ou l'union $C: \forall w, w \in c \iff (w \in A \lor w \in B)$.

#### Théorème

**L'ensemble des languages rationnels est clos par complémentarité.**

Soit $L$ reconnu par $M = (Q,\Sigma, \delta, q_i, F)$, $\bar L$ est reconnu par $\bar M = (Q,\Sigma, \delta, q_i, Q \setminus F)$

**L'ensemble des languages rationnels est clos par union**

Soit $L_1$ un language reconnu par $M_1 = (Q_1,\Sigma, \delta_1, q_1, F_1)$ et $L_2$ un language reconnu par $M_2 = (Q_2,\Sigma, \delta_2, q_2, F_2)$. 

On peut construire l'automate 
$$
M = (Q_1 \times Q_2,\Sigma,\delta(\delta_1,\delta_2),(q_1,q_2),(F_1\times Q_2) \cup (Q_1 \times F_2))
$$
Ainsi, c'est équivalent a faire fonctionner les deux automates de manière couplée, avec des 2-uplets d'états qui représente l'état sur le language 1 et l'état sur le language 2.

**L'ensemble des languages rationnels est clos par concaténation**

>[!Définition]
> Un automate fini non déterministe est un $5$-uplet $M = (Q,\Sigma, \delta, q_i, F)$
> - $Q$ est *l'ensemble fini des états*
> - $\Sigma$ est la *l'alphabet d'entrée*
> - $\delta: Q \times ({\Sigma \cup \varepsilon}) \rightarrow \mathscr{P}(Q)$ est la *fonction de transition*
> - $q_i$ est *l'état initial*
> - $F \subset Q$ est l'ensemble des états finaux

Ainsi, l'*automate fini non-déterministe* propose plusieurs calculs possibles ($\mathscr{P}(Q)$) en fonction d'une entrée, qui elle même peut être vide. Ainsi, il peut executer plusieurs chemin simultanément. Une entrée est acceptée si *au moins un* chemin l'accepte.

Formellement, dire que le mot $w = y_1,y_2,...,y_n$ est accepté signifie qu'il existe une suite d'états $r_0, r_1, r_2,..., r_n \in Q$ avec 
 - $r_0 = Q_0$
 - $r_i \in \delta(r_i, y)$ pour $i\leq n$ 
 - $r_n \in F$ 

La présence d'une $\varepsilon$-transition est une source de non-déterminisme. En effet, il peut avoir une transition spontanée. 

Il existe une équivalence théorique entre les automates déterministe et les automates non-déterministes. En effet on peut décomposer les transitions simultanées en ensembles d'automates finis.

On peut donc résoudre la cloture par concaténation : À chaque lettre d'un mot, l'automate non-==déterministes== emprunte en même temps le chemin du language $1$ et du language $2$ finalement, si la coupure est dans un endroit correct, les chemin correct sera trouvé, si la coupure n'est pas la, le chemin correct sera trouvé plus tard.


### Expressions rationelles

Les expressions rationelles sont de la forme :
1. $a \in \Sigma$ 
2. $\varepsilon$
3. $\emptyset$
4. $R_1 \cup R_2$ avec $R_1$ et $R_2$ des expressions déjà définies 
5. $R_1 R_2$ 
6. $R^*$ 

**Si un language peut être décrit par une expression rationelle alors il est rationnel**

On peut dériver ça des propriétés de clôture des languages rationnels acceptés par les automates finis.

### Automate généralisé

Un automate non déterministe généralisé se caractérise par des transitions étiquetées par des expressions rationelles.

Il admet aussi un unique état final différent de l'état initial.

On le définit formellement comme une $5$-uplet :
$$
M = (Q,\Sigma,\delta, q_0,q_f)
$$
avec :
 - $Q$ l'ensemble des états
 - $\Sigma$ l'alphabet
 - $\delta: (Q - \{q_f\}) \times (Q - \{q_0\})$

$w \in \Sigma^*$ est accepté si il existe des mots tels que  $w_1w_2...w_n$ et si il existe des états $q_0,q_1,...,q_n$ avec $q_n = q_f$ 

Ainsi on peut peut se servier des propriétés de cloture pour réduire les états des automates généralisés en combinant les expressions rationelles.

### Languages non rationnels

$$
L = \{0^n1^n;n\geq 0\} \text{ n'est pas rationnel}
$$
Soit $A$ un language rationnel il existe $p \geq 1$ tel que pour tout $w \in A$ de longueur au moins $p$ on peut écrire $w = xyz$ avec $x,y,z$ des mots qui vérifient :
 - $\forall i \geq 0, xy^iz \in A$
 - $|y| \gt 0$
 - $|xz| \leq p$ 

# Minimisation

### Résiduels

Soit $L \subseteq \Sigma^*$, $x,y \in \Sigma^*$
On dit que $x$ et $y$ sont *indistinguables* si $\forall z \in \Sigma^*$, $xz \in L \iff yz \in L$.

#### Notation

On le note $x \equiv_L y$

**Def**: Les *résiduels* de $L$ sont les languages $x^{-1}  L = \{z \in \Sigma^* | xz \in L\}$ pour tout $x \in \Sigma^*$. 

Ainsi on vérifie facilement que $x \equiv_L y \iff x^{-1}L = y^{-1}L$

#### Théorème de Myhill-Nérode

$L$ est rationnel si et seulement si $\equiv_L$ a un nombre fini de classes d'équivalence. Dans ce cas le nombre de classes de $L$ est égal au nombre d'états du plus petit DFA reconnaissant $L$. 



### Automate quotient

**Def**: Soit $A = (Q,\Sigma,\delta,q_0,F)$ 

# Décidabilité des théories logiques

Formules logiques du premier ordre:
1. $\forall q, \exists p, \forall x, \forall y ~[~ p \gt q \land ( x \gt 1 \land y \gt 1) ~] \implies xy \neq p$

Au début du XXème siècle David Hilbert théorise l'existence d'un *algorithme* pour $\text{Th}(\mathbb{N},+,\times,=)$, c'est à dire pour résoudre n'importe quel théorème sur des entier qui utilise les opérateurs $+,\times,=$. Aujourd'hui, on sait qu'un tel algorithme d'existe pas. 

Une logique du *premier ordre* quantifie uniquement sur des variables. Une logique du *second ordre* peut quantifier sur des meta-variables de prédicats.

### Syntaxe

 - $R_i$ : symbole de relation 
 - $R_i (x_1, ... x_n)$ : formule atomique d'application de $R_i$ 

On peut ensuite construire des formules de plus en plus compliquées. 

On note l'ensemble des formules qui utilisent $+$ et $=$ sur les entiers naturels : $\text{Th}(\mathbb{N},+,=)$ 

Par exemple:
 - $\exists x, \forall y ~(y + x = y)$


Le language composé par l'ensemble de ces formules est un language rationnel et constructif. Ainsi on peut définir un algorithme qui nous permet de **décider** toutes ses expressions.

### Languages algébriques

À l'origine en linguistique, afin de décrire la structure des languages naturels, **Chomsky** invente un les *languages algébriques*.

Aujourd'hui, c'est principalement appliqué pour décrire la syntaxe des languages de programmation. 

Un language algébrique est un $4$-uplet $(V,\Sigma, R,S)$ avec
1. $V$ l'ensemble des variables (*Non-terminals**)
2. $\Sigma$ un alphabet fini des **terminals**
3. $R$ l'ensemble des règles de la force $A \rightarrow w$ avec $A$ une variable et $w$ un mot sur l'alphabet $\Sigma \cup V$ 
4. $F$ un élément **non-terminal** de $V$ qui représente la variable de départ

Les languages algébriques correspondent aux *context-free grammars*.

Il existe des languages intrinséquement ambigus, qui ne peuvent donc être générés que par des grammaires ambigues.


### Forme normale de Chomsky

Une grammaire est sous *forme normale de Chomsky* si toutes les règles sont de l'une de trois formes :
 - 