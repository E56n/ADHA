# 📊 Modelado Matemático del Crecimiento de Pasajeros Aéreos (1949–1960)

Este proyecto presenta un análisis del crecimiento en el número de pasajeros de aerolíneas internacionales entre 1949 y 1960, utilizando un modelo matemático **exponencial** para ajustar los datos históricos.

## 📁 Contenido

- `modelado_matematico_de_pasajeros_aereos_1949_1960.ipynb`: Notebook con todo el análisis, visualizaciones y modelado.
- Gráficos comparativos entre datos reales y modelo ajustado.
- Cálculo de métricas de error: MAE y MSE.
- Visualización de la ecuación del modelo directamente en el gráfico.

## 📈 Objetivo

Modelar el crecimiento de pasajeros usando la ecuación:

$y = A \cdot e^{Bx}$


Donde:
- `y`: número de pasajeros
- `x`: meses desde enero de 1949
- `A`, `B`: parámetros obtenidos por regresión lineal sobre los datos log-transformados

## 📊 Métricas de Evaluación

- **MAE (Error Medio Absoluto)**: Evalúa el promedio de errores absolutos.
- **MSE (Error Cuadrático Medio)**: Penaliza errores grandes, útil para detectar desviaciones significativas.

## 📦 Requisitos

```bash
pip install numpy matplotlib scikit-learn
``` 
📌 Fuente de Datos
Airline Passengers Dataset: https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv

🧠 Autor
Eder Said Martínez Ramírez Apasionado por la ciencia de datos, el modelado estadístico y la visualización efectiva. 🔍 En búsqueda activa de roles en Data Science, Machine Learning y Data Engineering.
