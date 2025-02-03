
L'entropie est notée $S$
L'information est notée en $\text{bits}$ tels que $\log 2$ "information" correspond à $1 \text{bit}$
# Définitions
 - **Thermodynamique**: $\Delta S = \frac{\Delta E}{T}$,  avec $T$: *température*, $\Delta E$ changement d'*énergie*
 - **Statistique**: $S = k\int_X p(X)\ln(p(x))d\micro(x)$, avec $p$ probabilité dans l'espace $(X,\micro)$.
 - **Statistique quantique**: $S = -k\text{tr}(\rho \ln \rho)$, avec $\rho$ une matrice de densité.
 - **Théorie de l'information**: *Notée H*, $H = - \sum_{i\in X} p_i \log p_i$ 
 - **Algorithmique**: L'entropie d'une chaîne de caractère est la longueur du plus petit programme qui la `print`.


# Entropie et Information

L'entropie possède un rapport étroit à l'[[information]]. En effet, elle correspond dans un certains sens à l'inverse de l'information, c'est à dire a l'inconnu.
### Entropie de Shannon

Avec $p$ une distribution de [[probabilité]] sur l'ensemble $X$, on à l'entropie de *Shannon* notée $H$ :

$$ H(p) = -\sum_{i \in X} p_i \log p_i$$

> [!principe-d'entropie-maximale]
>  Si il existe $n$ solution possible, il n'y a *a priori* aucun raison de penser qu'un est plus probable que l'autre. Le principe *d'entropie maximale* dit que la distribution de probabilité la meilleure correspond à celle qui à la plus grande *entropie de Shannon*.


# Entropie physique

L'entropie est définie en **thermodynamique** comme une modification de l'énergie relative à la température. Elle est exprimée en $\frac{J}{K}$.

### Entropie et énergie

Dans l'étude des transformation d'un système thermodynamique on peut séparer l'**entropie** entre *entropie échangée* avec le milieu extérieur et *entropie créée* par la transformation :
$$
d S = \delta S_\text{échangée} + \delta S_\text{créée}
$$
 - $\delta S_\text{échnagée} = \frac{\delta Q}{T_\text{ext}}$

On peut définir l'entropie grâce à sa relation avec d'autres **variables d'état** d'un système thermodynamique comme l'[[enthalpie]] et l'[[énergie interne]] :
 - $dU = TdS - PdV$
 - $dH = TdS + VdP$


### Entropie d'un gaz monoatomique



