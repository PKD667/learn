### Probabilité et Information

L'information obtenue par la connaissance qu'un événement de probabilité $p$ s'est produit vaut $-\log p$ .

  - $n$ tirages d'un événement de probabilité $p$ est un événement de probabilité $\frac{1}{p^n}$, son résultat est donc d'information $-\log \left(\frac{1}{p^n}\right)$
 - Le lancer d'une pièce de monnaie a $p = 2$. L'information du résultat "pile,face,pile" de $3$ tirages est donc $- \log \left( \frac{1}{2^3} \right) = 3 \log 2 = 3\text{bits}$

*Voir [[Unités d'information]]*

##### Justification

Soit $I(p)$ une fonction qui définit l'information d'un événement de probabilité $p$. 

1. Cette fonction est **décroissante**: l'information est inversement proportionnelle à la probabilité *(Un événement moins probable contient plus d'information)*.
2. Cette fonction est **additive**: $I(pq) = I(p) + I(q)$. La combinaison de deux événements indépendants est la somme de leurs informations.

Ainsi, on obtient $-log(p)$ comme la seule fonction qui rempli ces critères.

##### Variation

L'information dépend de la quantité d'inconnu. En effet, beaucoup de *données* sur un événement sur lequel on à déjà beaucoup d'*information* représente moins d'*information* que sur un événement qui comporte beaucoup d'inconnues.  Autrement dit, limiter le nombre de choix possible lors d'un événement probabiliste réduit la quantité d'information obtenu par la connaissance d'un résultat.
