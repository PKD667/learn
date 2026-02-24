Une **transformation thermodynamique** fait passer un [[système thermodynamique]] d'un état d'équilibre à un autre. On s'intéresse aux échanges d'énergie ($W$, $Q$) et aux variations des fonctions d'état ($\Delta U$, $\Delta H$, $\Delta S$).

## Types de transformations

On classe souvent les transformations selon la grandeur maintenue constante :

**Isotherme** ($T = \text{cte}$) : pour un [[gaz parfait]], $\Delta U = 0$ donc $Q = -W$.

**Isobare** ($P = \text{cte}$) : le transfert thermique égale la variation d'[[enthalpie]], $Q_P = \Delta H$. C'est le cas le plus courant en chimie (réactions à pression atmosphérique).

**Isochore** ($V = \text{cte}$) : pas de travail des forces de pression ($W = 0$), donc $Q_V = \Delta U$.

**Adiabatique** ($Q = 0$) : pas d'échange thermique. $\Delta U = W$. Pour un gaz parfait, $PV^\gamma = \text{cte}$ le long d'une adiabatique réversible.

## Réversibilité

Une transformation **réversible** est une suite continue d'états d'équilibre. Le système évolue infiniment lentement, $P_\text{int} = P_\text{ext}$ à chaque instant. L'[[entropie]] créée est nulle : $S_c = 0$.

En pratique, c'est une idéalisation. Toute transformation réelle est **irréversible** : frottements, gradients de température, détentes brutales... L'irréversibilité se manifeste par $S_c > 0$.

## Travail des forces de pression

$$W = -\int P_\text{ext} dV$$

Le signe moins traduit la convention : compression ($dV < 0$) → travail reçu ($W > 0$).

Pour une transformation réversible, $P_\text{ext} = P$ et le travail est l'aire sous la courbe $P(V)$. Pour une transformation irréversible, $P_\text{ext}$ est imposée (souvent constante) et le travail diffère.

>[!example] Détente isotherme réversible (gaz parfait)
> $\Delta U = 0$ donc $Q = -W$.
> $W = -nRT \ln\frac{V_f}{V_i}$
> Si $V_f > V_i$ (détente), $W < 0$ : le gaz fournit du travail et absorbe de la chaleur.

## Transformations cycliques

Le système revient à son état initial : $\Delta U = 0$, $\Delta S = 0$. Donc $W = -Q$. C'est le principe des machines thermiques : convertir chaleur en travail (moteur) ou l'inverse (pompe à chaleur).
