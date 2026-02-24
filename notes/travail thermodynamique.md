Le **travail** $W$ est l'énergie échangée sous forme mécanique entre un [[système thermodynamique]] et l'extérieur. Avec le [[transfert thermique]] $Q$, c'est l'un des deux modes d'échange d'énergie.

## Convention de signe

- $W > 0$ : travail **reçu** par le système (compression)
- $W < 0$ : travail **fourni** par le système (détente)

## Travail des forces de pression

Pour un système soumis à une pression extérieure $P_\text{ext}$ :
$$\delta W = -P_\text{ext} \, dV$$

Le signe moins traduit la convention : quand le volume diminue ($dV < 0$), le système reçoit du travail ($\delta W > 0$).

Pour une transformation finie :
$$W = -\int_{V_i}^{V_f} P_\text{ext} \, dV$$

## Cas réversible vs irréversible

**Réversible** : le système est à l'équilibre à chaque instant, donc $P_\text{ext} = P$. Le travail est l'aire sous la courbe $P(V)$ dans le diagramme de Clapeyron.

**Irréversible** : $P_\text{ext}$ est imposée (souvent constante). Le travail diffère : une compression brutale contre $P_\text{ext}$ constante donne $W = -P_\text{ext}(V_f - V_i)$, qui est plus grand (en valeur absolue) que le travail réversible.

C'est une manifestation de l'irréversibilité : on "gaspille" de l'énergie.

## Cas particuliers

**Isochore** : $V = \text{cte}$, donc $W = 0$.

**Isobare réversible** : $P = \text{cte}$, donc $W = -P(V_f - V_i) = -P\Delta V$.

**Isotherme réversible** (gaz parfait) : $PV = nRT = \text{cte}$, donc $P = nRT/V$ et :
$$W = -nRT \ln\frac{V_f}{V_i}$$

## Travail électrique

Un système peut aussi recevoir du travail électrique. Pour une résistance traversée par un courant :
$$W_\text{élec} = RI^2 \Delta t$$

C'est l'**effet Joule** : le travail électrique se dissipe intégralement en chaleur dans le système.

$W$ dépend du **chemin suivi**, pas seulement des états initial et final. On peut aller de A à B par plusieurs chemins avec des travaux différents. C'est pourquoi on écrit $\delta W$ et non $dW$.
