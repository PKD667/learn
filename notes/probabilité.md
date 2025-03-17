La probabilité est un outil mathématique pour étudier les phénomènes incertains et le futur.

Il existe deux définitions majeures de la probabilité :
1. La définition **bayésienne**
2. La définition **fréquentiste**

### Probabilité fréquentiste

> « Le probable est ce qui arrive le plus souvent » 
>   — Aristote, Rhétorique

La vision **fréquentiste** définit la probabilité d'un événement comme à la fréquence de sa réalisation au cours d'un nombre *empirique* ou *théorique* d'essais. Ainsi, les probabilités se retrouvent vidées de toute ambition **prédictive** et ne peuvent que servir d'outil pour décrire des phénomènes connus. 

### Probabilité bayésienne

La vision **bayésienne** considère les probabilités comme des **estimations** de phénomènes inconnus. Ainsi, on peut considérer qu'elle étends le domaine de la [[logique mathématique]] à l'étude de propositions dont la valeur est *inconnue*.

Cette interprétation mets en avant la **mise à jour** de l'*a priori* par rapport à des données nouvelles. 

# Probabilité et mesures

On appelle **mesure** sur un ensemble $X$ une function qui lie un nombre $m(S) \in [0,\infty]$ à des sous ensembles $S \subseteq X$ dit *mesurables*. 

Cette mesure est définie par trois critères :
1. $\emptyset,X \subseteq X$ sont *mesurables* et $m(\emptyset) = 0$
2. Si $S,T \subseteq X$ sont mesurables alors $T-S$ est mesurable et $\displaystyle m(T) = m(S) + m(T-S)$ 
3. Pour toute *collection comptable* de sous-ensembles $S_i \subseteq X$ sont *mesurables* alors leur **union** mesurable et  $\displaystyle m \big(  \bigcup^\infty_{i=1}S_i\big) = \sum^\infty_{i=1}m(S_i)$

On dit que $m$ est une *mesure de probabilité* si $m(X) = 1$.

