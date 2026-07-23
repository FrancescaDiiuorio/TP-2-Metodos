# TP 2 - Métodos Computacionales

Trabajo práctico de la materia Métodos Computacionales (UTDT) sobre curvas de Bézier y ajuste de datos por cuadrados mínimos.

## Contenido

El TP está resuelto en un notebook (`tp2.ipynb`) organizado en 13 ejercicios, entre los que se incluyen:

- Funciones base de Bernstein y construcción de curvas de Bézier cúbicas
- Ajuste de puntos de control por cuadrados mínimos (matrices A, P, Q)
- Deducción analítica de la función de error E(p) y su convexidad (autovalores de AᵀA)
- Implementación de descenso por gradiente con distintos valores de α
- Implementación del método de Newton
- Estudio del efecto del ruido (σ) en la calidad del ajuste

Las figuras generadas en cada ejercicio están guardadas en `TP 2/figuras/`. El enunciado original está en `TP 2/Trabajo practico 2.pdf`.

## Stack

Python — NumPy, Matplotlib, Jupyter Notebook.

## Cómo verlo

Abrir `TP 2/tp2.ipynb` con Jupyter Notebook o JupyterLab. Requiere `numpy` y `matplotlib` instalados.

## Autoras

Trabajo grupal desarrollado por Francesca Di Iuorio y Lourdes Moreira.
