Un signal est une **grandeur physique** porteuse d'une **information**, qui peut-être modélisée par une **fonction mathématique** d'une ou plusieurs variables (*temps ou coordonnées de l'espace*). Cette information est transmise d'un **émetteur** vers un **récepteur**.

Il existe plusieurs types de signaux :
 - Signaux dépendants du temps $s(t)$
 - Signaux dépendants de l'espace $s(x,y,z)$
 - Signaux dépendants du temps et de l'espace $s(x,y,z,t)$

Un signal peut être de différentes natures, selon le type de **support de l'information**, qui impact aussi la nature du **récepteur**. On a:
 - *Signal lumineux*
 - *Signal électromagnétique*
 - *Signal mécanique*
 - *Signal thermodynamique*

### Caractéristique des signaux mécaniques

Les signaux mécaniques se propagent dans un **milieu materiel**, et se caractérisent par une **déformation locale** du milieu par déplacement des atomes. Le signal est une fonction du temps et de l'espace $s(x,y,z,t)$.

#### Signaux acoustiques

Les signaux acoustiques sont des cas particuliers de signaux mécaniques. Il se propagent dans l'air et sont caractérisés par une [[fréquence]], une **amplitude**, une **durée** et une **forme**.

#### Signaux sismiques

les signaux sismiques sont des signaux mécaniques qui se propagent dans le sol.

### Ondes longitudinales et transversales

#### Définitions

Une onde **longitudinale** est une onde dont la perturbation est *parallèle* à la direction de propagation.
Une onde **transversale** est une onde dont la perturbation est *perpendiculaire* à la direction de propagation.

### Propagation dans un milieu matériel

*Dans la réalité les signaux sont atténués par le milieu, mais nous n'en tiendrons pas compte dans la suite.*

On suppose que les signaux considérés se propagent dans un milieu **homogène,illimité,non dispersif et transparent**.
 - **Homogène** : même caractéristiques en tout point.
 - **Illimité** : taille infinie du milieu.
 - **Non dispersif** : la propagation garde ses caractéristiques (en particulier la *célérité*) quelle que soit la longueur d'onde du signal.
 - **Transparent**: pas d'absorption du signal

#### Célérité 

La **célérité** d'un signal est la vitesse à laquelle se propage le signal dans le milieu.

$$[c] = [\text{vitesse}] = \frac{[\text{distance}]}{[\text{temps}]} = \frac{L}{T} = L.T^{-1}$$
$$[f] = T^{-1}$$
$$[\lambda] = L$$
$$[T] = T$$

La célérité d'un signal est affectée par de nombreux facteurs comme la température ou le milieu. Le son par exemple se propage plus vite dans l'eau que dans l'air.

Célérité du son dans *l'air* : $340 \phantom | m.s^{-1}$ 
Célérité du son dans *l'eau*: $1482 \phantom | m.s^{-1}$


#### Signal unidimensionnel

On considère un **signal unidimensionnel**, c'est à dire qui se propage selon **une seule direction de l'espace**, qui sera notée axe $O(x)$. 
$S$ ne dépend sont plus que d'une seule coordonnée de l'espace et du temps. Le signal est une fonction de ces deux variables : $s(x,t)$.

On appelle **retard temporel** le délai de propagation du signal au point $M$ d'abscisse $x$ en partant de $x=0$. On le note $\tau$.
On peut lier ce **retard temporel** à la célérité : $c = \frac{x}{\tau}$
On peut écrire la *conservation de l'information* : $s(x=0,t) = s(x,t+\frac{x}{c})$
Pour que la signal arrive en $M$ à la date $t$ il faut qu'il ait été émis en $O$ à la date $t-\tau$

Le décalage dans l'espace d'appelle **retard spatial**.
b
#### Signaux sinusoïdaux

##### Signal périodique

Un signal est périodique si il est constitué d'un *motif* qui se répète a l'identique à intervalles de temps réguliers. La période est l'intervalle de répétition le plus petit.

##### Signal alternatif 

Un signal est dit alternatif si sa valeur moyenne est null. On peut aussi dire que l'aire sous sa courbe pour une période est *algébriquement nulle*.

##### Signal sinusoïdal

Un signal sinusoïdal est un signal **périodique alternatif** particulier qui peut s'écrire:
$$s(t) = S_m \cos(\omega t + \varphi)$$
$S_m$ est **l'amplitude** du signal 
$\varphi$ est la **phase à l'origine**, c'est à dire à $t = 0$ ($\omega t + \varphi$ est la phase à l'instant $t$), *en $\text{rad}$*.
$\omega$ est la **pulsation** en $\text{rad}.s^{-1}$.

*Attention à la conversion [[degrés - radians]]*

La **période** $T$ est la **plus petite durée** au bout de laquelle, en un point donné, le système se retrouve dans le même état qu'a l'instant $t=0$.

$s(x,0) = s(x,T) \text{ ou } s(x,t) = s(x,t+T)$

**Relation entre la pulsation et la période**

$\omega = \frac{2\pi}{T} = 2\pi f$

Chaque période d'une fonction sinusoïdale correspond à un parcours de $2\pi$, c'est à dire une rotation d'une cercle.

**Calcul de la phase à l'origine**

$s(t) = S_m \times \cos(11t + \varphi)$
$s(t = 0) = S_m \times \cos(\varphi)$
$\cos(\varphi) = \frac{s(t = 0)}{S_m}$
$\varphi = \cos^{-1}(\frac{s(0)}{S})$



