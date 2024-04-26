# Análisis de Regresión Lineal Simple: Precios de Bienes Raíces

## Contenido del Repositorio

Este repositorio contiene un análisis de regresión lineal simple aplicado a un conjunto de datos de bienes raíces. El análisis se enfoca en la relación entre el tamaño de las propiedades y sus precios.

Los archivos en este repositorio son los siguientes:

- `real_estate_price_size.csv`: Este archivo CSV contiene los datos utilizados en el análisis. Contiene dos columnas: 'size' (tamaño de la propiedad) y 'price' (precio de la propiedad).

- `regression_analysis.ipynb`: Este es el cuaderno de Jupyter utilizado para realizar el análisis. Contiene el código Python junto con explicaciones detalladas y visualizaciones del proceso de regresión lineal.

## Requisitos

Para ejecutar el código en el cuaderno de Jupyter, se requieren las siguientes bibliotecas de Python:

- NumPy
- Pandas
- Matplotlib
- Statsmodels

Estas bibliotecas pueden ser instaladas usando pip.


## Ejecución del Análisis

Para ejecutar el análisis, abre el cuaderno de Jupyter `regression_analysis.ipynb` en tu entorno de Jupyter Notebook y ejecuta las celdas secuencialmente. Asegúrate de tener el archivo CSV `real_estate_price_size.csv` en el mismo directorio que el cuaderno.

## Detalles del Análisis

El análisis sigue los siguientes pasos:

1. Importación de bibliotecas y lectura de datos desde el archivo CSV.
2. Visualización de los datos mediante un gráfico de dispersión.
3. Ajuste de un modelo de regresión lineal utilizando statsmodels.
4. Visualización de la línea de regresión en el gráfico de dispersión.
5. Resumen detallado de los resultados del análisis.

## Resultados

El análisis revela la relación entre el tamaño de las propiedades y sus precios en el mercado inmobiliario.
## Objetivo del Análisis

El objetivo de este análisis de regresión lineal simple es investigar y comprender la relación entre el tamaño y el precio de las propiedades en el mercado inmobiliario. Al realizar este análisis, buscamos:

- Determinar si existe una relación lineal significativa entre el tamaño y el precio de las propiedades.
- Proporcionar una herramienta predictiva para estimar el precio de una propiedad en función de su tamaño.
- Explorar visualmente la relación entre las variables mediante gráficos de dispersión y líneas de regresión.

Este análisis tiene aplicaciones potenciales en la valoración de propiedades y en la identificación de factores que influyen en los precios de bienes raíces.
