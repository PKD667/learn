La mécaniques des fluides met en relation les phénomènes microscopiques avec les relations macro de mouvement des fluides. 

Voir [[Phénomène de transport]]

# Particule de fluide

## Échelle mésoscopique

Comme en Thermodynamique, on va définir une échelle supérieure aux particules mais inférieure à l'échelle macroscopique.

On ne peut se contenter d'étudier le centre de masse des objets.

On considère un système de masse constante, qui peut être ouvert, mais ou les flux de masse se compensent. 

## Forces volumiques

On se place dans un référentiel supposé galliléen muni d'un repère cartésien et une horloge. 

Le système considéré correspond à l'ensemble des particules et on pose 
 - $\mathrm{d}\tau$ son volume
 - $\mathrm{d} m$ sa masse
$$
\mathrm d m = \rho \ \mathrm d z
$$
avec 
$$
M_\text{macro} = {\int \int \int}_V \ \mathrm d m = {\int \int \int}_V \ \rho \ \mathrm d z
$$
Si une force extérieure est appliquée au fluide, on en définit l'équivalent volumique 
$$
\mathrm d \vec F = \vec f \ \mathrm d \tau
$$
et 
$$
\vec F = {\int \int \int}_V \ \mathrm d \vec F = {\int \int \int}_V \ \vec f \ \mathrm d \tau
$$
> [!Example]
> On peut prendre l'exemple de la pesanteur $\vec P = M \vec g$
> $$ \mathrm d \vec P = \mathrm d m\ \vec g = \rho \vec g \ \mathrm d \tau$$
> et
> $$\vec P = {\int \int \int}_V \ \rho \vec g \ \mathrm d \tau = \vec g {\int \int \int}_V \ \rho \ \mathrm d \tau$$
>  - car $\vec e_z$ est constant

On en retient que la force volumique qui découle du poids s'exprime 
$$
\vec f_\text{poids} = \rho \vec g 
$$
en $\text{N.m}^{-3}$ 

## Forces surfaciques

Les forces surfaciques repéresentent les interactions de contact avec le reste du fluide, ou avec d'autres systèmes.

On note $\mathrm d \vec S$ orientée vers la normale sortante. 

On peut noter la **force de contact**
$$
\mathrm d \vec F_\text{contact} = \vec C \mathrm \ \mathrm d \vec S
$$
 - Avec $\vec C$ une contrainte exrpimée en unité de force par surface

Dans le cas d'un fluide non-visqueux 
$$
\mathrm d \vec F_\text{contact} =  P \mathrm \ \mathrm d \vec S
$$
 - Avec $P$ la pression en pascal

#### Équivalent volumique

$$
\mathrm d \tau = \mathrm d x \ \mathrm d y \ \mathrm d z
$$

On peut faire un système de faces pour correspondre à une volume infinitésimal parralelepipédique
$$
\begin{cases}
\mathrm d \vec S_z = \mathrm d x \ \mathrm d y \ \vec e_z \\
\mathrm d \vec S_y = \mathrm d x \ \mathrm d z \ \vec e_y \\
\mathrm d \vec S_x = \mathrm d z \ \mathrm d y \ \vec e_x \\
\mathrm d \vec S_z' = -\mathrm d x \ \mathrm d y \ \vec e_z \\
\mathrm d \vec S_y' = -\mathrm d x \ \mathrm d z \ \vec e_y \\
\mathrm d \vec S_x' = -\mathrm d z \ \mathrm d y \ \vec e_x \\
\end{cases}
$$
De même pour les forces 
$$
\begin{cases}
\mathrm d \vec F_{z,\text{press}} = -P(x,y,z+\mathrm dz)\ \mathrm d x \ \mathrm d y \ \vec e_z \\
\mathrm d \vec F_{y,\text{press}} = -P(x,y+\mathrm dy,z)\ \mathrm d x \ \mathrm d z \ \vec e_y \\
\mathrm d \vec F_{x,\text{press}} = -P(x+\mathrm dx,y+\mathrm dy,z)\ \mathrm d y \ \mathrm d z \ \vec e_x \\
...
\end{cases}
$$

On peut faire un bilan par axe (par exemple $\vec e_z$)
$$
\begin{align*}
&\mathrm d \vec F_{z,\text{press}} + \mathrm d \vec F_{z,\text{press}}' \\
&= \mathrm d x \ \mathrm d y \ \vec e_z(P(x,y,z)-P(x,y,z+\mathrm dz)) \\
&\approx - \mathrm d x \ \mathrm d y \ \vec e_z \frac{\partial P}{\partial z}(x,y,z)
\end{align*}
$$
On peut généraliser en 
$$
\mathrm d \vec F_\text{press} = - \vec \nabla P\ \mathrm d \tau
$$
## Équilibre hydrostatique

On considére un volume $V$ de fluide dans une référentiel galliléen, soumis à la pesanteur et avec une force de pression sur son bord ($\partial V$). 

A l'équillibre:
$$
\vec F_\text{poids}+\vec F_\text{press} = \vec 0
$$
ainsi
$$
{\int \int \int}_V \ \rho \vec g \ \mathrm d \tau  = 
{\oint\oint}_{\partial V} \ P\ \mathrm d\vec S
$$
> [! Définition]
> On peut donc définir le principe fondamentale de l'hydrostatique
> $$
> \vec \nabla P = \rho \vec g 
> $$



