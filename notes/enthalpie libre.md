L'**enthalpie libre** (ou énergie de Gibbs) $G = H - TS$ est la fonction qui détermine la **spontanéité** d'une transformation à température et pression constantes. C'est le critère ultime en chimie.

## Le critère de spontanéité

À $T$ et $P$ constants, une transformation est spontanée si :
$$\Delta G < 0$$

Si $\Delta G > 0$, la transformation n'est pas spontanée (il faudrait fournir de l'énergie). Si $\Delta G = 0$, le système est à l'équilibre.

## Pourquoi $G$ et pas $H$ ou $S$ seuls

Le [[premier principe]] (conservation de $U$) et le [[second principe]] (croissance de $S$) s'appliquent à l'**univers** (système + extérieur). Mais on veut un critère portant sur le **système seul**.

À $T$ et $P$ constants, on peut montrer que $\Delta S_\text{univers} = -\Delta G/T$. Donc $\Delta G < 0$ équivaut à $\Delta S_\text{univers} > 0$ : le second principe est respecté.

## La compétition enthalpie/entropie

$$\Delta G = \Delta H - T\Delta S$$

Deux effets s'opposent :
- $\Delta H < 0$ (exothermique) favorise la réaction
- $\Delta S > 0$ (création de désordre) favorise la réaction

À basse $T$, c'est $\Delta H$ qui domine. À haute $T$, c'est $\Delta S$.

| $\Delta H$ | $\Delta S$ | Spontanéité |
|------------|------------|-------------|
| $< 0$ | $> 0$ | Toujours spontanée |
| $> 0$ | $< 0$ | Jamais spontanée |
| $< 0$ | $< 0$ | Spontanée à basse $T$ |
| $> 0$ | $> 0$ | Spontanée à haute $T$ |

## Lien avec l'équilibre

À l'équilibre, $\Delta_r G = 0$. Cela donne la relation fondamentale :
$$\Delta_r G° = -RT \ln K°$$

La [[constante d'équilibre]] $K°$ est directement liée à $\Delta_r G°$. Une réaction avec $\Delta_r G° \ll 0$ a $K° \gg 1$ : elle est quasi-totale.

## Potentiel chimique

Le [[potentiel chimique]] $\mu_i$ est l'enthalpie libre molaire partielle du constituant $i$. Un système évolue vers les $\mu$ les plus bas. À l'équilibre entre phases, $\mu$ est égal dans toutes les phases.

>[!example] Dissolution du sel
> $\text{NaCl}(s) \rightarrow \text{Na}^+(aq) + \text{Cl}^-(aq)$
> 
> $\Delta H > 0$ (endothermique : la solution refroidit)
> $\Delta S > 0$ (désordre : ions dispersés)
> 
> À 25°C, $T\Delta S > \Delta H$ donc $\Delta G < 0$ : dissolution spontanée malgré l'absorption de chaleur.
