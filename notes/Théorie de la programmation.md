
---
### Meta
  - DM Rocq: jeudi avant les vacances. Demander de l'aide. S'y prendre à l'avance.
---

On peut crée inductivement des ensembles, qui nous donne des éléments avec des propriétés formalisables. 

Ainsi, sur l'ensemble inductivement construit par succesion des entiers naturels, on peut définir une relation d'égalité, d'ordre partiel et total.

Les règles d'inférence se traduisent dans des languages par des **constructeurs**. Elles permettent de définir des ensembles inductivement. 

### Exemple

On peut définir la fonction **pair**, qui lie un entier naturel a une **proposition** (truth value): `nat -> Prop`. 

Cette définition passe par deux règles d'inférence:

$$
$$

```
---
p0 0
```
*0 est pair*

```
pair
---
pair S (S n)
```
*si n est pair, alors n+2 est pair*

#### Traduction rocq

```rocq
Inductive pair: (nat -> Prop) :=
| p0: pair 0
| p_a : forall n, pair n -> pair (S (S n)).
```

# Rocq

L'approche de preuve en Rocq se définit par la construction d'objects, l'énonciation de proposition et ensuite leur preuve par construction.

### Définitions inductives d'ensemble

Pour chaque ensemble définit de manière inductive, on peut définir des propriétés de manière inductive sur l'ensemble.

Une **relation** c'est un *sous-ensemble* d'un produit cartésien. On la définit grâce a un tas de règles d'inférences. 

On appelle *dérivation* une preuve ou justification sur arbre construit à l'aide des règles d'inférence avec des axiomes aux feuilles.

On construit un arbre d'inférence pour obtenir nos propriétés. En haut on a des axiomes et en bas nos propriétés aux feuilles.

La **relation** que l'on définit inductivement peut être vue comme:
 - L'ensemble des dérivations *possibles*
 - L'ensemble des tuples qui *décorent* la racine

Ainsi, on peut voir la relation $*$ sur $A$ comment sous ensemble du produit cartésien, c'est à dire l'ensemble des tuples $(x,y) \in A$ qui **vérifie** (enfin qui sont constructibles) avec $*$.

# Théorie logique intuitionniste

Toute relation est définie de manière constructive. En gros, y'a pas de vrai ou de faux, juste du *valide*/*constructif*. On ne peut pas se servir de $\lnot A$. On ne peut pas faire d'*assertion*. 

Le principe du *tiers exclu* n'est pas appliqué en Rocq. Ainsi, on ne peut pas dériver la proposition $\lnot A$ a partir la définition de $A$. 


# Languages fonctionnels

### FUN

$$
k \in \mathbb{Z}, x,y,z \in \text{Vars} \\
$$$$
e ::= k|e_1 + e_2| x | \text{let } x = e_1 \text{ in } e_2| \text{ fun } x \rightarrow e | e_1 e_2
$$

#### Sémantique opérationnelle à grands pas

`
`(fun x -> x + x)(6 + 4)`
1. `(6 + 4)` -> $10$
2. `(fun x -> x + x)10` -> `10+10`
3. `10 + 10` -> `20`

Functions are first-class citizens

On définit une relation d'évaluation $\Downarrow$ qui s'écrit *$e$ s'évalue en $b$*: $e \Downarrow b$.

`