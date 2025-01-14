
L'entropie est notée $S$
L'information est notée en $\text{bits}$ tels que $\log 2$ "information" correspond à $1 \text{bit}$
### Définitions
 - **Thermodynamique**: $\Delta S = \frac{\Delta E}{T}$,  avec $T$: *température*, $\Delta E$ changement d'*énergie*
 - **Statistique**: $S = k\int_X p(X)\ln(p(x))d\micro(x)$, avec $p$ probabilité dans l'espace $(X,\micro)$.
 - **Statistique quantique**: $S = -k\text{tr}(\rho \ln \rho)$, avec $\rho$ une matrice de densité.
 - **Théorie de l'information**: *Notée H*, $H = - \sum_{i\in X} p_i \log p_i$ 
 - **Algorithmique**: L'entropie d'une chaîne de caractère est la longueur du plus petit programme qui la `print`.


### Entropie et Information

L'entropie possède un rapport étroit à l'[[Information]]. En effet, elle correspond dans un certains sens à l'inverse de l'information, c'est à dire a l'inconnu.
### Entropie de Shannon

Avec $p$ une distribution de probabilité sur l'ensemble $X$, on à l'entropie de *Shannon* notée $H$ :

$$ H(p) = -\sum_{i \in X} p_i \log p_i$$

**Le principe d'entropie maximale**: Si il existe $n$ solution possible, il n'y a *a priori* aucun raison de penser qu'un est plus probable que l'autre. Le principe *d'entropie maximale* dit que la distribution de probabilité la meilleure correspond à celle qui à la plus grande *entropie de Shannon*.




### Entropie d'un gaz monoatomique

