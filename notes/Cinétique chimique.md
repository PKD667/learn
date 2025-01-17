La **cinétique chimique** étudie la **vitesse** des réactions chimiques. Ainsi, elle est complémentaire à la [[Thermodynamique chimique]] qui elle étudie le **sens** et l'**état** des réactions. 

>[!conditions] 
>Pour l'analyse cinétique, on considère que toutes les réactions sont **thermodynamiquement favorable**.

### Objectifs

La **cinétique** va permettre de mieux comprendre les réactions chimiques et de déterminer les **conditions** optimales pour leur réalisation.

>[!cadre] 
>On va étudier des *systèmes fermés*, de *volume constant* et à *température constante*.
>On va aussi supposer que les milieux réactionnels sont **homogènes** c'est à dire en pratique *parfaitement agités*.
>


### Définition des vitesses

On prends $\nu_i$ le [[coefficient stœchiométrique algébrique]]. 

#### Apparition

La vitesse d'apparition d'un produit correspond à la [dérivée](dérivation) de sa quantité de matière dans le système chimique en fonction du temps. 
$$
v_{\text{app},i} = \frac{dn_i}{dt} = \nu_i\frac{d\xi}{dt}
$$

#### Disparition

La vitesse de disparition correspond donc à la [dérivée](dérivation) de la quantité de matière d'un produit en fonction du temps.
$$
v_{\text{disp},i} = \frac{dn_i}{dt} = |\nu_i| \frac{d\xi}{dt}
$$

#### Vitesse d'une réaction

La **vitesse d'une réaction** permet d'étudier de manière unique une réaction sans considérer les coefficients relatifs à chaque espèce. Elle est définie par la la [dérivée](dérivation) de l'avancement molaire en fonction du temps.
$$
v = \frac{d\xi}{dt} = \frac{1}{\nu_i}\times \frac{dn_i}{dt}
$$
De plus, puisque les quantités de matière sont dépendantes du volume, on va étudier la variation de la concentration ($\frac{\text{mol}}{L\times s}$). Elle est **nécessairement positive**.
$$
v = \frac{1}{v_i} \times \frac{d[A_i]}{dt}
$$

### Facteurs cinétiques

Pour déterminer la **cinétique** d'une réaction, on va se baser sur plusieurs facteurs :
 - la **concentration** des réactifs
 - la **température** du milieu
 - la **pression** (*espèces gazeuses*)
 - les potentiels **catalyseurs**

#### Concentration

Une réaction admet un **ordre** si on peu écrire une *loi de vitesse* 