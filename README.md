# Análisis de Resultados SAT en Escuelas de Nueva York

**Python | Pandas | Matplotlib | Seaborn | Data Cleaning | Exploratory Data Analysis (EDA)**

## Descripción del proyecto

Este proyecto tiene como objetivo analizar el desempeño académico de diferentes escuelas de Nueva York a partir de los resultados de los exámenes SAT, considerando las puntuaciones obtenidas en matemáticas, lectura y escritura. A través de un proceso de limpieza y análisis exploratorio de datos (EDA), se busca identificar las 20 escuelas con mejores resultados académicos y explorar cómo se distribuyen entre los cinco distritos de Nueva York (Manhattan, Bronx, Brooklyn, Queens y Staten Island).

## Objetivos

- Preparar y limpiar el conjunto de datos, identificando valores faltantes, duplicados y posibles valores atípicos.
- Analizar la distribución de las puntuaciones SAT y los niveles de participación estudiantil.
- Identificar las 20 escuelas con mejor promedio académico.
- Comparar el rendimiento entre los diferentes distritos de Nueva York.
- Explorar las relaciones entre las puntuaciones de matemáticas, lectura, escritura y participación en los exámenes.

## Metodología

El proyecto se desarrolló en dos etapas principales:

**1. Limpieza y preparación de datos (`Examenes_SAT_P1_Clean.ipynb`)**

Se trabajó con un dataset inicial de 375 registros y 7 variables. Se realizó la identificación y tratamiento de valores faltantes, revisión de duplicados, análisis de valores atípicos y validación de variables categóricas y numéricas. Como resultado, se obtuvo un conjunto de 355 registros completos para el análisis.

**2. Análisis exploratorio (`Examenes_SAT_P2_EDA.ipynb`)**

Se aplicaron técnicas de estadística descriptiva y visualización de datos para estudiar las distribuciones de los puntajes SAT, construir un ranking de las mejores escuelas, comparar los resultados por distrito y evaluar las correlaciones entre variables académicas.

## Principales hallazgos

- **Rendimiento académico:** Stuyvesant High School obtuvo el promedio SAT más alto, con aproximadamente 715 puntos por sección.
- **Diferencias geográficas:** Se identificó una concentración de escuelas con altos resultados académicos en Manhattan.
- **Relación entre asignaturas:** Las puntuaciones de matemáticas, lectura y escritura presentan correlaciones positivas elevadas, indicando que las escuelas con mejores resultados tienden a destacar en las tres áreas.
- **Participación estudiantil:** Las escuelas del Top 20 presentan porcentajes relativamente altos de participación en los exámenes SAT.

## Herramientas utilizadas

- **Python:** procesamiento y análisis de datos.
- **Pandas:** limpieza, transformación y análisis estadístico.
- **Matplotlib y Seaborn:** visualización de distribuciones, comparaciones y correlaciones.
- **Google Colab / Jupyter Notebook:** desarrollo y documentación del análisis.

## Archivos del proyecto

| `SchoolTransport.csv` | Dataset original |
| `SchoolTransport_clean.csv` | Dataset procesado y limpio |
| `Examenes_SAT_P1_Clean.ipynb` | Limpieza y preparación de datos |
| `Examenes_SAT_P2_EDA.ipynb` | Análisis exploratorio y visualizaciones |

## Conclusión

Este proyecto permitió aplicar un flujo de trabajo de análisis de datos, desde la preparación de la información hasta la identificación de patrones mediante técnicas estadísticas y visualizaciones. Los resultados evidencian diferencias en el desempeño académico entre las escuelas y los distritos de Nueva York, destacando la utilidad del análisis exploratorio para transformar datos educativos en información relevante para comprender el comportamiento de los resultados SAT.
