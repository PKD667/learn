L'**enthalpie** $H$ est définie par $H = U + PV$. C'est une combinaison de l'[[énergie interne]] et du terme $PV$. Son intérêt principal : à **pression constante**, $\Delta H = Q_P$.

## Pourquoi cette définition

En chimie, la plupart des réactions se font à pression atmosphérique (système ouvert à l'air). À pression constante :
$$\Delta U = Q_P - P\Delta V$$
$$Q_P = \Delta U + P\Delta V = \Delta(U + PV) = \Delta H$$

Mesurer la chaleur échangée donne directement $\Delta H$. C'est beaucoup plus pratique que de travailler avec $\Delta U$.

## Capacité thermique à pression constante

$$C_P = \left(\frac{\partial H}{\partial T}\right)_P$$

Pour un [[gaz parfait]], $C_P = C_V + nR$ (relation de Mayer). $C_P > C_V$ car à pression constante, une partie de l'énergie sert à faire du travail contre la pression extérieure.

## Cas du gaz parfait

Comme pour $U$, l'enthalpie d'un gaz parfait ne dépend que de $T$ :
$$H = H(T) \quad \Rightarrow \quad dH = C_P dT$$

C'est la **seconde loi de Joule**.

## En thermochimie

L'enthalpie est omniprésente en chimie :

- L'[[enthalpie de réaction]] $\Delta_r H$ donne la chaleur échangée par une réaction à $P$ constante
- L'[[enthalpie de formation]] $\Delta_f H°$ est tabulée pour calculer $\Delta_r H$ via la [[loi de Hess]]
- L'[[enthalpie libre]] $G = H - TS$ détermine la spontanéité

## Changements d'état

Lors d'un [[changement d'état]] à $P$ constante, $\Delta H = Q_P$ correspond à la **chaleur latente**. Pour vaporiser l'eau à 100°C : $\Delta_\text{vap}H = 40.7$ kJ·mol⁻¹. Cette énergie brise les liaisons hydrogène sans changer la température.

>[!example] Pourquoi $C_P > C_V$
> À volume constant, toute la chaleur augmente $U$ (et donc $T$).
> À pression constante, une partie de la chaleur sert à faire du travail ($-P\Delta V$) car le gaz se dilate.
> Il faut donc plus de chaleur pour obtenir la même augmentation de température.
