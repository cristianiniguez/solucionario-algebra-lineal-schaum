# CAPITULO 1 - SISTEMAS DE ECUACIONES LINEALES

## SISTEMAS HOMOGÉNEOS

1.53. Hallar la dimensión y una base para la solución general $W$ de cada uno de los sistemas siguientes:

b. $
\begin{cases}
2x & - &  4y & + & 3z & - &  s & + & 2t & = & 0 \\
3x & - &  6y & + & 5z & - & 2s & + & 4t & = & 0 \\
5x & - & 10y & + & 7z & - & 3s & + &  t & = & 0 \\
\end{cases}
$

$
\begin{aligned}
-3L_1 + 2L_2 & \rightarrow L_2 \\
-5L_1 + 2L_3 & \rightarrow L_3
\end{aligned}
\Rightarrow
\begin{cases}
2x & - & 4y & + & 3z & - & s & + & 2t & = & 0 \\
   &   &    &   &  z & - & s & + & 2t & = & 0 \\
   &   &    & - &  z & - & s & - & 8t & = & 0 \\
\end{cases}
$

$L_2 + L_3 \rightarrow L_3 \Rightarrow
\begin{cases}
2x & - & 4y & + & 3z & - & s & + & 2t & = & 0 \\
   &   &    &   &  z & - &  s & + & 2t & = & 0 \\
   &   &    &   &    & - & 2s & - & 6t & = & 0 \\
\end{cases}
$

$-\frac{1}{2}L_3 \rightarrow L_3 \Rightarrow
\begin{cases}
2x & - & 4y & + & 3z & - & s & + & 2t & = & 0 \\
   &   &    &   &  z & - &  s & + & 2t & = & 0 \\
   &   &    &   &    &   &  s & + & 3t & = & 0 \\
\end{cases}
$

Variables libres: $y, t$. Por lo tanto $\dim W = 2$.

$\{u_1, u_2\} = \{(2, 1, 0, 0, 0), (5, 0, -5, -3, 1)\}$
