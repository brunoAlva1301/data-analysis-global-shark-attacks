# Data Analysis — Global Shark Attacks

## Descripción

Proyecto académico de limpieza, transformación y análisis exploratorio de datos utilizando Python.

El análisis se realizó sobre el dataset **Global Shark Attacks**, obtenido de Kaggle y basado en información del Global Shark Attack File.

## Dataset

- Registros originales: 25.723
- Registros luego de la limpieza inicial: aproximadamente 6.302
- Variables principales utilizadas: actividad, edad y resultado del ataque.

## Proceso de análisis

El proyecto incluye:

- Eliminación de registros vacíos y duplicados.
- Selección de variables relevantes.
- Limpieza y transformación de datos.
- Categorización de actividades.
- Conversión de edades a rangos etarios.
- Normalización de la variable de fatalidad en categorías `Fatal` / `No fatal`.
- Análisis de distribución de ataques según actividad y rango etario.
- Análisis del porcentaje de ataques fatales.
- Comparación de fatalidad según actividad.
- Visualización de resultados.

## Preguntas analizadas

1. ¿Qué actividades concentran la mayor cantidad de ataques registrados?
2. ¿Qué porcentaje de los ataques registrados fueron fatales?
3. ¿Cómo varía la fatalidad según la actividad realizada?
4. ¿Qué actividades presentan mayor peligrosidad relativa dentro del dataset?

## Tecnologías

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Archivos

- `TP_Alvarez_Bruno.ipynb` — Notebook con el análisis, código, resultados y visualizaciones.
- `attacks.csv` — Dataset utilizado.

## Fuente

Dataset: [Global Shark Attacks — Kaggle](https://www.kaggle.com/datasets/teajay/global-shark-attacks)

Fuente original de los datos: Global Shark Attack File.
