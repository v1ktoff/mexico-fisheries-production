# Análisis Multivariado de la Producción Pesquera en México (2005-2018)

Este repositorio corresponde al reabajo final de mi curso de estadistica multivariada, contiene el análisis estadístico multivariante realizado sobre los datos de la producción pesquera en México entre los años 2005 y 2018. El objetivo de este proyecto es aplicar técnicas avanzadas de análisis de datos para extraer información relevante y patrones en la producción pesquera, utilizando técnicas de Regresión Lineal Múltiple (RLM), Análisis de Componentes Principales (PCA), Clustering y Visualización Multivariante.

## Descripción

El conjunto de datos utilizado proviene de la plataforma Kaggle, en el dataset Fisheries Production in Mexico (2005 to 2018)
. Este análisis se centra en predecir el valor de la producción pesquera y en explorar las dinámicas entre las diferentes variables del dataset, que incluyen datos temporales, geográficos, biológicos y técnicos.

## Objetivos

- Regresión Lineal Múltiple: Estimar el valor total de la producción pesquera en pesos mexicanos en función de variables explicativas como el peso desembarcado, el año, la especie, la región, etc.

- Visualización Multivariante: Aplicar gráficas multivariadas para explorar las relaciones entre múltiples variables de manera visual.

- Análisis de Componentes Principales (PCA): Reducir la dimensionalidad del conjunto de datos y analizar cómo las diferentes variables contribuyen a la variabilidad global.

- Clustering: Implementar técnicas de agrupamiento (como K-means) para identificar grupos homogéneos dentro del sector pesquero.

- Conclusiones: Presentar conclusiones basadas en el análisis de los datos, discutiendo tendencias y posibles áreas de mejora.

## Estructura del Proyecto

El análisis se desarrolla a través de diferentes secciones:

- Descripción y Carga de Datos: Carga de datos y transformación de variables.

- Regresión Lineal Múltiple (RLM): Modelado de la variable objetivo y validación de supuestos.

- Visualización de Datos: Creación de gráficos de series de tiempo, gráficos 3D y análisis de relaciones entre variables.

- Análisis de Componentes Principales (PCA): Reducción de dimensionalidad y visualización de la varianza explicada.

- Clustering: Segmentación del dataset utilizando K-means en el espacio reducido por PCA.

## Requisitos

Para ejecutar este proyecto, se deben instalar las siguientes librerías de R:

leaps
GGally
ggplot2
olsrr
MASS
lmtest
dplyr
plotly
scales
scatterplot3d
tidyr
cluster
factoextra

Puedes instalar todas las dependencias necesarias usando el siguiente código en R:

`install.packages(c("leaps", "GGally", "ggplot2", "olsrr", "MASS", "lmtest", "dplyr", "plotly", "scales", "scatterplot3d", "tidyr", "cluster", "factoextra"))`

## Uso

Clona este repositorio en tu máquina local:

`git clone https://github.com/tu-usuario/analisis-produccion-pesquera.git`


Carga los datos en R y ejecuta los scripts para realizar el análisis de regresión, PCA, clustering y visualización.

`source("analisis_pesquera.R")`

