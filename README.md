# Spark Movie Recommendation

Este proyecto implementa un sistema de recomendación de películas utilizando Apache Spark y su biblioteca de aprendizaje automático (MLlib).

## Clona el repositorio en tu máquina local

git clone <url_del_repositorio>

## Configuración del entorno:

Asegúrate de tener instalado Apache Spark en tu máquina.
Coloca los archivos movies.csv y ratings.csv en tu carpeta principal.

## Link de base de datos usada

https://grouplens.org/datasets/movielens/latest/

## Ejecución del código:
Abre el archivo movie_recommender.ipynb en Jupyter Notebook o en tu entorno preferido para ejecutar código Python.
Ejecuta las celdas del notebook en orden para cargar los datos, entrenar el modelo y obtener las recomendaciones para los usuarios.

## Desafíos Enfrentados
Durante el desarrollo de este proyecto, se enfrentaron los siguientes desafíos:

- Manejo de grandes volúmenes de datos: La escalabilidad de Spark y su capacidad para procesar grandes volúmenes de datos fue un desafío importante, especialmente al trabajar con conjuntos de datos de películas y calificaciones extensos.

- Optimización de hiperparámetros: Ajustar los hiperparámetros del modelo ALS, como el número de factores latentes y el número de iteraciones, fue un desafío para obtener un buen rendimiento del modelo y evitar el sobreajuste.

- Interpretación de los resultados: Entender y evaluar las recomendaciones generadas por el modelo requirió un análisis cuidadoso de las métricas de evaluación y la interpretación de los datos de películas y calificaciones.

## Hallazgos y Perspectivas Interesantes
Durante el desarrollo y evaluación del sistema de recomendación de películas, se obtuvieron los siguientes hallazgos y perspectivas interesantes:

- La evaluacion del modelo nos lanzo un resultado de 1.24 usando RMSE, es un puntaje aceptable, pero se tendria que trabajar mas en mejorarlo. Ya que aun hay un margeb de error

- El modelo ALS demostró ser efectivo para generar recomendaciones personalizadas en base a las preferencias de los usuarios, utilizando la información de calificaciones de películas existentes.

- La elección adecuada de hiperparámetros y la optimización del modelo pueden tener un impacto significativo en la calidad de las recomendaciones generadas. Es importante experimentar con diferentes configuraciones para obtener el mejor rendimiento.

- El uso de técnicas de preprocesamiento de datos, como la eliminación de valores atípicos o la normalización de las calificaciones, puede mejorar la precisión del modelo y la calidad de las recomendaciones.
