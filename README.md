# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Heidi Esther Peña Betanzos
## Actividad \#20 - Documentación de Matrices
## Grupo 1C
## Fecha: 22/11/2025

---
# Objetivo de esta documentación 
El objetivo de esta documentación fue explicar detalladamente el proceso de representación, manipulación y operación de matrices en Google Sheets o Execel, aplicadas a imágenes de 30×30 píxeles.
Cada hoja del documento contiene matrices que representan imágenes, sus traspuestas y diversas operaciones matriciales como suma, resta, multiplicación escalar y composición lineal entre matrices.

# 1.Matrizes Originales (dibujo1-dubujo5)
Cada hoja contiene una imagen  representada como una matriz de 30x30.
Los valores de cada una se representan en niveles de coloes entre 0 y 1.

1.dibujo1


matriz = [
    [0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	1	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	1	1	0,1	0,3	1	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	1	0,1	0,1	0,1	0,1	0,3	0,3	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	1	0,1	0,1	0,1	0,1	0,1	0,3	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	1	0,1	0,1	0,1	0,1	0,1	0,1	0,3	0,3	1	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0,8	0,1	0,1	0,1	0,1	0,1	0,1	0,3	0,3	0,8	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0,4	0,8	0,8	0,1	0,1	0,1	0,1	0,1	0,3	0,8	0,8	0,4	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0,4	0,4	0,4	0,8	0,1	0,1	0,1	0,1	0,8	0,4	0,4	0,4	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0,8	0,4	0,4	0,4	0,8	0,8	0,8	0,8	0,4	0,4	0,4	0,8	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0,4	0,4	0,4	0,4	0,4	0,4	0,4	0,4	0,4	0,4	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0,4	0,4	0,4	0,3	0,6	0,3	0,6	0,4	0,4	0,4	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0,4	0,4	0,4	0,4	0,4	0,4	0,4	0,4	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0,4	0,4	0,4	0,4	0,4	0,4	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0,4	0,4	0,4	0,4	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0],
  
]
separator = "|" + "---|"*30
print(separator)

for row in matriz:
    line = "| " + " | ".join(str(x) for x in row) + " |"
    print(line)




