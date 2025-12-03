Tecnológico de Software
Materia: Fundamentos de Álgebra
Alumna: Heidi Esther Peña Betanzos
Actividad #22 – Matrices

Para esta actividad se resolvieron ejercicios que involucran matrices utilizando distintos métodos: Gauss, Gauss-Jordan, Inversa y Cramer. El objetivo es documentar el procedimiento y los resultados obtenidos para las variables x, y y z.

Ejercicio 1

Resolver el siguiente sistema por todos los métodos:

{
𝑥
+
𝑦
+
𝑧
=
6


2
𝑥
−
𝑦
+
𝑧
=
3


𝑥
+
2
𝑦
−
𝑧
=
2
⎩
⎨
⎧
	​

x+y+z=6
2x−y+z=3
x+2y−z=2
	​


Matriz de coeficientes:

𝐴
=
[
1
	
1
	
1


2
	
−
1
	
1


1
	
2
	
−
1
]
A=
	​

1
2
1
	​

1
−1
2
	​

1
1
−1
	​

	​


Matriz de términos independientes:

𝐵
=
[
6


3


2
]
B=
	​

6
3
2
	​

	​

Método de Gauss

Matriz aumentada:

[
1
	
1
	
1
	
6


2
	
−
1
	
1
	
3


1
	
2
	
−
1
	
2
]
	​

1
2
1
	​

1
−1
2
	​

1
1
−1
	​

6
3
2
	​

	​


Operaciones:

R2 → R2 − 2R1
R3 → R3 − R1

[
1
	
1
	
1
	
6


0
	
−
3
	
−
1
	
−
9


0
	
1
	
−
2
	
−
4
]
	​

1
0
0
	​

1
−3
1
	​

1
−1
−2
	​

6
−9
−4
	​

	​


R2 → (-1/3)R2

[
1
	
1
	
1
	
6


0
	
1
	
−
1
3
	
3


0
	
1
	
−
2
	
−
4
]
	​

1
0
0
	​

1
1
1
	​

1
−
3
1
	​

−2
	​

6
3
−4
	​

	​


R3 → R3 − R2

[
1
	
1
	
1
	
6


0
	
1
	
−
1
3
	
3


0
	
0
	
−
7
3
	
−
7
]
	​

1
0
0
	​

1
1
0
	​

1
−
3
1
	​

−
3
7
	​

	​

6
3
−7
	​

	​


Despeje:

−
7
3
𝑧
=
−
7
⇒
𝑧
=
3
−
3
7
	​

z=−7⇒z=3
𝑦
+
1
3
(
3
)
=
3
⇒
𝑦
=
2
y+
3
1
	​

(3)=3⇒y=2
𝑥
+
2
+
3
=
6
⇒
𝑥
=
1
x+2+3=6⇒x=1

Solución por Gauss:

(
𝑥
,
𝑦
,
𝑧
)
=
(
1
,
2
,
3
)
(x,y,z)=(1,2,3)
Método Gauss-Jordan

Al aplicar las operaciones correspondientes se obtiene finalmente:

[
1
	
0
	
0
	
1


0
	
1
	
0
	
2


0
	
0
	
1
	
3
]
	​

1
0
0
	​

0
1
0
	​

0
0
1
	​

1
2
3
	​

	​


Solución por Gauss-Jordan:

𝑥
=
1
,
 
𝑦
=
2
,
 
𝑧
=
3
x=1, y=2, z=3
Método de la Inversa
𝑋
=
𝐴
−
1
𝐵
X=A
−1
B

Al calcular la inversa de A y multiplicar por B:

𝑋
=
[
1


2


3
]
X=
	​

1
2
3
	​

	​


Solución por Inversa:

(
𝑥
,
𝑦
,
𝑧
)
=
(
1
,
2
,
3
)
(x,y,z)=(1,2,3)
Método de Cramer
𝑥
=
∣
𝐴
𝑥
∣
∣
𝐴
∣
=
1
,
𝑦
=
∣
𝐴
𝑦
∣
∣
𝐴
∣
=
2
,
𝑧
=
∣
𝐴
𝑧
∣
∣
𝐴
∣
=
3
x=
∣A∣
∣A
x
	​

∣
	​

=1,y=
∣A∣
∣A
y
	​

∣
	​

=2,z=
∣A∣
∣A
z
	​

∣
	​

=3

Solución por Cramer:

(
𝑥
,
𝑦
,
𝑧
)
=
(
1
,
2
,
3
)
(x,y,z)=(1,2,3)
Solución Final
𝑥
=
1
,
𝑦
=
2
,
𝑧
=
3
x=1,y=2,z=3
