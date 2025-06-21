# CAPITULO 1 - SISTEMAS DE ECUACIONES LINEALES

## SISTEMAS HOMOGÉNEOS

1.53. Hallar la dimensión y una base para la solución general $W$ de cada uno de los sistemas siguientes:

a. $
\begin{cases}
 x & + & 3y  & + & 2z  & - & s & - &  t & = & 0 \\
2x & + & 6y  & + & 5z  & + & s & - &  t & = & 0 \\
5x & + & 15y & + & 12z & + & s & - & 3t & = & 0 \\
\end{cases}
$

$
\begin{aligned}
-2L_1 + L_2 & \rightarrow L_2 \\
-5L_1 + L_3 & \rightarrow L_3
\end{aligned}
\Rightarrow
\begin{cases}
 x & + & 3y  & + & 2z  & - &  s & - &  t & = & 0 \\
   &   &     &   &  z  & + & 3s & + &  t & = & 0 \\
   &   &     &   & 2z  & + & 6s & + & 2t & = & 0 \\
\end{cases}
$

$
-2L_2 + L_3 \rightarrow L_3 \Rightarrow
\begin{cases}
 x & + & 3y  & + & 2z  & - &  s & - &  t & = & 0 \\
   &   &     &   & z   & + & 3s & + &  t & = & 0 \\
   &   &     &   &     &   &    &   &  0 & = & 0 \\
\end{cases}
$

Variables libres: $y, s, t$. Por lo tanto $\dim W = 3$.

$
\begin{aligned}
y = 1 \\
s = 0 \\
t = 0 \\
\end{aligned}
\Rightarrow
\begin{cases}
 x & + & 3(1) & + & 2z & - &    0 & - &  0 & = & 0 \\
   &   &      &   &  z & + & 3(0) & + &  0 & = & 0 \\
\end{cases}
\Rightarrow
\begin{cases}
 x & + & 2z & = & -3 \\
   &   &  z & = &  0 \\
\end{cases}
$

$
-2L_2 + L_1 \rightarrow L_1
\Rightarrow
\begin{cases}
x & = & -3 \\
z & = &  0 \\
\end{cases}
$

$
\Rightarrow u_1 = (-3, 1, 0, 0, 0)
$

$
\begin{aligned}
y = 0 \\
s = 1 \\
t = 0 \\
\end{aligned}
\Rightarrow
\begin{cases}
 x & + & 3(0) & + & 2z & - &    1 & - &  0 & = & 0 \\
   &   &      &   &  z & + & 3(1) & + &  0 & = & 0 \\
\end{cases}
\Rightarrow
\begin{cases}
 x & + & 2z & = &  1 \\
   &   &  z & = & -3 \\
\end{cases}
$

$
-2L_2 + L_1 \rightarrow L_1
\Rightarrow
\begin{cases}
x & = &  7 \\
z & = & -3 \\
\end{cases}
$

$
\Rightarrow u_2 = (7, 0, -3, 1, 0)
$

$
\begin{aligned}
y = 0 \\
s = 0 \\
t = 1 \\
\end{aligned}
\Rightarrow
\begin{cases}
 x & + & 3(0) & + & 2z & - &    0 & - &  1 & = & 0 \\
   &   &      &   &  z & + & 3(0) & + &  1 & = & 0 \\
\end{cases}
\Rightarrow
\begin{cases}
 x & + & 2z & = &  1 \\
   &   &  z & = & -1 \\
\end{cases}
$

$
-2L_2 + L_1 \rightarrow L_1
\Rightarrow
\begin{cases}
x & = &  3 \\
z & = & -1 \\
\end{cases}
$

$
\Rightarrow u_3 = (3, 0, -1, 0, 1)
$

Base: $\{u_1, u_2, u_3\} = \{(-3, 1, 0, 0, 0), (7, 0, -3, 1, 0), (3, 0, -1, 0, 1)\}$
