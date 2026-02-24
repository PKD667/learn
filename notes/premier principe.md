Le **premier principe** est la conservation de l'énergie appliquée aux systèmes thermodynamiques.

## Énoncé

Pour un [[système thermodynamique]] fermé :
$$\Delta U = W + Q$$

L'[[énergie interne]] $U$ ne peut changer que par deux voies : le [[travail thermodynamique|travail]] $W$ (énergie mécanique) ou le [[transfert thermique]] $Q$ (énergie thermique). Il n'y a pas de création d'énergie.

## Fonction d'état vs chemin

$U$ est une **fonction d'état** : sa variation $\Delta U$ ne dépend que des états initial et final, pas du chemin. En revanche, $W$ et $Q$ dépendent du chemin suivi. On peut aller de A à B par plusieurs chemins avec des $W$ et $Q$ différents, mais $\Delta U$ sera toujours le même.

C'est pourquoi on écrit $\delta W$ et $\delta Q$ (formes différentielles non exactes) mais $dU$ (différentielle exacte).

## Cas particuliers

**Isochore** ($V$ constant) : pas de travail des forces de pression, donc $\Delta U = Q_V$. Toute la chaleur va dans l'énergie interne.

**Isobare** ($P$ constant) : on introduit l'[[enthalpie]] $H = U + PV$ car $\Delta H = Q_P$. Plus pratique expérimentalement.

**Adiabatique** ($Q = 0$) : $\Delta U = W$. Une compression adiabatique chauffe le gaz (pompe à vélo).

**Cyclique** (retour à l'état initial) : $\Delta U = 0$ donc $W = -Q$. Base des machines thermiques.

>[!example] Compression adiabatique
> Un gaz comprimé rapidement (sans échange de chaleur) reçoit du travail ($W > 0$).
> Comme $Q = 0$, on a $\Delta U = W > 0$ : la température augmente.

## Lien avec le second principe

Le premier principe dit que l'énergie se conserve, mais ne dit rien sur le sens des transformations. C'est le [[second principe]] qui l'impose via l'[[entropie]].
