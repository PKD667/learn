L'**équation de Nernst** donne le [[potentiel redox]] d'un couple en fonction des concentrations.

## Forme générale

Pour le couple $\text{Ox} + ne^- \rightleftharpoons \text{Red}$ :

$$E = E° + \frac{RT}{nF}\ln\left(\frac{\prod a_{\text{Ox}}^{\nu}}{\prod a_{\text{Red}}^{\nu}}\right)$$

- $E°$ : potentiel standard (V)
- $R = 8.314$ J·K⁻¹·mol⁻¹
- $T$ : température (K)
- $n$ : nombre d'électrons échangés
- $F = 96500$ C·mol⁻¹ (constante de Faraday)
- $a$ : [[activité]]

## Forme pratique (25°C)

$$E = E° + \frac{0.059}{n}\log\left(\frac{\prod a_{\text{Ox}}^{\nu}}{\prod a_{\text{Red}}^{\nu}}\right)$$

## Constante d'équilibre

À l'équilibre, les potentiels des deux couples sont égaux :
$$E_1 = E_2$$

Ce qui donne :
$$K° = 10^{\frac{n(E_1° - E_2°)}{0.059}}$$

## Exemples d'application

### Couple simple $\text{Cu}^{2+}/\text{Cu}$

$$E = E° + \frac{0.059}{2}\log[\text{Cu}^{2+}]$$

(le solide a une activité de 1)

### Couple avec H⁺ : $\text{MnO}_4^-/\text{Mn}^{2+}$

$\text{MnO}_4^- + 8\text{H}^+ + 5e^- \rightleftharpoons \text{Mn}^{2+} + 4\text{H}_2\text{O}$

$$E = E° + \frac{0.059}{5}\log\frac{[\text{MnO}_4^-][\text{H}^+]^8}{[\text{Mn}^{2+}]}$$

>[!example] Calcul de K° pour la pile Daniell
> $\text{Zn} + \text{Cu}^{2+} \rightleftharpoons \text{Zn}^{2+} + \text{Cu}$
> 
> $E°(\text{Cu}^{2+}/\text{Cu}) = +0.34$ V
> $E°(\text{Zn}^{2+}/\text{Zn}) = -0.76$ V
> 
> $$K° = 10^{\frac{2(0.34-(-0.76))}{0.059}} = 10^{37}$$
> 
> Réaction quasi-totale.

## Voir aussi

- [[potentiel redox]]
- [[oxydoréduction]]
- [[pile électrochimique]]
- [[constante d'équilibre]]
