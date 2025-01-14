# Évolution et équilibre d'un système chimique

Rappels [[Moles et concentrations]]

##### Bilan de matière dans un systèmes siège d'une réaction chimiques

La [[réaction chimique]].

Une réaction est dite **thermodynamiquement favorable** si sa constante d'équilibre est supérieure à $1$ ($K^0 > 1$). 
Une réaction est **thermodynamiquement défavorable** si sa constante d'équilibre est inférieure à $1$ ($K^0 < 1$).

### Sens d'évolution d'un système

Si le **coefficient de réaction** est *inférieur* à la constante d'équilibre ($Q_r < K^0$, la réaction va évoluer dans le **sens direct**.
Si le **coefficient de réaction** est *supérieur* ($Q_r > K^0$, la réaction va évoluer dans le **sens indirect**.

#### Réaction *très* défavorable

Si la constante d'équilibre est *très petite* ($K^0 < 10^{-3}$), il s'agit d'une réaction limitée, et on pourra alors utiliser l'**approximation de faible avancement à l'équilibre ($\xi_{éq} \ll n_0$)**. 

#### Réaction *très* favorable

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

### États final 

#### $pH$

Une solution aqueuse est caractérisée par son $pH$ :
$$ pH = -\log ~[H_3O^+]$$
De même :
$$ pOH = - \log~ [HO^-]$$
##### Relations
$$pK_e = pH + pOH$$
$$pH = pK_A + \log\frac{[A^-]_{éq}}{[AH]_{éq}}$$

#### Diagramme de prédominance

Un diagramme de prédominance montre le rapport entre la base et l'acide d'un couple en fonction du $pH$.

![[prédomiance.png]]

# Réaction d’oxyde-réduction

Un **oxydant** est une espèce qui peut *capter* un ou plusieurs **électrons** ($e^-$) d'une autre espèce.
Un **réducteur** est une espèce qui peut *céder* un ou plusieurs **électrons** ($e^-$)à une autre espèce.

L'association d'un oxydant et d'un réducteur forme un **couple rédox** symbolisé par l'équation :
$$\text{Ox} + ne⁻ = \text{Red}$$

#### Cas de l'eau

L'eau intervient dans deux réactions :
 - $H_2O/H_2$ ou $H^+/H_2$  
 - $O_2/H_2O$

Ainsi, elle est l'**oxydant** d'un couple  et le **réducteur** d'un autre. Ilm s'agit donc d'un **ampholyte redox**

### Nombres d'oxydation

Un élément dans une *espèce chimique* est caractérisé par son **nombre d'oxydation** qui reflète son état d'oxydation. Il s'agit d'un nombre entier noté en *chiffres romains*. Le **nombre d'oxydation** d'un élément varie en fonction de l'espèce chimique à laquelle il est associé.




