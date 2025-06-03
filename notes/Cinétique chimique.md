  La **cinétique chimique** étudie la **vitesse** des réactions chimiques. Ainsi, elle est complémentaire à la [[Thermodynamique chimique]] qui elle étudie le **sens** et l'**état** des réactions. 

>[!conditions] 
>Pour l'analyse cinétique, on considère que toutes les réactions sont **thermodynamiquement favorable**.

### Objectifs

La **cinétique** va permettre de mieux comprendre les réactions chimiques et de déterminer les **conditions** optimales pour leur réalisation.

>[!cadre] 
>On va étudier des *systèmes fermés*, de *volume constant* et à *température constante*.
>On va aussi supposer que les milieux réactionnels sont **homogènes** c'est à dire en pratique *parfaitement agités*.
>


### Définition des vitesses

On prends $\nu_i$ le [[coefficient stœchiométrique algébrique]]. 

#### Apparition

La vitesse d'apparition d'un produit correspond à la [dérivée](dérivation) de sa quantité de matière dans le système chimique en fonction du temps. 
$$
v_{\text{app},i} = \frac{dn_i}{dt} = \nu_i\frac{d\xi}{dt}
$$

#### Disparition

La vitesse de disparition correspond donc à la [dérivée](dérivation) de la quantité de matière d'un produit en fonction du temps.
$$
v_{\text{disp},i} = \frac{dn_i}{dt} = |\nu_i| \frac{d\xi}{dt}
$$

#### Vitesse d'une réaction

La **vitesse d'une réaction** permet d'étudier de manière unique une réaction sans considérer les coefficients relatifs à chaque espèce. Elle est définie par la la [dérivée](dérivation) de l'avancement molaire en fonction du temps.
$$
v = \frac{d\xi}{dt} = \frac{1}{\nu_i}\times \frac{dn_i}{dt}
$$
De plus, puisque les quantités de matière sont dépendantes du volume, on va étudier la variation de la concentration ($\frac{\text{mol}}{L\times s}$). Elle est **nécessairement positive**.
$$
v = \frac{1}{v_i} \times \frac{d[A_i]}{dt}
$$

### Facteurs cinétiques

Pour déterminer la **cinétique** d'une réaction, on va se baser sur plusieurs facteurs :
 - la **concentration** des réactifs
 - la **température** du milieu
 - la **pression** (*espèces gazeuses*)
 - les potentiels **catalyseurs**

#### Concentration

Une réaction admet un **ordre** si on peu écrire une *loi de vitesse* 

# Cinétique microscopique

On appelle **actes élémentaires** ou **réactions simples** les transformation qui se déroulent à l'échelle *moléculaire*. Dans ce cas, on passe directement de réactifs aux produits, sans *étapes intermédiaires*.

Les réactions simples les plus courantes se réalisent à travers une collision entre deux molécules.

On peut établir le **mécanisme réactionnel** d'une réaction chimique en isolant les différentes **réaction simples** ou **actes élémentaires** qui la composent.

### Propriétés des actes élémentaires

1. Une **réaction simple** ou **acte élémentaire** suit la *loi de Van't Hoff*, c'est à dire que l'ordre partiel par rapport à chaque réactif est égale à sont coefficient stœchiométrique.
2. La constante de vitesse $k$ d'une réaction simple suit la *loi Arrhenius* :
$$
k = A\times e^{-\frac{E_a}{RT}}
$$

### Étude énergétique 

On peut définir l'**énergie potentielle** d'un système chimique comme somme de l'*énergie d'interaction électrostatique* entre les différentes noyaux et l'*énergie électronique* (énergie des électrons dans chaque molécule).

L'énergie potentielle peut être étudiée de manière statistique. On peut par exemple définir une *surface d'énergie potentielle*, qui nous permet de représenter l'énergie potentielle d'une réaction en fonction des distances (en pratique statistiques) entre les espèces étudiées.

#### Profil réactionnel

Le profit réactionnel correspond à l'expression de l'énergie d'un système en fonction de l'avancement d'une réaction. Il représente notamment l'énergie d'activation.

On nomme **état de transition**, l'état de maximum énergie potentielle par lequel un système chimique doit passer afin de réaliser une réaction.

De fait, on peut mesurer l'énergie d'activation comme la différence entre l'énergie à l'*état de transition* et celle de l'*état initial*.

#### Réversibilité

On considère qu'au niveau microscopique, les réaction peuvent être exprimées de manière réversible.

### Postulat de Hammond

Dans un complexe de réaction, des états proches énergétiquement et temporellement sont aussi proches stucturelement. On peut ainsi analyser des états de transitions à partir de données sur d'autres instants réactionnels.

 - Dans une réaction **endothermique**, l'*état de transition* est proche de l'état final.
 - Dans une réaction **exothermique** l'*état de transition* est proche de l'état initial

### Réaction complexes

Une réaction **complexe** est caractérisée par une succession de **réactions simples**. Elle admet des espèces appelées *intermédiaires réactionnels* (IR) qui sont successivement produits, puis consommés par des **réactions simples**.
 
On distingue deux formes d'**IR**:
 - Les *IR ioniques*
 - Les *IR radicalaires*


### Études de mécanismes
### Approximations

#### Approximation de l'étape cinétiquement déterminante

L'approximation de l'**étape cinétiquement déterminante** nous permet de modéliser la réaction entière par une seule des **réactions simples** qui la composent. Ainsi, on obtient une loi de *Van't Hoff* simples.

#### Approximation des états quasi-stationnaires

L'*AEQS* nous permet de simplifer la modélisation d'une réaction en retirant une étape, considérée comme *quasi-stationnaire* et donc négligeable dans le calcul de sa loi. Ainsi, pour un *intermédiaire réaction* $[\text{IR}]$ on à:
$$
\frac{\mathrm{d}[\text{IR}]}{\mathrm{d}t} = 0
\implies v_\text{app} - v_\text{disp} = 0
$$

Ainsi, dans le cas d'un *IR* qui admet une unique étape de création $(1)$ et une unique étape de consommation $(2)$ on peut conclure que $v_1 \approx v_2$. 

#### Approximation de l'équilibre rapide

L'*AER* est utilisée dans le cas d'une réaction simple en état d'équilibre constant, qui nous permet donc d'établir la relation $v_1 = v_{-1}$. 