# Supervivencia en el Titanic con Machine Learning

Este proyecto tiene como objetivo utilizar técnicas de Machine Learning para predecir si un pasajero del Titanic sobrevivió o no al desastre. Se utilizará un conjunto de datos históricos que contiene información sobre los pasajeros, como su edad, género, clase de boleto, entre otros, para entrenar varios modelos de clasificación supervisada.

## Requisitos

Para ejecutar el proyecto, necesitarás tener instaladas las siguientes bibliotecas de Python:

pandas
numpy
scikit-learn
matplotlib
seaborn

## Instalación
No se requiere ninguna instalación especial para utilizar este proyecto.

## Uso
Para utilizar el proyecto, simplemente ejecuta todas las celdas del archivo principal ML.ipynb. Este archivo cargará el conjunto de datos, realizará la preprocesamiento de los datos, entrenará varios modelos de clasificación (como Regresión Logística, Random Forest y SVM) y evaluará su rendimiento utilizando la validación cruzada.

## Conjunto de Datos
El conjunto de datos utilizado en este proyecto se encuentra en la carpeta titanic y en dos archivos (train.csv y test.csv) uno para entrenar y otro para testear el modelo. 
El mismo contiene información sobre los pasajeros del Titanic, incluidos detalles como la edad, el género, la clase de boleto, el número de hermanos/cónyuge a bordo, el número de padres/hijos a bordo, el costo del boleto, etc.

## Estructura del Proyecto
El proyecto está organizado de la siguiente manera:

- ML.ipynb: Archivo principal que carga y procesa los datos, entrena los modelos y evalúa su rendimiento.
- EDA.ipynb: Archivo que contiene el analisis exploratorio de los datos para tener una mejor idea de como abordar los datos y el entrenamiento.
- README.md: Documento que describe el proyecto y su funcionamiento.
- train.csv: Archivo que contiene los datos historicos de los pasajeros para el entrenamiento del modelo, es decir que tiene su variable objetivo.
- test.csv: Archivo que contiene los datos historicos de los pasajeros para el test del modelo, es decir que NO contiene su variable objetivo

## Créditos
El conjunto de datos del Titanic fue obtenido del sitio web Kaggle.
