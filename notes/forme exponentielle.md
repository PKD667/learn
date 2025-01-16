#### Définition :
Pour tout $\theta$ de $\mathbb R$, on note $e^{i\theta}$ le nombre complexe de [[module]] 1 défini par :$$e^{i\theta}=\cos(\theta)+i\sin(\theta)$$ On a donc :$$Re(e^{i\theta})=\cos(\theta),\quad Im(e^{i\theta})=\sin(\theta)\quad\text{et}\quad |e^{i\theta}|=1$$Soit $r\in\mathbb R$ et $\theta$ un angle, il existe un $z\in\mathbb C$ tel que :$$z=re^{i\theta}$$
#### Propriétés :
##### Formule d'Euler :
Pour tout $\theta\in\mathbb R$,$$\cos(\theta)=\frac{e^{i\theta}+e^{-i\theta}}{2}\quad\text{et}\quad\sin(\theta)=\frac{e^{i\theta}-e^{-i\theta}}{2i}$$
###### Démonstration :
Soit $\theta\in\mathbb R\mod(2\pi)$:

$$
e^{i\theta}+e^{-i\theta}=\cos(\theta)+i\sin(\theta)+\cos(-\theta)+i\sin(-\theta) =\cos(\theta)+i\sin(\theta)+cos(\theta)-i\sin(\theta)=2\cos(\theta)
\iff\cos(\theta)=\frac{e^{i\theta}+e^{-i\theta}}{2}
$$ On a également : 
$$
e^{i\theta}-e^{-i\theta}=\cos(\theta)+i\sin(\theta)-\cos(-\theta)-i\sin(-\theta) =\cos(\theta)+i\sin(\theta)-cos(\theta)+i\sin(\theta)=2i\sin(\theta)\iff\sin(\theta)=\frac{e^{i\theta}-e^{-i\theta}}{2i}
$$
##### addition d'exponentielles complexes

Soient $(a,b)\in\mathbb R^2$ :
$$
e^{ia}+e^{ib}=e^{i(\frac{a+b}{2})}\Big(e^{i(\frac{a-b}{2})}+e^{-i(\frac{a-b}{2})}\Big
)$$ 

