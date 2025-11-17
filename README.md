# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Heidi Esther Peña Betanzos
## Grupo: 1C
## Actividad #18 – Determinantes

---

### EJERCICIO 1 – Determinantes 2×2

Para una matriz

$$
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
$$

el determinante se calcula como:

$$
\det = ad - bc
$$

---

**Matriz A**

$$
A =
\begin{pmatrix}
5 & 2 \\
3 & 1
\end{pmatrix}
$$

$$
\det(A) = 5(1) - 2(3) = 5 - 6 = -1
$$

---

**Matriz B**

$$
B =
\begin{pmatrix}
-1 & 4 \\
2 & -8
\end{pmatrix}
$$

$$
\det(B) = (-1)(-8) - 4(2) = 8 - 8 = 0
$$

---

**Matriz C**

$$
C =
\begin{pmatrix}
6 & 9 \\
2 & 3
\end{pmatrix}
$$

$$
\det(C) = 6(3) - 9(2) = 18 - 18 = 0
$$

---

**Matriz D**

$$
D =
\begin{pmatrix}
0 & 5 \\
-5 & 0
\end{pmatrix}
$$

$$
\det(D) = 0(0) - 5(-5) = 0 + 25 = 25
$$

---

### EJERCICIO 2 – Regla de Sarrus (3×3)

Para una matriz 3×3:

$$
\det = (\text{diagonales principales}) - (\text{diagonales secundarias})
$$

---

**Matriz E**

$$
E =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
5 & 6 & 0
\end{pmatrix}
$$

**Diagonales positivas:**

$$
1\cdot1\cdot0 = 0, \quad 2\cdot4\cdot5 = 40, \quad 3\cdot0\cdot6 = 0
$$

$$
\text{Suma positiva} = 40
$$

**Diagonales negativas:**

$$
3\cdot1\cdot5 = 15, \quad 2\cdot0\cdot0 = 0, \quad 1\cdot4\cdot6 = 24
$$

$$
\text{Suma negativa} = 15 + 0 + 24 = 39
$$

**Determinante:**

$$
\det(E) = 40 - 39 = 1
$$

---

**Matriz F**

$$
F =
\begin{pmatrix}
2 & -1 & 3 \\
1 & 4 & 0 \\
3 & 2 & -2
\end{pmatrix}
$$

**Diagonales positivas:**

$$
2\cdot4\cdot(-2) = -16, \quad (-1)\cdot0\cdot3 = 0, \quad 3\cdot1\cdot2 = 6
$$

$$
\text{Suma positiva} = -16 + 0 + 6 = -10
$$

**Diagonales negativas:**

$$
3\cdot4\cdot3 = 36, \quad (-1)\cdot1\cdot(-2) = 2, \quad 2\cdot0\cdot2 = 0
$$

$$
\text{Suma negativa} = 36 + 2 + 0 = 38
$$

**Determinante:**

$$
\det(F) = -10 - 38 = -48
$$
### Ejercicio 1 y 2 corregidos a la perfeccion para que se vean mas esteticos 