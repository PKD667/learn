La chimie organique s'intéresse aux [[molécules organiques]]. 

# Nomenclature
### Chaînes carbonées

Les chaînes carbonées de type **alcanes** prennent la forme $C_nH_{2n+2}$ ou $R-H$ avec $R$ un radical **alkyle**.

Par exemple, on peut représenter l'*hexane* ($C_6H_{14}$) :
```smiles
CCCCCC
```
#### Chaines cycliques

Certaines chaînes carbonées se **cyclisent** comme :
 -  Le benzène :
```smiles
C1=CC=CC=C1
```
 - Le 3-méthyl-2-phénylbutane:
```smiles
CC(c1ccccc1)C(C)C
```
### Familles fonctionnelles


#### Carbonylés

La familles des **carbonylés** est composée de deux familles fonctionnelles caractérisées par la présence d'un atome d'oxygène doublement lié à un carbone 
```smiles
C=O
```
##### Aldéhydes



##### Cétones

#### Acétal

```smiles
CC(OC)(OC)C
```
#### Hémiacétal

L'**hémiacétal** représente la forme cyclique des sucres comme le *glucose*.


#### Carboxylés

Le groupe **carboxyle** caractérise la fonction acide. Ainsi, la famille des carboxylés contient tout les composées d'une fonction acide. 

##### Acides

```smiles
CC(=O)O

```
---

Il existe aussi de nombreux dérivés, contenant des fonction **carboxyle** et d'autre groupes comme :
 -  Chlorure d'acyle
```smiles
CC(=O)Cl
```
 -  Anhydride d'acide
```smiles
CC(=O)OC(=O)CC
```
 -  Ester (alcanoate d'alkyle) 
```smiles
CC(=O)OC
```
 - Amide
```smiles
CC(=O)N
```

#### Nitrile

```smiles
CC#N
```

### Nomenclature

1. Identifier la chaîne carbonées la plus longue
2. Numéroter pour que la fonction principale ait le numéro le plus faible possible
3. Si il y a plusieurs groupes fonctionnels, plus le carbone est oxydé, plus la fonction est prioritaire.

### Utilités dans le vivant

La chimie organique sert dans la [[biochimie]].

# Isomérie et stéréo-isomérie

Les **isomères** sont des molécules de même formule brute, mais qui se différencient par des caractéristiques spatiales ou de conformation.

## Isomères de constitution

Les **isomères de constitutions** sont des molécules de même composition chimique mais qui ont une formule semi-développée différente. Ainsi, elles ne présentes pas les même fonctions organiques et n'ont pas les même propriétés. 

## Représentation spatiale et stéréo-chimie

Il existe d'autres isomères, qui possèdent les même chaines, fonctions et positions qui différent uniquement par leur représentation spatiale. Ainsi, afin de les distinguer, une **représentation spatiale** (*tridimensionnelle*) est nécessaire.

### Perspective de Cram

La perspective de Cram se place dans le plan qui contient le plus d'atomes d'une molécule a représenter. Elle développer aussi des notations pour les placement spatiaux :
 - liaisons dans le plan -> *trait simple*
 - liaisons en avant -> *triangle plein*
 - liaisons en arrière -> *triangle en pointillés*
 - liaison inconnue -> *trait ondulé*

## Stéréo-isomérie de configuration et chiralité

### Configurations

On nomme **carbone asymétrique** ($C^\star$) le carbone $\ce{AX4}$ avec *quatre substituants différents*. Chaque $C^\star$ est lié à deux configuration nommées $Z$ et $S$.

La **double liaison dissymétrique** est une liaison $\ce{C=C}$ ou les substituants des deux carbones de la double liaison sont différents. Chaque double liaison admet deux configuration qu'on appelle $Z$ et $E$

On peut donc classer les différents groupements qui entourent un $C^\star$ par **priorité** en fonction d'un certain nombre de règles.

#### Règles C.I.P.

Les **règles CIP** permettent de classer par ordre de priorité décroissante les substituants liés à un groupe *central* :
1. Les priorité des atomes augmente avec leur numéro atomique $Z$
2. Si les atomes de rang $1$ sont identiques, comparer les atomes de rang $2$. Plus généralement, si l'indétermination n'est pas levée au rang $n$ comparer les atomes de rang $n+1$.
3. Une *liaison multiple* compte comme *autant de liaisons simples* entre ces atomes. 

# Méthodes spectroscopiques

On peut quantifier la variation d'énergie d'une molécule en fonction d'une absorption d'énergie :
$$
\Delta E = h\nu = \frac{hc}{\lambda} = hc \sigma
$$

Il existe différentes méthodes de **spectroscopie d'absorption** qui sont liées à différentes transition dans la molécules :
 - Une transition **électronique** (radiation *UV-visible*)
 - Une transition **vibrationnelle** (radiation *infrarouge)
 - Un changement d'état de **spin nucléaire**. (spectroscopie *RMN*)

### Spectroscopie UV-visible

Les molécules absorbent le rayonnement pour faire des **transitions électroniques**. le spectre qui en résulte ($A = f(\lambda)$) permet d'identifier les longueurs d'ondes associés à des transition d'états dans les **Orbitales Moléculaires** de la molécule.

Le processus de spectroscopie passe par une radiation d'un spectre défini d'ondes électromagnétiques sur une *solution* qui contient la molécule qui nous intéresse. Ainsi, on compare le spectre *après passage dans la cuve* au *spectre émis*. 

Soit $I_0$ le rayonnement **incident** et $I_t$ le rayonnement **transmis**. On définit la transmittance $T = \frac{I_t}{I_0}$ (*adimensionnée*) et l'absorbance  $A = -\log_{10}(T) = \log_{10}(\frac{I_0}{I_t})$ (*adimensionnée* aussi).

La loi de Beer-Lambert nous permet d'étudier les concentration en fonction de l'absorbance dans un contexte expérimental :
$$
A = \varepsilon~  l ~c
$$
 - $A$ représente l'*absorbance*
 - $l$ représente la largeur de la cuve
 - $c$ représente la concentration su soluté
 - $\varepsilon$ est le coefficient d'extinction molaire (lié aux propriétés de la molécule et du solvant)

### Spectroscopie infrarouge

Les molécules absorbent les radiations *infrarouges* pour faire des transitions *vibrationnelles*/ ...

#### Principes pour une liaison

On peut assimiler la liaison entre deux atomes à un ressort de constante de *raideur* $k$. On peut donc exprimer le nombre d'onde $\sigma$ avec la loi de *Hooke* :
$$
\sigma = \frac{1}{2\pi c} \sqrt{\frac{k}{\mu}}
$$

Ainsi, plus la liaison est **forte** plus le *nombre d'onde $\sigma$* est **grand**. La force de la liaison est affectée par deux facteurs :
1. La **multiplicité** de la liaison ($\ce{C#C > C=C > C-C}$)
2. La **conjugaison**, une liaison conjuguée est moins forte.
3. L'influence des liaisons $\ce{H}$, les liaisons $H$ inter-moléculaires vont *élargir* les liaisons covalente de chaque molécule et donc **diminuer** le nombre d'onde.

#### Principes pour des formes complexes

Les vibrations dans les *molécules complexes* peuvent prendre plusieurs formes :
1. Des **élongations** (variation de longueur de liaison: $\sigma$ **élevé**)
2. Des **déformations angulaires** (variation des angles: $\sigma$ **faible**)

Cela à pour conséquence de scinder le spectre infrarouge de la molécule en deux domaines :
1. Un domaine dit **attribuable**, avec des $\sigma$ élevés qui correspondent au élongations de liaisons et qui peuvent être identifiés
2. Un domain d'**empreinte digitale** qui contient les traces des élongations et de toutes formes de déformations qui sont uniques mais difficile à déchiffrer.

### Résonance magnétique nucléaire

