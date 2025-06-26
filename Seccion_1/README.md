# Fundamentos en Matemática y Estadística para Análisis de Datos Cohorte III 2025-1

## Actividad 1  
### Fundamentos Matemáticos - Semana 1

Esta actividad tiene como objetivo afianzar conceptos clave de funciones y su representación gráfica, fundamentales para el análisis de datos y el aprendizaje automático. A continuación, se trabajará con funciones matemáticas relevantes usando Python.

1. Álgebra de Matrices en Analítica de Datos: 
   - Represente un conjunto de datos como una matriz. Realice operaciones algebraicas básicas y 
discuta cómo el álgebra de matrices es esencial para analizar datos.
## Punto 1
## 1. Álgebra de Matrices en Analítica de Datos

En analítica de datos, los datos frecuentemente se representan como matrices, donde cada fila es una observación y cada columna una variable. El álgebra de matrices permite realizar operaciones como suma, producto y transposición, que son fundamentales para modelar y transformar datos.

A continuación, se muestra un ejemplo en Python utilizando NumPy para representar y manipular matrices.

```python
import numpy as np

# Creamos una matriz de datos: 3 filas (observaciones), 3 columnas (variables)
A = np.array([[5, 7, 9],
              [2, 4, 6],
              [8, 1, 3]])

# Otra matriz del mismo tamaño
B = np.array([[1, 1, 1],
              [1, 1, 1],
              [1, 1, 1]])

# Suma de matrices
suma = A + B

# Producto matricial
producto = np.dot(A, B)

# Transpuesta
transpuesta = A.T

print("Matriz A:\n", A)
print("\nMatriz B:\n", B)
print("\nSuma A + B:\n", suma)
print("\nProducto A x B:\n", producto)
print("\nTranspuesta de A:\n", transpuesta)
