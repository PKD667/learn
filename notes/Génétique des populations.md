> [!Population] 
> Une **population** est un ensemble d'individus dont les allèles des gènes sont susceptibles d'être associés au cours des générations issues de la reproduction

# Structure génétique d'une population

## Fréquence alléliques et fréquences génotypiques

Un **locus** représente l'emplacement d'un gène sur un chromosome. 

> [!Example]
> On peut par exemples étudier un locus une population diploïde avec :
> - 2 allèles ($A,a$)
> - 3 génotypes ($Aa,AA,aa$)

La fréquence d'un génotype c'est 
$$
\frac{\text{effectif du génotype}}{\text{effectif total}}
$$
On peut aussi considérer les *fréquences alléliques* 
$$
\frac{2\times\text{effectif homozygote } \\
+ \text{ effectif héterozygote }}{2\times\text{effectif total}}
$$

On peut aisément passer des fréquences alléliques aux fréquence génotypiques mais pas l'inverse. 

## Modèle de Hardy-Weinberg

Le modèle de Hardy-Weinberg est un ensemble d'hypothèse qui permet de passer des fréquences alléliques aux fréquences génotypiques pour $1$ locus donné. 

Il établit un relation **bijective**.

### Hypothèses
 - Organisme diploide
 - Générations non-chevauchantes
 - Reproduction séxuée
 - Union au hasard des individus (panmixie et pangamie)
 - Effectif grand
 - Pas de mutation
 - Population close
 - Pas de selection sur le locus 

### Relation

Avec $p$ et $q$ respectivement les fréquences des allèles $A$ et $a$ on à les fréquences génotypiques :
- $AA = p^2$
- $Aa = 2pq$
- $aa = q^2$

## Tester la conformité

### Test du $\chi^2$

Le test du $\chi^2$ permet de vérifier si la réalité est conforme au prédiction de notre modèle. 
$$
\chi^2 = \sum^\text{Nb. Génotypes}_{i=1} \frac{\Big(\text{Effectifs}_\text{théoriques} - \text{Effectifs}_\text{observés} \Big)^2}{\text{Effectifs}_\text{théoriques}}
$$

### $F-$statistiques

> [!F-stats ]
> Les $F-$statistiques sont une méthode mathématiques  d'interprétation des écarts à la panmixie dans une population. 

**Dans une population panmictique pour $1$ locus donné, l'hétérozygotie attendue st $2pq$**

 - Si elle est supérieure à $2pq$ cela ignifie qu'il y a plus d'hétérozygotes que prévu => hétérogamie
 - Si elle est inférieure à $2pq$ il y a deux possibilité :
    - La population est structurée en $2$ sous population dont les fréquences alléliques sont distinctes
    - endo/auto/homo-gamie dans la population

Quand il y à un déficit d'hétérozygotes dus a une division en *sous-populations* de la population observée, on parle d'**effet whalund**. 

Le test initial de conformité à la proportion $2pq$ est appelé test **FIT**.

$$
F_{IT} = \frac{ H_{Attendue} - H_{observée} }{H_{Attendue}} = 1- \frac{H_{observée}}{H_{Attendue}}
$$

##  Regimes non-panmictiques

L'**homogamie** c'est l'union entre des individus semblables pour un ou plusieurs caractères phénotypiques. Elle entraine une diminution de l'hétérozygotie. 

### Endogamie

L'**endogamie** c'est l'union entre des individus apparentés. 

Le **coefficient de consanguinité** correspond à la probabilité qu'un individu possède deux allèles identiques par descendance sur un locus donné. 

On peut aussi calculer le **coefficient de consanguinité moyen d'une population** qui correpsond à la moyenne des coefficients de consanguinité des individus.

L'endogamie entraine une perte d'hétérozygotie **sur tout le gènome** mais ne modifie pas les fréquences alléliques. 

### Hétérogamie

L'hétérogamie c'est l'union entre des individus phénotypiquement différents. Elle etraine un gain d'hétérozygotie au niveau des locus impliqués dans le phénotype. Elle entraine également une modification des fréquence allélique en avantageant les alléles rares. 

### déséquilibre gamétique

Cette différence entre la fréquence observée des gamètes (ou haplotypes) et la fréquence attendue est appelé déséquilibre gamétique. Il mesure une association privilégiée ou corrélation entre certains alléles de locus différent. 

$$
D_{AB} = p_{AB} - p_Ap_B
$$
*pareil pour tout x,y*

et ca forme un system de somme 1


## Evolution

### Mutation

La mutation est la seule source d'innovation génétique. Elle ne va nénamoins pas avoir un impact important sur les fréquences alléliques. 

### Sélections

La **valeur sélective absolue d'un génotype** correspond au nombre moyen de descendants laissés par des individus porteurs de ce génotype. 

$$
W_{AA} = \text{Éspérance de vie}_{AA} \times \frac{\text{Nb. descendants}_\text{AA}}{\text{Temps}}
$$












