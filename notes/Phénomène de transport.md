### Courant électrique

$$
I = \frac{\mathrm{d}Q}{\mathrm{d}t} = \int \int_S ~\overrightarrow{j} \cdot \mathrm{d}S = \int \int_S ~\overrightarrow{j} \cdot \overrightarrow{n~}  \mathrm{d}S = \overrightarrow{j} \cdot \overrightarrow{n~} \int \int_S \mathrm{d}S
$$
 - $I$ en Ampères (ou Coulombs/Secondes)
 - $||\overrightarrow{j}||$ en $\text{C}\cdot\text{s}^{-1}\cdot\text{m}^{-2}$
 - $\overrightarrow{n}$ la normale à la surface

Ainsi, on arrive à exprimer l'intensité, c'est à dire l'ensemble du courant qui traverse la surface en fonction des différentes charges en chaque point de la surface. 

On peut aussi l'exprimer en fonction de la vitesse et de la densité d'electrons.

$$
\mathrm{d}Q = -|e|\mathrm{d}N_e = -|e|n_e \times \int \overrightarrow{n} \cdot \overrightarrow{v_e} ~\mathrm{d}t
$$
 - Avec $-|e|n_e$ qui correspond à la *densité* de charge d'electrons.

$$
\overrightarrow{j_e} = -|e|n_e\times \overrightarrow{v_e}
$$

On peut appliquer la même méthode pour calculer des flux de particules. 

### Transfert thermique

$$
\phi_{\text{th}} = \int \int ~\overrightarrow{j}_\text{th} \cdot \mathrm{d}\overrightarrow{S}
$$

Il existe plusieurs types de phénomènes de transport:
 - Radiatif
 - Convectif
 - Diffusif

## Transport diffusif

On définit des lois phénoménologique pour le phénomène de diffusion.

### Modèle de Drüde

On suppose le métal composé d'un réseau cristallin de cations et d'un nuage d'électrons mobiles définit par ($m_e, q_e = -|e|, n_e$). Le courant électrique décrit donc la réponse des électrons à un champ électrique extérieur. On considère un électrons moyen qui modélise le mouvement du nuage. Cet électron est soumis à $\vec{E}$ qui lui applique une force (force de Lorentz)
$$
\vec{F_L} = -|e|\vec{E}
$$
Il est aussi soumis par une force de *frottement fluide* lié aux chocs avec le réseau cationique
$$
\vec{F_f} = -\lambda\vec{v_e}
$$
On applique le principe fondamental de la dynamique à ce système:
$$
m_e\times \frac{\mathrm{d}\vec{v_e}}{\mathrm{d}t} = -|e|\vec{E} - \lambda\vec{v_e}
$$
En **régime stationnaire** on considère que $\frac{\mathrm{d}\vec{v_e}}{\mathrm{d}t} = \vec{0}$ donc
$$
\vec{v_e} = \frac{-|e|}{\lambda}\vec{E} 
$$
Ainsi avec $\vec{j_e} = -|e|n_e\times \vec{v_e}$ on a
$$
\vec{j_e} = \frac{|e|^2n_e}{\lambda}\vec{E}
$$
 - $\frac{|e|^2n_e}{\lambda} = \sigma$

On peut donc dériver la loi d'Ohm à partir d'un modèle mécanique de l'électron.
### Loi d'Ohm locale

On considère un conducteur, avec des charges mobiles soumises à un champ électrique $\overrightarrow{E}$. On note $\sigma$ la conductivité du milieu.

$$
\overrightarrow{j_e} = \sigma \overrightarrow{E} = -\sigma \times \overrightarrow{\text{grad}}~V
$$
On utilise le [[gradient]].

On étudie l'application d'un champ électrique sur un cylindre métallique.

$$
{\vec{E} = \frac{-\mathrm{d}V}{\mathrm{d}x}\vec{e_x}}
$$
$$
||\vec{j_e}|| = \frac{I}{S} = \sigma E \implies E = \frac{I}{S\sigma}
$$
Le champ étant homogène, on peut intégrer :
$$
-\int_0^x \frac{\mathrm{d}V}{\mathrm{d}x'}\mathrm{d}x' = -V(x) + V(0) = \int_0^x E\mathrm{d}x' = Ex
$$
De plus 
$$
||\vec{j_e}|| = \frac{I}{S} = \sigma E \implies E = \frac{I}{S\sigma}
$$
Ainsi on a
$$
V(x) = V(0) - Ex 
$$
et avec $\Delta V = V(L) - V(0)$
$$
\Delta V = -RI \implies R = \frac{L}{S\sigma}
$$

### Loi de Ficke pour la diffusion de particules

On suppose un ensemble de particules de densité inhomogène $n(\vec{r},t)$ plongé dans un substrat immobile. On à donc 
$$
\vec{j} = -D~\overrightarrow{\text{grad}}~n
$$
 - $D$ un coefficient de diffusion
 - $\overrightarrow{\text{grad}}~n$ le gradient de densité en particules

On peut le résumer en disant que les particules vont de diffuser vers les endroits ou il n'y à pas de particules.

### Loi de fourrier

On suppose un système qu'on peut décrire avec une *étude thermodynamique locale* on à alors la **loi de Fourrier**:
$$
\vec{j_\text{th}} = -\lambda~\overrightarrow{\text{grad}}~T
$$
 - $\vec{j_\text{th}}$ en $\text{J}.\text{m}^{-2}.\text{s}^{-1}$ 
 - $\lambda$ le coefficient de conductivité thermique en $\text{W}.\text{m}^{-1}.\text{K}^{-1}$
 - $T$ en $\text{K}$


## Equations de diffusion

### Bilan de particule

On considère un canal unidirectional de section $S$ ou se développe un courant diffusif $\vec{j}$ selon $\vec{u_x}$. Le canal contient un fluide de densité $n(\vec{r},t)$.

 - On suppose le problème unidirectionnel 
 $$
 \displaystyle\vec{j} = j(x,t) \vec{u_x}
 $$
 $$
 n = n(x,t)
 $$
 
 - On fait un bilan de particules sur un volume $\mathrm{d}V = \mathrm{d}x\times S$ entre $x$ et $x + \mathrm{d}x$ entre les instants $t$ et $t+\mathrm{d}t$ 

$$
\mathrm{d}N(x,t) = n(x',t) S \mathrm{d}x
$$
$$
\mathrm{d}N(x,t+\mathrm{d}t) = n(x',t+\mathrm{d}t) S \mathrm{d}x
$$
 - Avec $S$ la **section transversale du canal** 
Ainsi
$$
\delta N = \mathrm{d}N(x,t+\mathrm{d}t) - \mathrm{d}N(x,t) = S \mathrm{d}x \Big( n(x',t+\mathrm{d}t) - n(x',t)\Big)
$$

On fait un développement limité:
$$
\delta N \approx S \mathrm{d}x \times \frac{\partial n}{\partial t}(x',t) \mathrm{d}t
$$

De plus, on peut poser le flux entrant dans le volume $\mathrm{d}V$ en $x$ entre $t$ et $t + \mathrm{d}t$ :
$$
\phi_\text{in} = -\vec{j}(x,t) \cdot \vec{n}_\text{ext}(x) S
$$
Le flux sortant entre $x$ et $x+\mathrm{d}x$ et $t + \mathrm{d}t$ :
$$
\phi_\text{in} = \vec{j}(x,t) \cdot \vec{n}_\text{ext}(x+\mathrm{d}x) S
$$

On peut calculer un bilan de flux $\delta \phi$ :
$$
\begin{align*}
\delta phi &= \phi_\text{entrant} - \phi_\text{sortant}\\
           &= -j(x,t)\vec{u_x}\cdot (-\vec{u_x}) \times S - j(x+\mathrm{d}x,t')\vec{u_x}\cdot \vec{u_x} \times S \\
           &=-S(j(x+\mathrm{dx},t') - j(x,t')) \\
           &\approx -S \frac{\partial j}{\partial x}(x,t')dx
\end{align*}
$$

Or on peut établir la relation
$$
\delta N = \delta \phi dt
$$

ce qui implique
$$
S \mathrm{d}x \times \frac{\partial n}{\partial t}(x',t) \mathrm{d}t=-S \frac{\partial j}{\partial x}(x,t')dx 
$$
et
$$
\frac{\partial n}{\partial t}(x',t) = -\frac{\partial j}{\partial x}(x,t')
$$

#### Applications phénoménologiques

D'après la loi de Fick on à:
$$
\vec{j} = -D~\vec{\nabla}n
$$
Ce qui nous donne en application:
$$
j(x,t) = \vec{j}\cdot \vec{u_x} = - D \frac{\partial n}{\partial x}(x,t)
$$
Ainsi
$$
\frac{\partial n}{\partial t}(x',t) = D\frac{\partial^2 n}{\partial x^2}(x,t')
$$
##### En 1D
$$
\frac{\partial n}{\partial t} = D\frac{\partial^2n}{\partial x^2}
$$
##### En 3D
$$
\frac{\partial n}{\partial t} = D \Delta n
$$

> $\Delta n$ étant le laplacien défini en 3 dimensions comme $\displaystyle\frac{\partial^2n}{\partial x^2} + \frac{\partial^2n}{\partial y^2} + \frac{\partial^2n}{\partial z^2}$. Il correspond a la divergence du gradient.

 - $x' = x + \alpha \mathrm{d}x$ 
 - $t + \beta \mathrm{d}t$ 

$$
\frac{\partial n}{\partial t}(x',t) = \frac{\partial n}{\partial t}(x+\alpha \mathrm{d}x,t) \approx \frac{\partial n}{\partial t}(x,t) + \frac{\partial^2 n}{\partial x\partial t}(x,t)\alpha \mathrm{d}x
$$
$$
\frac{\partial^2 n}{\partial x^2}(x,t') = \frac{\partial^2 n}{\partial x^2}(x,t + \beta \mathrm{d}t) \approx \frac{\partial^2 n}{\partial x^2}(x,t) + \frac{\partial^3 n}{\partial x^2\partial t}(x,t)\beta \mathrm{d}t
$$

Donc 
$$
\frac{\partial n}{\partial t}(x',t) = D\frac{\partial^2n}{\partial x^2}(x,t')
$$
On développe limité
$$
\frac{\partial n}{\partial t}(x,t) + \frac{\partial^2 n}{\partial t \partial x}(x,t) \alpha \mathrm{d}x = D \frac{\partial^2 n}{\partial x^2}(x,t) + D \frac{\partial^3 n}{\partial x^2\partial t}(x,t)\beta \mathrm{d}t
$$

### Résolution

Pour résoudre l'équation de diffusion
$$
\frac{\partial n}{\partial t} = D\Delta n
$$
On à besoin de:
 - Conditions initiales valeurs pour $t=0$
 - Condition aux bords ($\vec{r} = \vec{R}$)

Les conditions aux bords correspondent à des valeurs fixées de densité. Des contraintes imposées localement. Elle peuvent porter sur $n(\vec{r},t)$ ou sur $\nabla n$. 

> L'équation de diffusion est une équation différentielles aux dérivées partielles (PDE), ses solutions sont inconnues, et très recherchées. On peut résoudre facilement uniquement des cas simplifiés.

#### Cas stationnaire

$\Delta n = 0$

##### Concentration imposée (Dirichlet)

On a un canal  de longueur $L$ orienté par $\vec{u_x}$ qui relie deux réservoirs avec des densités fixées $n_0$ et $n_1$.
 - $\displaystyle\Delta n = 0 \iff \frac{\partial^2n}{\partial x^2} = 0$

On à dont une solution générique
$$
n = Ax + B
$$
 - $n(x=0) = n_0$
 - $n(x=L) = n_1$

Donc 
$$
 n = (\frac{n_1 - n_0}{L})x + n_0
$$
Pour le courant défini par 
$$
\vec{j} = -D\nabla n = -D \frac{\partial n}{\partial x}\times \vec{u_x}
$$
On à:
$$
\vec{j} = -D\nabla n = -D \frac{n_1-n_0}{L}\times \vec{u_x}
$$

##### Flux imposé (Neumann)

on impose des conditions limite de flux sur les extrémités du canal.


$$\phi_0 = \int \int \vec{j} \cdot \mathrm{d}S$$
$$\Delta n = 0 \iff \frac{\partial j}{\partial x} = 0 \implies j = \frac{\phi_0}{S} = -D\frac{\partial n}{\partial x}$$
$$
n = \frac{\phi_0}{DS}x + C, ~~c = n_0
$$
$$
n = n_0 - \frac{\phi_0}{DS}x
$$