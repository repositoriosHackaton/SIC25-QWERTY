# Tabla de contenidos

1. [Nombre](#Nombre)
2. [Descripción](#descripción)
3. [Arquitectura](#Arquitectura)
4. [Proceso](#Proceso)
5. [Funcionalidades](#Funcionalidades)
6. [Estado del proyecto](#EstadoDelProyecto)
7. [Agradecimientos](#Agradecimientos)


* Nombre del proyecto: Predicción de la Masa Invariante en una colision de dos electrones

* Breve descripción del proyecto

Este proyecto utiliza técnicas de machine learning para predecir la masa invariante resultante de colisiones de dos electrones utilizando datos del CERN. El dataset incluye características relacionadas con la energía, el momento, la pseudorapidez, el ángulo phi y otras variables derivadas del evento de colisión. Se aplicaron modelos como LightGBM, XGBoost y CatBoost para entrenar el sistema y evaluar su desempeño en la predicción de la masa invariante.

![alt text](1.jpg)

* Arquitectura del proyecto

![alt text](2.jpg)

* Proceso de desarrollo:

Proceso de desarrollo: Preprocesamiento -> Ingeniería de Características -> Escalado -> Modelo en sí.

La unidad de preprocesamiento incluirá los siguientes pasos: selección de características -> eliminación/imputación de valores atípicos.

La unidad de ingeniería de características realizará la creación de características para mejorar el rendimiento del modelo.

La unidad de escalado se utilizará para estandarizar todos los datos numéricos antes de pasarlos al modelo.

Finalmente, la unidad del modelo simplemente contendrá el algoritmo de aprendizaje automático con el que realizaremos las predicciones.

-Fuente del dataset https://www.kaggle.com/datasets/fedesoriano/cern-electron-collision-data

-Limpieza de datos (img que lo valide)

Visualizacion de limpieza.

![alt text](3.jpg)


-Manejo excepciones/control errores

Visualizacion de columnas duplicadas.

![alt text](4.jpg)

Manejo de columnas duplicadas.

![alt text](5.jpg)

-Estadísticos (Valores, gráficos, …)

Distribucion de la masa invariante. Se pueden observas unos picos que corresponden a energias de particulas fundamentales.

![alt text](6.jpg)

* Funcionalidades extra:

Integración del proyecto en una pág web

Luego de obtener los resultados esperados con los modelos utilizados y entrenado en el proyecto, se desarrolló una página con el fin de presentar los conocimientos utilizados, herramientas así como las bases teóricas y conceptuales con el fin de presentar de forma dinámica el trabajo realizado.

- Tecnología/Herramientas usadas

HTML: para desarrollo web 
CSS: estilo y dinámica del sitio

Se aplicaron lenguajes de programación sencillos para la construcción de la página así como el framework Bootstrap con el fin de agilizar el trabajo.

- Arquitectura

![alt text](7.jpg)

