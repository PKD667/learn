
La **dérivée** d'une fonction $f$ représente son taux de variation sur un intervalle h dont on fait la [[limite]] en $0$.
$$
f'(a)=lim_{h\rightarrow 0}\frac{f(a+h)-f(a)}{h}
$$
>[!dérivabilité] On dit qu'une fonction $f(x$ ) est dérivable en $a$ si et seulement si : $\lim_{x\rightarrow a}f(x)=f(a)$
### Dérivées usuelles

#### $f(x)=x \Rightarrow f'(x)=1$ 
$$
f'(x)=lim_{h\rightarrow 0}\frac{(x+h)-x}{h}=lim_{h\rightarrow 0}\frac{h}{h}=lim_{h\rightarrow 0}1=1
$$
#### $f(x)=ax \Rightarrow f'(x)=a$
$$
\begin{align}
f'(ax) &= lim_{h\rightarrow 0}\frac{a(x+h)-ax}{h} \\
       &=lim_{h\rightarrow 0}\frac{ax+ah-ax}{h} \\
       &=lim_{h\rightarrow 0}\frac{ah}{h} \\
       &=lim_{h\rightarrow 0}a=a
\end{align}
$$

	
#### $f(x)=x^n \Rightarrow f'(x)=nx^{n-1}$ 
$$
f'(x^n)=lim_{h\rightarrow 0}\frac{(x+h)^n-x^n}{h}
$$
#### $f(x)=e^x \Rightarrow f'(x)=e^x$ 

$$
\begin{align}
f'(e^x) &= lim_{h\rightarrow 0}\frac{(e^{x+h})-e^x}{h} \\
	    &= lim_{h\rightarrow 0}\frac{e^x\cdot e^h-e^x}{h} \\
	    &= lim_{h\rightarrow 0}\frac{e^x(e^h-1)}{h} \\
	    &= e^x\cdot lim_{h\rightarrow 0}\frac{e^h-1}{h} \\
	    &= e^x\cdot 1=e^x	\\
\end{align}
$$

