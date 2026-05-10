# nutritional-data-analysis
Segundo Proyecto sobre Aprendizaje Supervisado - Inferencia Estadística y Reconocimiento de Patrones - Com 02

- Institución: Universidad Nacional Guillermo Brown
- Año: 2025

## Resumen del proyecto

El repositorio contiene la implementación de diversos modelos de aprendizaje supervisado y no supervisado aplicados a conjuntos de datos heterogéneos, para demostrar el comportamiento de estos en tareas de clasificación, reducción de dimensionalidad y agrupamientos de datos.

## Modelos e Implementaciones

 - ***Boosting:*** Se realizó un análisis comparativo entre AdaBoost y XGBoost utilizando el dataset wine-quality, binarizando la variable respuesta para optimizar y evaluar la capacidad predictiva de ambos modelos en problemas de clasificación binaria.
 - ***Análisis de Componentes Principales -PCA- :*** Se aplicó el modelo sobre un dataset nutricional para lograr identificar la importancia de las variables y así simplificar la estructura de datos.
   Se exploró la visualización mediante biplots de las primeras dos componentes, aunque se determinó que se requieren más dimensiones para capturar la complejidad total del fenómeno.
   Sobre el mismo, se determinó que las primeras 5 componentes principales explican más del 70% de la varianza total, representando una limpieza óptima, aunque a pesar de eso se observó que con 8 componentes se alcanza más del 93% de la información.
- ***Clustering:*** Se trabajó sobre un dataset de exoplanetas para comparar el desempeño entre K-means y K-medoides, donde se aplicaron métricas como el Método del Codo y Silhouette para determinar el número óptimo de clústers (k).
