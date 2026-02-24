La **constante d'équilibre** $K°(T)$ caractérise l'état d'équilibre d'une [[réaction chimique]] à une température donnée.

## Définition (Guldberg-Waage)

$$K°(T) = Q_{r,\text{éq}} = \prod_i (a_{i,\text{éq}})^{\nu_i}$$

- $a_{i,\text{éq}}$ : [[activité]] à l'équilibre
- $\nu_i$ : coefficients stœchiométriques algébriques

## Relation avec l'enthalpie libre

À l'équilibre : $\Delta_r G = 0$, donc :

$$K°(T) = \exp\left(-\frac{\Delta_r G°(T)}{RT}\right)$$

ou de manière équivalente :

$$\Delta_r G°(T) = -RT\ln K°(T)$$

## Interprétation

| $K°$ | Signification | Approximation |
|------|---------------|---------------|
| $\gg 1$ ($> 10^4$) | Réaction **quantitative** | $\xi_\text{éq} \approx \xi_\text{max}$ |
| $\ll 1$ ($< 10^{-4}$) | Réaction **très limitée** | $\xi_\text{éq} \approx 0$ |
| $\approx 1$ | Réaction **équilibrée** | Calcul exact nécessaire |

## Critère d'évolution

En comparant le [[quotient de réaction]] $Q_r$ à $K°$ :

| Condition | Évolution |
|-----------|-----------|
| $Q_r < K°$ | Sens direct ($\xi$ augmente) |
| $Q_r = K°$ | Équilibre |
| $Q_r > K°$ | Sens indirect ($\xi$ diminue) |

## Dépendance en température

Voir [[loi de Van't Hoff]] :
$$\frac{d(\ln K°)}{dT} = \frac{\Delta_r H°}{RT^2}$$

>[!example] Synthèse de l'ammoniac (450°C)
> $\text{N}_2(g) + 3\text{H}_2(g) \rightleftharpoons 2\text{NH}_3(g)$
> 
> $K° \approx 0.5$ à 450°C
> 
> Réaction équilibrée, nécessite haute pression pour favoriser les produits.

## Voir aussi

- [[quotient de réaction]]
- [[enthalpie libre]]
- [[loi de Van't Hoff]]
- [[équilibre chimique]]
