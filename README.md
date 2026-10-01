# Estadística descriptiva y visualización de datos con Python

Trabajo práctico de la Licenciatura en Inteligencia Artificial y Ciencia de Datos (UADE).

## Descripción
Análisis exploratorio de un conjunto de 16 observaciones con cuatro variables numéricas y una variable categórica. Se calcularon medidas de tendencia central, dispersión y posición, y se construyeron visualizaciones para identificar patrones y relaciones entre variables.

## Tecnologías
- Python
- pandas
- matplotlib
- Jupyter Notebook

## Contenido
- Cálculo de media, mediana, desvío estándar, coeficiente de variación y cuartiles.
- Selección de la medida de tendencia central más representativa según la dispersión de cada variable.
- Análisis segmentado por categoría mediante `groupby`.
- Gráfico de torta, gráfico de dispersión y boxplot por categoría.

## Principales hallazgos
- Var_1 y Var_3 presentan baja dispersión (CV < 5%), por lo que la media resulta representativa.
- Var_2 muestra alta variabilidad (CV ≈ 52%), por lo que se prioriza la mediana.
- Se observa una relación negativa entre Var_3 y Var_4.

## Archivos
- `clase_tp.ipynb`: notebook con el análisis completo.
- `datos_tp.csv`: dataset utilizado.
