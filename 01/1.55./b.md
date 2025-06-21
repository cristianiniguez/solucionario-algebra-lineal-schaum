# CAPITULO 1 - SISTEMAS DE ECUACIONES LINEALES

## MATRICES ESCALONADAS Y OPERACIONES ELEMENTALES ENTRE FILAS

1.55. Reducir $A$ a forma escalonada y luego a su forma canónica por filas, siendo:

b. $
A =
\begin{pmatrix}
0 & 1 &  3 & -2 \\
0 & 4 & -1 &  3 \\
0 & 0 &  1 &  1 \\
0 & 5 & -3 &  4 \\
\end{pmatrix}
$

$
\begin{aligned}
-4L_1 + L_2 & \rightarrow L_2 \\
-5L_1 + L_4 & \rightarrow L_4
\end{aligned}
\Rightarrow
\begin{pmatrix}
0 & 1 &   3 & -2 \\
0 & 0 & -13 & 11 \\
0 & 0 &   1 &  1 \\
0 & 0 & -18 & 14 \\
\end{pmatrix}
$

$
\begin{aligned}
 -L_2 - 13L_3 & \rightarrow L_3 \\
18L_2 - 13L_3 & \rightarrow L_4
\end{aligned}
\Rightarrow
\begin{pmatrix}
0 & 1 &   3 &  -2 \\
0 & 0 & -13 &  11 \\
0 & 0 &   0 & -24 \\
0 & 0 &   0 &  16 \\
\end{pmatrix}
$

$
-16L_3 - 24L_4 \rightarrow L_4 \Rightarrow
\begin{pmatrix}
0 & 1 &   3 &  -2 \\
0 & 0 & -13 &  11 \\
0 & 0 &   0 & -24 \\
0 & 0 &   0 &   0 \\
\end{pmatrix}
$ (Forma escalonada)

NOTA: en el libro la solución también es correcta, pero se ha hecho de otra forma.

$
-\frac{1}{24}L_3 \rightarrow L_3 \Rightarrow
\begin{pmatrix}
0 & 1 &   3 & -2 \\
0 & 0 & -13 & 11 \\
0 & 0 &   0 &  1 \\
0 & 0 &   0 &  0 \\
\end{pmatrix}
$

$
\begin{aligned}
  2L_3 + L_1 & \rightarrow L_1 \\
-11L_3 + L_2 & \rightarrow L_2 \\
\end{aligned}
\Rightarrow
\begin{pmatrix}
0 & 1 &   3 & 0 \\
0 & 0 & -13 & 0 \\
0 & 0 &   0 & 1 \\
0 & 0 &   0 & 0 \\
\end{pmatrix}
$

$
-\frac{1}{13}L_2 \rightarrow L_2 \Rightarrow
\begin{pmatrix}
0 & 1 & 3 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 \\
0 & 0 & 0 & 0 \\
\end{pmatrix}
$

$
-3L_2 + L_1 \rightarrow L_1 \Rightarrow
\begin{pmatrix}
0 & 1 & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 \\
0 & 0 & 0 & 0 \\
\end{pmatrix}
$ (Forma canónica por filas)
