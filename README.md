# Tecnológico de Software
## Materia: Fundamentos de Álgebra
## Alumna: Heidi Esther Peña Betanzos
## Actividad #22 – Matrices

En esta actividad se resolvieron sistemas de ecuaciones utilizando los métodos:
- Gauss
- Gauss-Jordan
- Inversa
- Cramer

El objetivo es documentar el procedimiento y los resultados obtenidos para las variables x, y y z.

---

# Ejercicio 1

Sistema a resolver:

x + y + z = 6  
2x - y + z = 3  
x + 2y - z = 2  

---

## Matriz de coeficientes

A =
[  
  1   1   1  
  2  -1   1  
  1   2  -1  
]

Vector B =
[  
  6  
  3  
  2  
]

---

# Método de Gauss

Matriz aumentada inicial:

[  
  1   1   1 | 6  
  2  -1   1 | 3  
  1   2  -1 | 2  
]

Operaciones:

R2 = R2 - 2R1  
R3 = R3 - R1  

[  
  1   1    1 | 6  
  0  -3   -1 | -9  
  0   1   -2 | -4  
]

R2 = (-1/3)R2  

[  
  1   1    1 | 6  
  0   1  -1/3 | 3  
  0   1   -2  | -4  
]

R3 = R3 - R2  

[  
  1   1    1 | 6  
  0   1  -1/3 | 3  
  0   0  -7/3 | -7  
]

Despeje final:

z = 3  
y = 2  
x = 1  

Solución por Gauss:
(x, y, z) = (1, 2, 3)

---

# Método de Gauss-Jordan

Matriz final:

[  
  1   0   0 | 1  
  0   1   0 | 2  
  0   0   1 | 3  
]

Solución:
(x, y, z) = (1, 2, 3)

---

# Método de la Inversa

X = A⁻¹B  

Resultado:  
X =  
[  
  1  
  2  
  3  
]

Solución por Inversa:
(x, y, z) = (1, 2, 3)

---

# Método de Cramer

x = 1  
y = 2  
z = 3  

Solución por Cramer:
(x, y, z) = (1, 2, 3)

---

# Solución Final

x = 1  
y = 2  
z = 3
