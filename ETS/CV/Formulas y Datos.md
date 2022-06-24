## Identidades Trigonometricas
![[identidades_trigonometricas.png]]
***
## Ángulos Notables

![[angulos_notables.png]]
***

## Ecuación vectorial de una recta
![[vectores_de_una_recta.png]]
***Ecuación vectorial de la recta:***
$\langle x,y,x\rangle=\langle x_0,y_0,z_0\rangle+t\langle a,b,c\rangle\to\langle x,y,x\rangle=\langle x_0+ta,y_0+tb,z_0+tc\rangle$
***Parametrización:***
$\langle x,y,x\rangle=\langle x_0+ta,y_0+tb,z_0+tc\rangle$
$x=x_0+ta$,    $y=y_0+tb$,    $z=z_0+tc$
***
## Integrales dobles
***Rectangulares:***
$$
\iint_R{f(x,y)dA}=\int_a^b{\int_c^d{f(x,y)dydx}}
$$
$c\leq y\leq d$,    $a\leq x\leq b$
***Polares:***
$$
\iint_R{f(rcos\theta,rsen\theta)dA}=\int_a^b{\int_c^d{f(rcos\theta,rsen\theta)rdrd\theta}}
$$
$c\leq r\leq d$,    $a\leq\theta\leq b$,    $x=rcos\theta$
$y=rsen\theta$,    $x^2+y^2=r^2$
***
## Integrales Triples
***Rectangulares:***
$$
\iiint_R{f(x,y,z)dV}=\int_a^b\int_c^d\int_e^f{f(x,y,z)dzdydx}
$$
$e\leq z\leq f$,    $c\leq y\leq d$,    $a \leq x\leq b$
***Cilindricas:***
$$
V=\iiint_R{f(r,\theta,z)dV}=\int_a^b\int_c^d\int_e^f{f(r,\theta,z)drd\theta dz}
$$
$e\leq z\leq f$,    $c\leq \theta\leq d$,    $a \leq r\leq b$
$x=rcos\theta$ ,    $y=rsen\theta$,    z=z$
$r^2=x^2+y^2$,    $tan\theta=\frac{y}{x}$,   $z=z$
***Esfericas:***
$$
\iint_R{f(\rho,\phi,\theta)dV}=\int_a^b\int_c^d\int_e^f{f(\rho,\phi,\theta)\rho^2sen\phi d\rho d\phi d\theta}
$$
$e\leq\rho\leq f$,    $c\leq\phi\leq d$,    $a \leq\theta\leq b$
$\rho^2=x^2+y^2+z^2$,    $tan\theta=\frac{y}{x}$,    $cos\phi=\frac{1}{\sqrt{x^2+y^2+z^2}}$
***
## Integrales de linea
***Respecto a $x$:***
$$
\int_C{f(x,y)dx=\lim_{|P|\to0}{\sum_{k=i}^{n}f(x_k^*,y_k^*)\Delta x_k}}=\int_a^b{f(x(t),y(t))x'(t)dt}
$$
***Respecto a $y$:***
$$
\int_C{f(x,y)dy=\lim_{|P|\to0}{\sum_{k=i}^{n}f(x_k^*,y_k^*)\Delta y_k}}=\int_a^b{f(x(t),y(t))y'(t)dt}
$$

***Respecto a la longitud de arco $s$:***
$$
\int_C{f(x,y)ds=\lim_{|P|\to0}{\sum_{k=i}^{n}f(x_k^*,y_k^*)\Delta s_k}}=\int_a^b{f(x(t),y(t))\sqrt{[x'(t)]^2+[y'(t)]^2}dt}
$$
