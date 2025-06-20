# CAPITULO 1 - SISTEMAS DE ECUACIONES LINEALES

## PROBLEMAS VARIOS

1.60. Considérese dos ecuaciones lineales generales con dos incógnitas $x$ e $y$ sobre el cuerpo real $R$:

$$
\begin{align*}
ax + by & = e \\
cx + dy & = f \\
\end{align*}
$$

Demostrar que:

i. si $\frac{a}{c} \neq \frac{b}{d}$, es decir, si $ad - bc \neq = 0$, entonces el sistema tiene la solución única $x = \frac{de - bf}{ad - bc}$, $y = \frac{af - ce}{ad - bc}$.

ii. si $\frac{a}{c} = \frac{b}{d} \neq \frac{e}{f}$, entonces el sistema no tiene solución.

iii. si $\frac{a}{c} = \frac{b}{d} = \frac{e}{f}$, entonces el sistema tiene más de una solución.

Reduciendo a forma escalonada:

$
-cL_1 + aL_2 \rightarrow L_2 \Rightarrow
\begin{cases}
ax & + &         by & = &       e \\
   &   & (ad - bc)y & = & af - ce \\
\end{cases}
$

i. Si $ad - bc \neq 0$:

$
\frac{1}{ad - bc}L_2 \rightarrow L_2 \Rightarrow
\begin{cases}
ax & + & by & = &                       e \\
   &   &  y & = & \frac{af - ce}{ad - bc} \\
\end{cases}
$

$
-bL_2 + L_1 \rightarrow L_1 \Rightarrow
\begin{cases}
ax & = & a\frac{de - bf}{ad - bc} \\
 y & = &  \frac{af - ce}{ad - bc} \\
\end{cases}
$

$
\frac{1}{a}L_1 \rightarrow L_1 \Rightarrow
\begin{cases}
x & = & \frac{de - bf}{ad - bc} \\
y & = & \frac{af - ce}{ad - bc} \\
\end{cases}
$

ii. Si $\frac{a}{c} = \frac{b}{d} \neq \frac{e}{f}$:

$
\begin{aligned}
ad - bc &    = 0 \\
af - ce & \neq 0 \\
\end{aligned}
\Rightarrow
\begin{cases}
ax & + & by & = &       e &        \\
   &   &  0 & = & af - ce & \neq 0 \\
\end{cases}
$ (El sistema no tiene solución)

iii. Si $\frac{a}{c} = \frac{b}{d} = \frac{e}{f}$:

$
\begin{aligned}
ad - bc & = 0 \\
af - ce & = 0 \\
\end{aligned}
\Rightarrow
\begin{cases}
ax & + & by & = & e \\
   &   &  0 & = & 0 \\
\end{cases}
$ (El sistema tiene más de una solución)

---
