
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
>  Si il existe $n$ solution possible, il n'y a *a priori* aucun raison de penser qu'un est plus probable que l'autre. Le principe *d'entropie maximale* dit que la distribution de probabilité la meilleure correspond à celle qui à la plus grande *entropie de Shannon*. En effet, choisir la distribution cohérente avec la plus grande entropie est une manière de minimiser les assomptions sur des faits en réalité inconnus.

#### Distribution de Boltzmann

Afin d'appliquer le principe d'entropie maximale, on peut construire une *distribution de probabilité* qui maximise l'entropie par rapport aux données connues. 

Ainsi, on utilise la distribution de Boltzmann :
$$
 p_i = \frac{\displaystyle e^{-\beta A_i}}{\displaystyle\sum^n_{i=1} e^{-\beta A_i}}
$$

Cette méthode déterminer le maximum de la fonction d'entropie par rapport à une valeur attendue fixée $A_i$. 

> [!boltzmann-physique] 
> La distribution de Boltzmann est utilisée en physique pour déterminer la probabilité $p_i$ qu'un système atteigne son *équilibre thermodynamique* dans l'état $i$ par rapport à un niveau d'énergie fixé $E$ tel que $\displaystyle\braket{E} = \sum^n_{i=1} p_i E_i$


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


#### Conséquences générales

Ces lois thermodynamiques nous permettent à travers des mesures précises d'isoler l'entropie propre aux différents éléments chimiques. 

On obtient donc par exemples :
- $5$ bits par atome de fer
- $12$ bits par molécule d'eau
- $23$ bits par molécule de dihydrogène



