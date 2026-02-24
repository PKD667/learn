Le **potentiel chimique**, noté $\mu_i$, est l'[[enthalpie libre]] molaire partielle d'un constituant $i$ dans un mélange. C'est la grandeur clé de la thermochimie.

## Définition

$$\mu_i = \left(\frac{\partial G}{\partial n_i}\right)_{T,P,n_{j\neq i}} = G_{m,i}$$

C'est une [[grandeur molaire partielle]].

## Expression générale

$$\mu_i(T,P,\text{composition}) = \mu_i°(T) + RT\ln a_i$$

- $\mu_i°(T)$ : potentiel chimique standard (ne dépend que de $T$)
- $a_i$ : [[activité]] du constituant

## Différentielle de G

$$dG = VdP - SdT + \sum_i \mu_i dn_i$$

Cette équation relie toutes les variables thermodynamiques.

## Critère d'équilibre

Un système évolue vers les **potentiels chimiques les plus bas**.

À l'équilibre entre deux phases $\alpha$ et $\beta$ :
$$\mu_i^{(\alpha)} = \mu_i^{(\beta)}$$

>[!example] Diamant vs graphite (25°C, 1 bar)
> - $\mu(C_\text{diamant}) = 2.9$ kJ·mol⁻¹
> - $\mu(C_\text{graphite}) = 0.0$ kJ·mol⁻¹
> 
> Le graphite est stable, le diamant est **métastable** (transformation cinétiquement bloquée).

## Changement d'état

Pour la vaporisation d'un corps $A$ :
$$\Delta_\text{vap}G_A = \mu_A(g) - \mu_A(l)$$

## Voir aussi

- [[activité]]
- [[grandeur molaire partielle]]
- [[enthalpie libre]]
- [[équilibre chimique]]
