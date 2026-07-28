# Proyecto: Análisis de Correlación y Asociación de Variables en Nova Market

## Objetivo del proyecto

El objetivo de este proyecto es analizar las relaciones existentes entre las variables del dataset **Nova Market** mediante técnicas de análisis exploratorio y métodos estadísticos de correlación y asociación. Se busca identificar patrones entre variables numéricas, binarias y categóricas para generar hallazgos que apoyen la toma de decisiones del negocio, siempre distinguiendo entre asociación estadística y causalidad.

---

## Dataset utilizado

El proyecto utiliza el siguiente conjunto de datos:

- **nova_market_activity.csv:** Contiene información de **15,000 clientes** y **12 variables**, incluyendo características demográficas, comportamiento de compra, visitas mensuales, gasto en publicidad dirigida, satisfacción del cliente, membresía premium, abandono, tipo de dispositivo, región e ingreso anual.

---

## Etapas del análisis

Durante el desarrollo del proyecto se realizaron las siguientes etapas:

1. Carga y exploración inicial del dataset.
2. Revisión de la estructura, tipos de datos y calidad de la información.
3. Corrección de tipos de datos cuando fue necesario.
4. Obtención de estadísticas descriptivas de variables numéricas.
5. Exploración de variables categóricas y binarias.
6. Construcción de una matriz de correlación y visualización mediante un heatmap.
7. Análisis de relaciones mediante scatterplots para pares de variables con correlaciones moderadas o fuertes.
8. Cálculo de coeficientes de correlación utilizando los métodos de Pearson y Spearman.
9. Evaluación de la relación entre variables binarias y numéricas mediante la correlación punto-biserial.
10. Medición de la asociación entre variables categóricas utilizando el coeficiente V de Cramér.
11. Interpretación de los resultados y elaboración de hallazgos para el negocio.
12. Identificación de limitaciones y propuestas para análisis futuros.

---

## Cómo ejecutar el notebook

1. Descarga el notebook (`.ipynb`) y el archivo **nova_market_activity.csv**.
2. Abre el notebook en **Google Colab** o **Jupyter Notebook**.
3. Coloca el archivo CSV en la carpeta correspondiente o modifica la ruta del archivo en la instrucción `pd.read_csv()`.
4. Ejecuta todas las celdas en orden, desde la primera hasta la última.

---

## Guía de reproducción

Para reproducir el análisis:

- Asegúrate de contar con **Python 3** y las siguientes bibliotecas:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy

- Verifica que el archivo **nova_market_activity.csv** se encuentre en la ruta correcta antes de ejecutar el notebook.

- Ejecuta el notebook siguiendo el orden de las celdas.

- Al finalizar, se generarán las estadísticas descriptivas, los gráficos de exploración, la matriz de correlación, los coeficientes de asociación y las conclusiones correspondientes al análisis.
