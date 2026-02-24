Le **second principe** introduit l'[[entropie]] et impose un sens d'évolution aux transformations. Le [[premier principe]] dit que l'énergie se conserve, mais il autorise des processus qui n'arrivent jamais (chaleur allant du froid vers le chaud). Le second principe les interdit.

## L'entropie

L'entropie $S$ est une fonction d'état qui mesure le "désordre" d'un système. Lors d'une transformation :
$$\Delta S = S_e + S_c$$

- $S_e = \int \frac{\delta Q}{T_\text{ext}}$ : entropie **échangée** avec l'extérieur
- $S_c \geq 0$ : entropie **créée** par les irréversibilités

Le point crucial : $S_c$ ne peut jamais être négative. L'entropie peut être échangée dans les deux sens, mais l'entropie créée est toujours positive ou nulle.

## Réversibilité

Une transformation est **réversible** si $S_c = 0$. C'est une idéalisation : le système reste à l'équilibre à chaque instant, on peut revenir en arrière par le même chemin.

En pratique, toute transformation réelle est **irréversible** ($S_c > 0$). Les sources d'irréversibilité : frottements, diffusion, échanges thermiques avec gradient de température, réactions chimiques...

## Conséquences

**Pour un système isolé** ($S_e = 0$) : $\Delta S = S_c \geq 0$. L'entropie ne peut qu'augmenter jusqu'à atteindre son maximum à l'équilibre. C'est la "flèche du temps" thermodynamique.

**Inégalité de Clausius** : $\Delta S \geq \frac{Q}{T_\text{ext}}$, l'égalité valant pour une transformation réversible.

**Machines thermiques** : le rendement est borné par celui de Carnot $\eta_\text{max} = 1 - \frac{T_f}{T_c}$. Impossible de convertir intégralement la chaleur en travail.

>[!example] Détente de Joule-Gay Lussac
> Un gaz se détend dans le vide. Système isolé donc $Q = 0$, $W = 0$, $\Delta U = 0$.
> Pourtant $\Delta S > 0$ : la transformation est irréversible, on ne peut pas la renverser spontanément.

>[!example] Équilibration thermique
> Deux corps à températures différentes mis en contact évoluent vers une température commune.
> L'entropie totale augmente. L'inverse (séparation spontanée des températures) violerait le second principe.
