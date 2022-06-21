# Clasificación de las ecuaciones diferenciales

## Qué es una ecuación diferencial?

Es una ecuación que relaciona una función, sus derivadas y sus variables.
**Función**
$f(x)$,  $y$, $f(t)$, $y(t)$
**Derivadas**
$f'(x)$,  $y'$,  $\frac{dy}{dx}$,  $y''$,  $\frac{dy}{dt}$
**Variables**
$x$, $t$
**Ecuación diferencial**
$f'(x)+2f(x)+x$, $\frac{dy}{dx}=2y+x$, $xy''-5y'+3=0$, $y''=y'-2y'''$
**Definición de ED:**
$$
F(x, y, y', y'', ..., y^{(n)})=0
$$
>Resolver una ecuación diferencial, significa encontrar la función o funciones que satisfacen la igualdad.

**Ejemplo:**
$y'-2x=0$
$y=x^2\to y'=2x\therefore2x-2x=0$
$y=x^2 \to y'=2x \therefore 2x-2x=0$
$\therefore y=x^2+C \gets Solución\space general$

## Qué es una EDO?

EDO significa ***Ecuación Diferencial Ordinaria***, esta es una ecuación diferencial de funciones con una variable.
**Ejemplo:**
$$
y'-2x=0,\space y
$$
Estas pueden ser aplicadas como un sistema de ecuaciónes diferenciales, es decir, un conjunto de ecuaciones diferenciales de una variable.
**Ejemplo:**
$$
\begin{cases}
    3x'+2y+y'=t \\
    2x-x'+3y'=1
\end{cases}
$$

## Qué es una EDP?

EDP significa ***Ecuación de derivadas parciales***, estas son ecuaciones de funciones de variables.
***Ejemplo***
$u(x, t)=x^2+2t$
$\frac{\partial u}{\partial x}=2x\space\space\frac{\partial u}{\partial t}=2$
$\frac{\partial u}{\partial y}=C\frac{\partial^2u}{\partial x^2}$
$u_t=cu_{xx}$
