L'**énergie interne** $U$ représente l'énergie totale contenue dans un [[système thermodynamique]] : énergie cinétique des molécules (agitation thermique) et énergie potentielle d'interaction entre elles. Elle ne comprend pas l'énergie cinétique macroscopique ni l'énergie potentielle de position du système.

## Le premier principe

Le [[premier principe]] dit que $U$ ne peut varier que par échange avec l'extérieur :
$$\Delta U = W + Q$$

Le [[travail thermodynamique|travail]] $W$ et le [[transfert thermique]] $Q$ sont les deux seules façons de modifier $U$. Pour un système isolé, $\Delta U = 0$.

## Pourquoi c'est une fonction d'état

$U$ ne dépend que de l'état actuel du système, pas de son histoire. On peut aller de A à B par plusieurs chemins avec des $W$ et $Q$ différents, mais $\Delta U = U_B - U_A$ sera toujours le même. C'est ce qui distingue $U$ de $W$ et $Q$.

## À volume constant

Si $V$ est constant, il n'y a pas de travail des forces de pression ($W = 0$) et :
$$\Delta U = Q_V$$

Toute la chaleur échangée va dans l'énergie interne. C'est pour ça qu'on définit la [[capacité thermique]] à volume constant :
$$C_V = \left(\frac{\partial U}{\partial T}\right)_V$$

## Cas du gaz parfait

Pour un [[gaz parfait]], les molécules n'interagissent pas. L'énergie potentielle d'interaction est nulle, il ne reste que l'énergie cinétique. Celle-ci ne dépend que de la température :
$$U = U(T) \quad \Rightarrow \quad dU = C_V dT$$

C'est la **première loi de Joule**. Conséquence : lors d'une détente isotherme, $\Delta U = 0$ donc $Q = -W$.

## Relation avec l'enthalpie

L'[[enthalpie]] $H = U + PV$ est plus pratique à pression constante (cas courant en chimie). Pour un gaz parfait, $H$ aussi ne dépend que de $T$.

>[!example] Compression isochore
> Un gaz chauffé à volume constant reçoit $Q > 0$.
> Comme $W = 0$, on a $\Delta U = Q = C_V \Delta T$.
> Toute la chaleur sert à augmenter l'énergie interne (et donc la température).
