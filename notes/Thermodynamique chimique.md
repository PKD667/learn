# Évolution et équilibre d'un système chimique

Rappels [[Moles et concentrations]]

##### Bilan de matière dans un systèmes siège d'une réaction chimiques

La [[réaction chimique]].

Une réaction est dite **thermodynamiquement favorable** si sa constante d'équilibre est supérieure à $1$ ($K^0 > 1$). 
Une réaction est **thermodynamiquement défavorable** si sa constante d'équilibre est inférieure à $1$ ($K^0 < 1$).

### Sens d'évolution d'un système

Si le **coefficient de réaction** est *inférieur* à la constante d'équilibre ($Q_r < K^0$, la réaction va évoluer dans le **sens direct**.
Si le **coefficient de réaction** est *supérieur* ($Q_r > K^0$, la réaction va évoluer dans le **sens indirect**.

#### Réaction *très défavorable*

Si la constante d'équilibre est *très petite* ($K^0 < 10^{-3}$), il s'agit d'une réaction limitée, et on pourra alors utiliser l'**approximation de faible avancement à l'équilibre ($\xi_{éq} \ll n_0$)**. 

#### Réaction *très favorable*

Si la constante d'équilibre est *très grande* ($K^0 > 10^{-3}$), il s'agit d'une réaction quantitative, et on pourra alors utiliser l'**approximation de fort avancement à l'équilibre ($\xi_{éq} \gg n_0$)**. 


# Réactions acido-basiques

Ces réactions mettent en jeu des couples [[acido-basique]].
#### Couples de l'eau

La molécule d'eau peut jouer à la fois le rôle de *base* et d'*acide* (**espèce amphotère** ou un **ampholyte**).

On à donc:
$$ H_2O = OH^- + H^+$$
et 
$$ H_3O^+ = H_2O + H^+$$

Ces deux réactions forment **l'autoprotolyse de l'eau** :
$$ 2h_2O \rightleftharpoons HO^- + H_3O^+$$
Sa *constante d'équilibre* notée $K_e$ est définie par :

$$K_e = [HO^-]_{éq}[H_3O^+]_{éq}$$

Cette constante vaut $K_e = 10^{-14}$ et $pK_e = -\log K_e = 14.0$ à $25°\text{C}$

La réaction $H_2O + H^+ \rightarrow H_3O^+$ est donc une réaction quantitative. Ainsi, le *proton* ($H^+$) **n'existe pas** en solution aqueuse.

### Réactions

Une *réaction* [[acido-basique]] mets en jeu deux couple **acide-base** qui s'échangent des protons. On à un couple dont l'acide ($A_1H$) va réagir avec la base ($A_2^-$) de l'autre couple et se transformer en base ($A_1^-$.
$$ A_1H + A_2^- = A_1^- + A_2H$$
La **constante d'acidité** d'un couple [[acido-basique]] notée $K^0_A$ est la constante thermodynamique de l'équilibre entre l'acide $AH$ du couple et l'*eau*.

$$ K^0_A = \frac{[A^-]_{éq} [H_3O^+]_{éq}}{[AH]_{éq}C^0}$$
et $pK_A = - \log K^0_A$

De même, la **constante de basicité** d'un couple [[acido-basique]] notée $K_B^0$ est la constante thermodynamique de l'équilibre entre la base $A^-$ du couple et l'*eau*.
$$ K_B^0 = \frac{[AH]_{éq}[HO^-]_{éq}}{[A^-]_{éq}C^0}$$
et $pK_B = - \log K_B^0$

#### Relations

Pour tout couple [[acido-basique]] on à 
$$K_A \times K_B = [HO^-][H_3O^+] = K_e$$
ou $$pK_A + pK_B = pK_e = 14.0$$
##### Cas de l'eau

$$pK_A(H_2O/HO^-) = 14.0 \text{ et } pK_A(H_3O^+/H_2O) = 0.0$$

#### Axe vertical du $pK_A$ 

On peut placer les couple *acido-basiques* sur un axe vertical de $pK_A$ :
![[pka.jpg]]

Cet axe ne permet de placer que les acides et les bases **faibles**.

### Étude thermodynamique

Lors d'une réaction entre deux couple *acido-basiques* on peut déterminer leur **constante d'équilibre thermodynamique**.
Pour la réaction $$A_1H + A_2^- \leftrightharpoons A_1^-+A_2H$$
On à :

$$ K^0 = \frac{K_{A,1}^0}{K_{A,2}^0}$$

Ainsi, quand deux couple [[acido-basique]] sont mis en contact dans une solution, la **réaction la plus favorable** ce produit toujours entre **l'acide le plus fort** ($pK_A$ faible) et la **base la plus forte** ($pK_A$ élevé).

### Acides et bases forts

Les **acides forts** et les **bases fortes** sont les espèces dont la **réaction avec l'eau est totale**.

Ils sont donc totalement dissociés.

### État final

#### $pH$ et $pOH$

On peut caractériser une solution aqueuse en fonction de son **acidité** et de la **basicité** grace à deux indicateurs :
 1. Le $pH$ qui mesure la concentration en **ions oxonium** ($H_30^+$) qui s'exprime $pH = -\log ~[H_3O^+]$
 2. Le $pOH$ qui mesure la concentration en **ions hydroxyde** ($HO^-$) qui s'exprime $pH = -\log ~[HO^-]$

Ces deux grandeurs sont liées par une relation inverse de proportionalité. $pK_e = pH + pOH$

De plus, on peut lier le $pH$ au $pK_A$ des solutés par la relation d'Henderson-Hasselbalch :
$$pH = pK_A + \log\frac{[A^-]_{éq}}{[AH]_{éq}}$$

Cette relation est vraie pour tout système à l'**équilibre thermodynamique**, indépendamment du nombre de composés chimiques.


#### Diagramme de prédominance

Un diagramme de prédominance montre le rapport entre la base et l'acide d'un couple en fonction du $pH$.

![[prédomiance.png]]

### Méthodes

Dans le cadre de l'analyse thermodynamique d'un système chimique, il faut pouvoir déterminer la valeur des grandeurs qui le définissent à son état final. Ainsi, on va devoir obtenir la concentration des différents éléments et le $pH$ de la solution après une réaction.

#### Identifier les espèces

1. Dans le cas d'acides et de bases **forts**, il faut noter qu'il sont **entièrement dissociés** et noter les produits de cette décomposition.
2. De même, les **sels** sont aussi entièrement dissociés
#### Calculer les concentration 

Après l'addition d'espèce chimiques à une solution, le volume total va varier, et donc modifier les valeurs initiales de concentration. Il faut donc les recalculer en fonction du *nouveau* volume total.
#### Axe de $pK_A$ 

Avant de déterminer les réaction, il est pratique de tracer un axe vertical des $pK_A$ qui comprends **toutes les espèces** présentes dans la solution, sans oublier les **deux couples de l'eau**.
#### Identifier la réaction

Pour étudier le système, il va d'abord falloir identifier la réaction qui se produit. Il va toujours s'agir de la réaction la plus **thermodynamiquement favorable** c'est à dire celle entre la **base** du couple avec le $pK_A$ le plus élevé et l'**acide** du couple avec le $pK_A$ le plus faible.

Ensuite, il va falloir en calculer la **constante d'équilibre** $K^0$.

#### Tableau d'avancement

Afin de déterminer la composition à l'équilibre, il faut dresser un **tableau d'avancement** qui détail les variation dans les concentrations des solutés. 

Si possible, il faudra faires des **hypothèses simplificatrices**:
 - Hypothèse de **fort avancement**
 - Hypothèse de **faible avancement**.

#### Composition et $pH$ à l'équilibre

On peut maintenant enfin noter la composition à partir du tableau d'avancement et calculer le $pH$ à l'équilibre.

### Solutions tampons

On appelle **solution tampon** une solution dont le $pH$ varie très peu si il y a addition d'*acide* ou de *base*. Elle est caractérisée par son **pouvoir tampon** ($\beta$) :
$$ \beta = \frac{dC_{\text{base}}}{d\text{pH}} = \frac{dC_{\text{acide}}}{d\text{pH}}$$
Le pouvoir tampon représente le **taux de change** du $pH$ en fonction d'addition d'*acide* ou de *base*. Plus $\beta$ est grand, plus le tampon est **efficace**.

L'idée de **solution tampon** est très utile en [[biochimie]] car les espèces étudiées ne peuvent exister que dans un intervalle restreint de $pH$. Ainsi, le *sang humain* est une solution tampon qui varie uniquement entre $7.37$ et $7.43$.

### Acides aminés

Un [[biochimie#Acides aminés]] est une molécule qui comporte, sur un même atome deux carbone, un groupe *acide carboxylique* et un groupement *amine*.

Ces deux groupement ayant des propriétés *acido-basiques*, les **acides aminés** sont caractérisés par **deux valeurs de $pK_A$.

Dans une solution, un **acide-aminé** réagit avec lui même et se transforme en **amphion** ou **swittérion**. Ainsi, il va se comporter comme une **base** dans un milieu **acide** et comme un **acide** dans un milieu **basique**. 

Il va donc avoir un diagramme de prédominance en trois parties : 
1. $pH < pK_1$ : il réagit comme base et prédomine en acide $AH^+_2$ 
2. $pK_1 < pH < pK_2$ : il reste sous forme de **swittérion** $AH^\pm$ 
3. $pK_2 < pH$ : il réagit comme acide et prédomine en base $A^-$

![[diagrame-acide-base-swittérion.png]]

#### $pH$ d'une solution d'acide aminé

L'**amphion** est un ampholyte. On peut déterminer le $pH$ d'une solution avec la relation $pH = \frac{1}{2}(pK_{A,1} + pK_{A,2})$


#### Électrophorèse

L'**amphion** est un espèce électriquement neutre, sa **conductivité** est nulle. Ainsi, une modification du $pH$ entraînant une dissociation de l'**amphion** va fortement augmenter la conductivité de la solution.

Le [[point isoélectrique]] d'une solution d'acide aminé est représenté par le $pH$ pour lequel il existe uniquement sous forme de **swittérion** donc $pI = \frac{1}{2}(pK_{A,1},pK_{A,2})$

Ainsi, l'[[électrophorèse]] peut nous permettre d'**analyser** une solution d'acide aminé et de **séparer** les constituant d'un mélanges de plusieurs *acides aminés*.

# Réaction d’oxyde-réduction

Un **oxydant** est une espèce qui peut *capter* un ou plusieurs **électrons** ($e^-$) d'une autre espèce.
Un **réducteur** est une espèce qui peut *céder* un ou plusieurs **électrons** ($e^-$)à une autre espèce.

L'association d'un oxydant et d'un réducteur forme un **couple rédox** symbolisé par l'équation :
$$\text{Ox} + ne⁻ = \text{Red}$$

>[!cas de l'eau]
>L'eau intervient dans deux réactions :
> - $H_2O/H_2$ ou $H^+/H_2$  
> - $O_2/H_2O$
> 
> Ainsi, elle est l'**oxydant** d'un couple  et le **réducteur** d'un autre. Il s'agit donc d'un **ampholyte redox**

### Nombres d'oxydation

Un élément dans une *espèce chimique* est caractérisé par son **nombre d'oxydation** qui reflète son état d'oxydation. Il s'agit d'un nombre entier noté en *chiffres romains*. Le **nombre d'oxydation** d'un élément varie en fonction de l'espèce chimique à laquelle il est associé.

En général on à $\text{no.}(O) = -II$ et $\text{no.}(H) = +1$.

### Réactions

On ne peut pas avoir d'[[électrons]] libres en solution. Pour qu'une réaction d'**oxydo-réduction** se produise il faut deux couple $\text{Ox}/\text{Red}$ qui s'échanges des électrons entre le **réducteur** d'un des couples et l'**oxydant** de l'autre.

$$ \alpha~\text{Ox}_1 + \beta~\text{Red}_2 \rightleftarrows \beta'~\text{Red}_1  + \alpha' \text{Ox}_2$$

Les transferts d'électrons peuvent avoir lieu directement dans la solution, ou passer par un **circuit électrique**. 

Lorsqu'un *ampholyte redox* réagit sur lui même, il s'agit d'une réaction de **dismutation** et la réaction inverse une **médiamutation**.

Une réaction d'**oxydation** d'un élément entre deux espèces d'une couple *redox* se traduit par une **augmentation** de son nombre d'oxydation. De même une réaction de **réduction** d'accompagne d'une **diminution** de son nombre d'oxydation.

### Potentiel redox

Un **couple redox** est caractérisé par un **potentiel redox**. Il s'agit d'une grandeur thermodynamique exprimée en *volts* ($V$). On ne peut pas le mesurer directement, on ne peut en mesurer qu'une différence. Il dépends des conditions expérimentales comme la **concentration** des solutés ou la **pression partielle** des composés gazeux. 

Le **potentiel redox** ($E_{\text{Ox}/\text{Red}}$) est défini par la **relation de Nernst** : $$ E_{\text{Ox}/\text{Red}} = E^0_{\text{Ox}/\text{Red}} + \frac{RT}{nF}\ln\Bigg(\frac{\Pi_{i,\text{Ox}}a_i^{\alpha_i}}{\Pi_{i,\text{Red}}a_i^{\alpha_i}}\Bigg)$$
 - $E^0_{\text{Ox}/\text{Red}}$ représente le **potentiel standard** ($V$)
 - $R$ est la **constante des gaz parfaits** ($8.31 \frac{J}{K\times\text{mol}}$)
 - $T$ est la **température** du système ($K$)
 - $F$ est la **constante de Faraday** ($96500~C$)
 - $n$ est le nombre d'[[électrons]] échangés entre l'oxydant et de réducteur.
 - $a_i$ représente les **activités** des espèces 
 - $\alpha_i$ représente les **coefficients stœchiométriques** des espèces 

En pratique, à $25°C$ et avec le $\log$ décimal on obtient: $$E_{\text{Ox}/\text{Red}} = E^0_{\text{Ox}/\text{Red}} + \frac{0.059}{n}\log\Bigg(\frac{\Pi_{i,\text{Ox}}a_i^{\alpha_i}}{\Pi_{i,\text{Red}}a_i^{\alpha_i}}\Bigg)$$

Le **potentiel standard** d'un *couple redox* correspond au *potentiel redox* des différents constituants du couple dans leur *état standard*.

> [!Analogie avec l'acido-basicité]
> Le **potentiel standard** d'un couple *redox* est similaire au $pK_A$ d'un couple [[acido-basique]], le **potentiel redox** est similaire au $pH$.

#### Influence du $pH$

Le $pH$ peu avoir une influence sur le potentiel standard. On parle alors de **potentiel standard apparent**, qui représente la valeur du **potentiel standard** ajusté pour $pH$.
### Classement

On peut classer les différent *couples redox* selon leur **pouvoir d'oxydo-réduction** grâce à leur **potentiel standard**.

Ainsi, plus un couple à un **potentiel standard** élevé, plus la puissance de son **oxydant** est élevée. A l'inverse, plus le **potentiel standard** est faible plus la puissance de son réducteur est élevée.

On peut placer les *couples redox* sur une échelle verticale :![[redox-vertical-postd.png]]

Dans le cas d'une **réaction redox**, l'***oxydant** le plus fort* va réagir avec le ***réducteur** le plus fort*. C'est à dire l'**oxydant** du couple au *potentiel standard* le plus fort et le **réducteur** du couple au *potentiel standard* le plus faible.

### Étude thermodynamique

On peut déterminer la **constante d'équilibre** d'une réaction *redox* grâce à la **relation de Nernst**.  En effet, dans une réaction les *potentiels redox* des différents couple sont égaux à l'**équilibre thermodynamique**.

Ainsi pour une réaction $\alpha~\text{Ox}_1 + \beta~\text{Red}_2 \rightleftarrows \beta'~\text{Red}_1  + \alpha' \text{Ox}_2$ on à  $$\displaystyle K^0 = 10^{\frac{n}{0,059}(E_1^0-E_2^0)}$$

#### Diagramme

On peut dresser un diagramme similaire à celui des réactions *acido-basiques*.

De plus, on sait qu'a la **fontière** les **concentrations** sont égales.

### Piles électrochimiques

La mise en place d'une *réaction redox* crée une différence de potentielle entre deux **demi piles**, sièges des *demi-équations redox*. Ainsi, l'association de deux **demi-piles** reliées par un **pont salin** qui permet la circulation des **ions** et par un **circuit électrique** qui permet la circulation des [[électrons]] donne une **pile**.

Une **pile** est donc composée d'une **anode**, c'est à dire la partie ou se produit l'**oxydation** et d'une **cathode** ou se produit la **réduction**.

La **force électromotrice** désigne la tension électrique définie par la différence de potentiel entre les deux **demi piles** ($e = E_+ - E_-$)

#### Capacité

La capacité ($Q$) d'une pile est la **quantité d'électricité** qu'une pile peut délivrer au cours de son fonctionnement.

$$Q = n_{e⁻} \times \mathscr{F} = n ~\xi~ \mathscr{F} $$
 -  $\mathscr{F}$ étant la constante de Faraday ($96500\frac{C}{\text{mol}}$)
 - $n_{e^-}$ étant le nombre d'électrons ayant circulé
 - $n$ étant le nombre d'électrons échangés entre les couple dans la réaction
 - $\xi$ étant l'avancement molaire à la fin

On peut donc aussi écrire $Q = I \times \Delta t$

#### Électrolyseur

L'**électrolyse** représente la réaction *inverse* de la **pile**. Elle consiste à forcer la réalisation de réactions *thermodynamiquement défavorables* à l'aide d'un apport en électricité.

On va donc inverser l'*anode* et la *cathode*.

# Titrages

Le **titrage** est le procédé de détermination de la quantité de matière d'un constituant présent dans une solution, que l'on va alors appeller *espèce titrée* à l'aide d'une réaction avec une autre espèce connue appelée *espèce titrante*.

Une réaction doit satisfaire trois conditions pour être utilisée dans un titrage :
1. Elle doit être **quantitative** ($K^0 > 10^4$)
2. Elle doit se faire *rapidement* 
3. Elle doit être **unique** et connue

On va donc ajouter progressivement l'*espèce titrante* à la solution, jusqu'à atteindre l'**équivalence du titrage**. Cette équivalence est atteinte quand les réactif ont été introduits dans les proportions stœchiométriques.

Ainsi, on peut exprimer une relation entre les quantités de matière de l'espèce **titrante** et celle de l'espèce **titrée** :
$$\frac{n_1}{|\nu_1|} = \frac{n_2}{|\nu_2|}$$

### Détermination de l'équivalence

Il existe plusieurs méthodes pour déterminer l'équivalence lors d'un titrage. Ces méthodes sont basées sur l'observation des variables du système considéré.

#### Détermination par le $pH$

Lors du titrage pas une réaction **acido-basique** on peut se servir du $pH$ comme un indicateur de l'équivalence. On observe un *saut brutal* du $pH$ au moment de l'équivalence. Autrement dit, la dérivée du $pH$ par rapport au volume titrant ($\frac{d\text{pH}}{dV}$) est maximale.

#### Suivi conductimétrique

On peut utiliser la conductivité de la solution

### Cas complexes

Dans le cas d'un polyacide, ou de couples *redox* difficiles, le titrage peut être complexe. *Good Luck !*