# CAPITULO 1 - SISTEMAS DE ECUACIONES LINEALES

## MATRICES ESCALONADAS Y OPERACIONES ELEMENTALES ENTRE FILAS

1.57. Supóngase que $A$ es una matriz cuadrada escalonada por filas. Demostrar que si $A \neq I$, la matriz identidad, $A$ tiene una fila nula.

En una matriz cuadrada escalonada por filas, el número máximo de pivotes es $n$, uno por fila. Si hay un pivote en cada fila y columna, la matriz debe ser la identidad $I$, ya que los pivotes deben aparecer en la diagonal principal con ceros debajo. Por tanto, si $A \neq I$, no puede haber un pivote en cada fila: hay menos de $n$ pivotes, lo que significa que alguna fila carece de pivote y, en una forma escalonada por filas, eso implica que esa fila es nula.

---
