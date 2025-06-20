# CAPITULO 1 - SISTEMAS DE ECUACIONES LINEALES

## MATRICES ESCALONADAS Y OPERACIONES ELEMENTALES ENTRE FILAS

1.55. Reducir $A$ a forma escalonada y luego a su forma canónica por filas, siendo:

a. $
A =
\begin{pmatrix}
1 &  3 & -1 & 2 \\
0 & 11 & -5 & 3 \\
2 & -5 &  3 & 1 \\
4 &  1 &  1 & 5 \\
\end{pmatrix}
$

$
\begin{aligned}
-2L_1 + L_3 & \rightarrow L_3 \\
-4L_1 + L_4 & \rightarrow L_4
\end{aligned}
\Rightarrow
\begin{pmatrix}
1 &   3 & -1 &  2 \\
0 &  11 & -5 &  3 \\
0 & -11 &  5 & -3 \\
0 & -11 &  5 & -3 \\
\end{pmatrix}
$

$
\begin{aligned}
L_2 + L_3 & \rightarrow L_3 \\
L_2 + L_4 & \rightarrow L_4
\end{aligned}
\Rightarrow
\begin{pmatrix}
1 &   3 & -1 &  2 \\
0 &  11 & -5 &  3 \\
0 &   0 &  0 &  0 \\
0 &   0 &  0 &  0 \\
\end{pmatrix}
$ (Forma escalonada)

$\frac{1}{11}L_2 \rightarrow L_2 \Rightarrow
\begin{pmatrix}
1 &   3 &            -1 &            2 \\
0 &   1 & -\frac{5}{11} & \frac{3}{11} \\
0 &   0 &             0 &            0 \\
0 &   0 &             0 &            0 \\
\end{pmatrix}
$

$-3L_2 + L_1 \rightarrow L_1 \Rightarrow
\begin{pmatrix}
1 & 0 &  \frac{4}{11} & \frac{4}{11} \\
0 & 1 & -\frac{5}{11} & \frac{3}{11} \\
0 & 0 &             0 &            0 \\
0 & 0 &             0 &            0 \\
\end{pmatrix}
$ (Forma canónica por filas)

---
