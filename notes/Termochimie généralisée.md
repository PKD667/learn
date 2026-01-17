
## Fondamentaux thermodynamiques

### Description d'une réaction chimique

Une **équation chimique** met en jeu des réactifs et des produits avec leurs coefficients stœchiométriques : $$ \sum \nu_{R_i} R_i = \sum \nu_{P_i} P_i $$

L'**avancement molaire** $\xi$ quantifie la progression de la réaction : $$ \mathrm{d}\xi = \frac{\mathrm{d}n_i}{\nu_i} $$

**Deux jeux de variables équivalents :**

- **Variables de Gibbs** : $(T, P, n_1, \ldots, n_k)$ → $2+k$ variables
- **Variables de De Donder** : $(T, P, \xi)$ → 3 variables seulement

### État standard de référence (ESR)

L'ESR d'un élément est son état le plus stable dans des conditions standard ($P° = 1$ bar, $T = 25°C$).

**Exemples :**

- Hydrogène : $H_2(g)$
- Carbone : $C$ graphite
- Oxygène : $O_2(g)$

### Les trois piliers énergétiques

**Enthalpie** : $H = U + PV$

- À pression constante : $\Delta H = Q_{P}$
- Quantifie l'énergie échangée sous forme de chaleur

**Entropie** : $\mathrm{d}S = \delta S_e + \delta S_c$ avec $\delta S_c \geq 0$

- Mesure le désordre du système
- La création d'entropie traduit l'irréversibilité

**Enthalpie libre (Gibbs)** : $G = H - TS$

- $\mathrm{d}G = -T\delta S_c \leq 0$
- Son minimum détermine l'équilibre

## Grandeurs molaires partielles

Les propriétés d'un constituant dans un mélange dépendent de son environnement. Il faut donc définir des grandeurs qui tiennent compte des interactions.

### Définition mathématique

Pour toute grandeur extensive $Z$ :

$$ Z_{m,i} = \left(\frac{\partial Z}{\partial n_i}\right)_{T,P,n_{j\neq i}} $$

**Interprétation physique :** variation de $Z$ quand on ajoute une mole de $i$ au mélange, à $T$, $P$ et composition fixées.

**Propriétés :**

- Grandeur **intensive**
- Unité : celle de $Z$ par mole

### Théorème d'Euler

Le théorème d'Euler traduit l'extensivité : $$ Z = \sum_i n_i Z_{m,i} $$

**Applications :**

- Volume d'un mélange : $V = \sum_i n_i V_{m,i}$
- Enthalpie d'un mélange : $H = \sum_i n_i H_{m,i}$

### Cas particulier du corps pur

Pour un corps pur, la grandeur molaire partielle devient simplement : $$ Z_m^* = \frac{Z}{n} $$

En conditions standard ($P = P° = 1$ bar) : $$ Z_{m,i}°(T) \text{ ne dépend que de } T $$

## Potentiel chimique 

### Définition

Le **potentiel chimique** est l'*enthalpie libre molaire partielle* :

$$ \mu_i = \left(\frac{\partial G}{\partial n_i}\right)_{T,P,n_{j\neq i}} = G_{m,i} $$

C'est la grandeur clé de la thermochimie.

### Expression générale du potentiel chimique

$$ \mu_i(T,P,\text{composition}) = \mu_i°(T) + RT\ln a_i $$

avec :

- $\mu_i°(T)$ : potentiel chimique standard
- $a_i$ : **activité** (sans dimension)

### Table des activités

| État physique              | Cas             | Activité $a_i$                                    |
| -------------------------- | --------------- | ------------------------------------------------- |
| **Gaz pur**                | Gaz parfait     | $\displaystyle\frac{P}{P°}$                       |
| **Gaz dans un mélange**    | Mélange de GP   | $\displaystyle\frac{P_i}{P°}$ où $P_i = x_i P$    |
| **Mélange liquide/solide** | Mélange idéal   | $x_i$ (fraction molaire)                          |
| **Soluté dilué**           | Solution idéale | $\displaystyle\frac{c_i}{c°}$ où $c° = 1$ mol·L⁻¹ |
| **Corps pur condensé**     | -               | $1$                                               |

### Équilibre

**Principe fondamental :** Un système évolue vers les potentiels les plus bas.

**À l'équilibre entre phases :** $\mu_i^{(\alpha)} = \mu_i^{(\beta)}$

**Exemple : diamant vs graphite** (25°C, 1 bar)

- $\mu(C_\text{diamant}) = 2,9$ kJ·mol⁻¹
- $\mu(C_\text{graphite}) = 0,0$ kJ·mol⁻¹

→ Le graphite est stable, le diamant est **métastable** (transformation extrêmement lente)


### Changements d'état

$$
\Delta_\text{vap}G_A = \mu_A(g)-\mu_A(l)
$$

### Différentielle de l'enthalpie libre

$$ \mathrm{d}G = V\mathrm{d}P - S\mathrm{d}T + \sum_i \mu_i \mathrm{d}n_i $$

Cette équation fondamentale relie toutes les variables thermodynamiques.

### Application : la pression osmotique

L'**osmose** est le transfert de solvant à travers une membrane semi-perméable, de la solution diluée vers la solution concentrée.

**Loi de Van't Hoff :** $$ \pi = C_\text{soluté} RT $$

**Applications :**

- Dessalement de l'eau de mer (osmose inverse)
- Phénomènes biologiques (turgescence, plasmolyse)
- Mesure de masses molaires

## Grandeurs de réaction 

### Définition générale

Pour toute grandeur extensive $Z$ :

**Grandeur de réaction :** $$ \Delta_r Z = \left(\frac{\partial Z}{\partial \xi}\right)_{T,P} = \sum_i \nu_i Z_{m,i} $$

**Grandeur standard de réaction :** $$ \Delta_r Z°(T) = \sum_i \nu_i Z_{m,i}°(T) $$

**Propriétés :**

- Grandeur **intensive** (J·mol⁻¹, J·K⁻¹·mol⁻¹, etc.)
- À $(T,P)$ constants : $\mathrm{d}Z = \Delta_r Z \mathrm{d}\xi$

### Approximation d'Ellingham

Dans de nombreux cas, on considère : $$ \Delta_r H°(T) \approx \Delta_r H°(25°C) = \text{Cte} $$ $$ \Delta_r S°(T) \approx \Delta_r S°(25°C) = \text{Cte} $$


## Enthalpie de réaction

### Définition et interprétation

$$ \Delta_r H = \sum_i \nu_i H_{m,i} $$

À $T$ et $P$ constants : $\Delta H_\text{réaction} = \Delta_r H \cdot \Delta\xi = Q_{P}$

|Type|$\Delta_r H°$|Signification|
|---|---|---|
|**Exothermique**|$< 0$|Libère de la chaleur|
|**Endothermique**|$> 0$|Absorbe de la chaleur|
|**Athermique**|$\approx 0$|Pas d'échange thermique|

**Applications pratiques :**

- Chaufferettes chimiques (exothermique)
- Poches de froid instantané (endothermique)
- Cannettes auto-chauffantes

### Loi de Hess 

**Enthalpie de formation** $\Delta_f H°$ : enthalpie de la réaction de formation d'une molécule à partir de ses éléments dans leur ESR.

**Loi de Hess :** $$ \boxed{\Delta_r H° = \sum_i \nu_i \Delta_f H_i°} $$

**Règle importante :** Pour un élément dans son ESR : $\Delta_f H° = 0$

**Exemple :** Pour $\text{NH}_3(g) + \text{HCl}(g) \rightarrow \text{NH}_4\text{Cl}(s)$ $$ \Delta_r H° = \Delta_f H°(\text{NH}_4\text{Cl}) - \Delta_f H°(\text{NH}_3) - \Delta_f H°(\text{HCl}) $$
### Autres méthodes de calcul

**Enthalpies de changement d'état :**

- Fusion, vaporisation, sublimation : **endothermiques** ($\Delta H° > 0$)
- Solidification, liquéfaction, condensation : **exothermiques** ($\Delta H° < 0$)

**Énergies de liaison :**

Pour $\text{A-B}(g) \rightarrow \text{A}(g) + \text{B}(g)$ : $\Delta H° = D_{\text{A-B}} > 0$

$$ \Delta_r H° = \sum D_\text{liaisons rompues} - \sum D_\text{liaisons formées} $$

### Flammes et explosions

**Principe :** Si $Q = 0$ (adiabatique) et $P = \text{Cte}$ (monobare) :

$$ \Delta H = 0 = \Delta H_\text{chim} + \Delta H_\text{échauffement} $$

$$ \xi_\text{fin} \Delta_r H° + \sum_i n_i C_{P,m,i}°(T_f - T_i) = 0 $$

**Méthode :**

1. Équilibrer la réaction et calculer $\Delta_r H°$
2. Tableau d'avancement → trouver $\xi_\text{fin}$ et les $n_i$ finales
3. Trouver $\Delta r H^\circ$
4. $Q = n \times \Delta r H^\circ$
5. $\Delta T = \frac{Q}{\sum_x c_x n_x}$
6. Résoudre pour $T_f$ (température de flamme)

**Applications :**

- Aluminothermie : $2\text{Al}(s) + \text{Fe}_2\text{O}_3(s) \rightarrow 2\text{Fe}(s) + \text{Al}_2\text{O}_3(s)$ ($\Delta_r H° = -851,5$ kJ·mol⁻¹)
- Explosifs militaires
- Flammes de combustion

### Calorimétrie 

**Principe :** Dans un calorimètre, le bilan enthalpique s'écrit : $$ Q_p = 0 = \xi \Delta_r H° + (C_{p,\text{cal}} + C_{p,\text{sol}}) \Delta T $$

La mesure de $\Delta T$ permet de remonter à $\Delta_r H°$.

## Entropie de réaction 

### Définition

$$ \Delta_r S = \sum_i \nu_i S_{m,i} $$

$$ \Delta_r S°(T) = \sum_i \nu_i S_{m,i}°(T) $$

Dans l'approximation d'Ellingham : $\Delta_r S°(T) \approx \Delta_r S°(25°C)$

### Calcul à partir des tables

On utilise directement les entropies molaires standard tabulées : $$ \Delta_r S°(T) = \sum_i \nu_i S_{m,i}°(T) $$

### Prévision du signe de $\Delta_r S°$

Le signe dépend de la création ou non de **désordre** (principalement via les gaz) :

|$\displaystyle\sum \nu_{i,\text{gaz}} > 0$|$\displaystyle\sum \nu_{i,\text{gaz}} < 0$|$\displaystyle\sum \nu_{i,\text{gaz}} = 0$|
|---|---|---|
|Réaction **augmente** le désordre|Réaction **diminue** le désordre|Désordre varie peu|
|$\Delta_r S° > 0$|$\Delta_r S° < 0$|$\Delta_r S° \approx 0$|

**Ordres de grandeur :**

- $S_m°(\text{solide}) \approx 10-100$ J·K⁻¹·mol⁻¹
- $S_m°(\text{liquide}) \approx 50-200$ J·K⁻¹·mol⁻¹
- $S_m°(\text{gaz}) \approx 150-250$ J·K⁻¹·mol⁻¹

## Enthalpie libre de réaction

### Définition et relation fondamentale

$$ \Delta_r G = \sum_i \nu_i \mu_i $$

$$ \Delta_r G°(T) = \sum_i \nu_i \mu_i°(T) $$

Or $G = H - TS$, donc :

$$ \boxed{\Delta_r G°(T) = \Delta_r H° - T\Delta_r S°} $$

Dans l'approximation d'Ellingham :

$$ \Delta_r G°(T) = A + BT $$

avec $A = \Delta_r H°$ et $B = -\Delta_r S°$

### Calcul de $\Delta_r G°(T)$

**Méthode :**

1. Calculer $\Delta_r H°$ avec la loi de Hess
2. Calculer $\Delta_r S°$ avec les tables
3. Appliquer : $\Delta_r G°(T) = \Delta_r H° - T\Delta_r S°$

**Conversions et erreurs**

- $\Delta_r H°$ souvent en kJ·mol⁻¹
- $\Delta_r S°$ en J·K⁻¹·mol⁻¹
- $T$ en K
## Équilibre chimique et évolution spontanée

### Relation de De Donder

En variables $(P, T, \xi)$ : $$ \mathrm{d}G = V\mathrm{d}P - S\mathrm{d}T + \Delta_r G\mathrm{d}\xi $$

Or $\mathrm{d}G = -T\delta S_c \leq 0$, donc :

$$ \boxed{\Delta_r G\mathrm{d}\xi = -T\delta S_c \leq 0} $$

C'est la **relation de De Donder** : elle dicte le sens d'évolution.

### Quotient de réaction $Q_r$

$$ Q_r = \prod_i (a_i)^{\nu_i} $$

sans dimension

**Exemples :**

- $\text{Ag}_3\text{PO}_4(s) \rightleftharpoons 3\text{Ag}^+(aq) + \text{PO}_4^{3-}(aq)$ : $Q_r = [\text{Ag}^+]^3[\text{PO}_4^{3-}]$
- $6\text{Fe}_2\text{O}_3(s) \rightleftharpoons 4\text{Fe}_3\text{O}_4(s) + \text{O}_2(g)$ : $Q_r = \frac{P_{\text{O}_2}}{P°}$
- $\text{N}_2(g) + 3\text{H}_2(g) \rightleftharpoons 2\text{NH}_3(g)$ : $\displaystyle Q_r = \frac{(P_{\text{NH}_3}/P°)^2}{(P_{\text{N}_2}/P°)(P_{\text{H}_2}/P°)^3}$

**Lien avec $\Delta_r G$ :**

$$ \boxed{\Delta_r G = \Delta_r G°(T) + RT\ln Q_r} $$

### Constante d'équilibre $K°(T)$

**Relation de Guldberg et Waage :** $$ K°(T) = Q_{r,\text{éq}} = \prod_i (a_{i,\text{éq}})^{\nu_i} $$

À l'équilibre : $\Delta_r G_\text{éq} = 0$, donc :

$$ \boxed{K°(T) = \exp\left(-\frac{\Delta_r G°(T)}{RT}\right)} $$

ou

$$ \boxed{\Delta_r G°(T) = -RT\ln K°(T)} $$

### Interprétation de $K°$

| $K° \gg 1$                             | $K° \ll 1$                    | $K° \approx 1$                       |
| -------------------------------------- | ----------------------------- | ------------------------------------ |
| Réaction **quantitative** (totale)     | Réaction **très peu avancée** | Réaction **équilibrée**              |
| $\xi_\text{éq} \approx \xi_\text{max}$ | $\xi_\text{éq}$ très faible   | On utilise $K°(T) = Q_{r,\text{éq}}$ |

### Loi de Van't Hoff 

$$ \boxed{\frac{\mathrm{d}(\ln K°(T))}{\mathrm{d}T} = \frac{\Delta_r H°}{RT^2}} $$

**Conséquences :**

|Réaction **endothermique**|Réaction **exothermique**|Réaction **athermique**|
|---|---|---|
|$\Delta_r H° > 0$|$\Delta_r H° < 0$|$\Delta_r H° \approx 0$|
|$K°$ **augmente** si $T$ augmente|$K°$ **diminue** si $T$ augmente|$K°$ **indépendant** de $T$|
|Favorisée à **haute** $T$|Favorisée à **basse** $T$||

**Par intégration :**

$$ \ln\left(\frac{K°(T_2)}{K°(T_1)}\right) = -\frac{\Delta_r H°}{R}\left(\frac{1}{T_2} - \frac{1}{T_1}\right) $$

### Critère d'évolution et d'équilibre

**Expression de $\Delta_r G$ :** $$ \Delta_r G = \Delta_r G°(T) + RT\ln Q_r = RT\ln\left(\frac{Q_r}{K°(T)}\right) $$


Le système évolue toujours vers le minimum de $G$, c'est-à-dire vers l'équilibre.
## Formules

### Relations fondamentales

$$ \boxed{\Delta_r G°(T) = \Delta_r H° - T\Delta_r S°} $$

$$ \boxed{\Delta_r G = \Delta_r G°(T) + RT\ln Q_r = RT\ln\left(\frac{Q_r}{K°(T)}\right)} $$

$$ \boxed{K°(T) = \exp\left(-\frac{\Delta_r G°(T)}{RT}\right) = Q_{r,\text{éq}}} $$

$$ \boxed{\frac{\mathrm{d}(\ln K°(T))}{\mathrm{d}T} = \frac{\Delta_r H°}{RT^2}} $$

### Critère d'évolution et d'équilibre


### Loi de Hess

$$ \boxed{\Delta_r H° = \sum_i \nu_i \Delta_f H_i°} $$

### Définitions des grandeurs

$$ \boxed{\Delta_r Z = \sum_i \nu_i Z_{m,i}} $$

$$ \boxed{\Delta_r Z° = \sum_i \nu_i Z_{m,i}°} $$