# **Actividad #18 – Determinantes**

**Materia:** Fundamentos de Álgebra
**Alumno:** Heidi Esther Peña Betanzos
**Grupo:** 1C
**Institución:** Tecnológico de Software

---

## **Ejercicio 1 – Determinantes 2×2**

El determinante de una matriz 2×2:

$$ begin{pmatrix} a & b \\ c & d \end{pmatrix} \quad \Rightarrow \quad \det = ad - bc $$

### **Matriz A**

[
A=\begin{pmatrix}
5 & 2 \
3 & 1
\end{pmatrix}
]

[
\det(A)=5(1)-2(3)=-1
]

### **Matriz B**

[
B=\begin{pmatrix}
-1 & 4 \
2 & -8
\end{pmatrix}
]

[
\det(B)=(-1)(-8)-4(2)=0
]

### **Matriz C**

[
C=\begin{pmatrix}
6 & 9 \
2 & 3
\end{pmatrix}
]

[
\det(C)=6(3)-9(2)=0
]

### **Matriz D**

[
D=\begin{pmatrix}
0 & 5 \
-5 & 0
\end{pmatrix}
]

[
\det(D)=0(0)-5(-5)=25
]

---

## **Ejercicio 2 – Regla de Sarrus (3×3)**

La regla de Sarrus calcula el determinante así:

[
\det = (\text{suma de diagonales principales}) - (\text{suma de diagonales secundarias})
]

### **Matriz E**

[
E=\begin{pmatrix}
1 & 2 & 3 \
0 & 1 & 4 \
5 & 6 & 0
\end{pmatrix}
]

[
\det(E)=40-39=1
]

### **Matriz F**

[
F=\begin{pmatrix}
2 & -1 & 3 \
1 & 4 & 0 \
3 & 2 & -2
\end{pmatrix}
]

[
\det(F)=-10-38=-48
]

---

## **Ejercicio 3 – Método de Cofactores**

[
G=\begin{pmatrix}
1 & 0 & 2 \
-1 & 3 & 1 \
2 & 0 & 1
\end{pmatrix}
]

Se expande por la segunda columna:

[
\det(G)=3,C_{22}
]

[
C_{22}=
\begin{vmatrix}
1 & 2 \
2 & 1
\end{vmatrix}=-3
]

[
\det(G)=3(-3)=-9
]

---

## **Ejercicio 4 – Propiedades de los determinantes**

Matrices utilizadas:

[
A=\begin{pmatrix}
2 & 1 \
1 & 3
\end{pmatrix},
\quad
B=\begin{pmatrix}
1 & 2 \
3 & 1
\end{pmatrix}
]

### **1. Verificar que (\det(AB)=\det(A)\det(B))**

[
\det(A)=5,\quad \det(B)=-5,\quad \det(A)\det(B)=-25
]

**Multiplicación:**

[
AB=
\begin{pmatrix}
5 & 5 \
10 & 5
\end{pmatrix}
]

[
\det(AB)=5\cdot5 - 5\cdot10 = -25
]

✔ **Se cumple la propiedad.**

---

### **2. Verificar que (\det(A^T)=\det(A))**

[
A^T=
\begin{pmatrix}
2 & 1 \
1 & 3
\end{pmatrix}
]

[
\det(A^T)=5=\det(A)
]

✔ **Se cumple la propiedad.**

---

## **Ejercicio 5 – Aplicación geométrica (Área de un paralelogramo)**

Vectores:

[
\vec{u}=(3,2),\quad \vec{v}=(1,4)
]

Área:

[
\text{Área}=\left|
\det\begin{pmatrix}
3 & 1 \
2 & 4
\end{pmatrix}
\right|=10
]

### **a) Área total**

[
\text{Área}=10
]

### **b) ¿Cambia si se intercambian los vectores?**

[
\det\begin{pmatrix}
1 & 3 \
4 & 2
\end{pmatrix}=-10
]

El signo cambia, **el área no**.

### **c) Significado del signo**

* Determinante positivo → orientación antihoraria
* Determinante negativo → orientación horaria

El área siempre es **el valor absoluto**.

---
