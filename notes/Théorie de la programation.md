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

```rocq
Inductive pair: (nat -> Prop) :=
| p0: pair 0
| p_a : forall n, pair n -> pair (S (S n)).
```

# Rocq

L'approche de preuve en Rocq se définit par la construction d'objects, l'énonciation de proposition et ensuite leur preuve par construction.

### Définitions inductives d'ensemble

Pour chaque ensemble définit de mainère inductive, on peut définir des propriétés de manière inductive sur l'ensemble.

Une **relation** c'est un *sous-ensemble* d'un produit cartésien. On la définit grâce a un tas de règles d'inférences. 

On appelle *dérivation* une preuve ou justification sur arbre construit à l'aide des règles d'inférence avec des axiomes aux feuilles.

On construit un arbre d'inférence pour obtenir nos propriétés. En haut on a des axiomes et en bas nos propriétés aux feuilles.

La **relation** que l'on définit inductivement peut être vue comme:
 - L'ensemble des dérivations *possibles*
 - L'ensemble des tuples qui *décorent* la racine

Ainsi, on peut voir la relation $*$ sur $A$ comment sous ensemble du produit cartésien, c'est à dire l'ensemble des tuples $(x,y) \in A$ qui **vérifie** (enfin qui sont constructibles) avec $*$.

# Théorie logique intuitioniste

Toute relation est définie de manière constructive. En gros, y'a pas de vrai ou de faux, juste du *valide*/*constructif*. On ne peut pas se servir de $\lnot A$. On ne peut pas faire d'*assertion*. 






