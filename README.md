# Supervivencia en el Titanic con Machine Learning

Este proyecto tiene como objetivo utilizar técnicas de Machine Learning para predecir si un pasajero del Titanic sobrevivió o no al desastre. Se utilizará un conjunto de datos históricos que contiene información sobre los pasajeros, como su edad, género, clase de boleto, entre otros, para entrenar varios modelos de clasificación supervisada.

## Requisitos

Para ejecutar el proyecto, necesitarás tener instaladas las siguientes bibliotecas de Python:

- Python3
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Uso
Para utilizar el proyecto, simplemente ejecuta todas las celdas del archivo principal ML.ipynb. Este archivo cargará el conjunto de datos, realizará la preprocesamiento de los datos, entrenará varios modelos de clasificación (como Regresión Logística, Random Forest y SVM) y evaluará su rendimiento utilizando la validación cruzada.

El mismo guardara las respuestas en un archivo.csv en la carpeta en que se encuentre.

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





------------------------------------------------------------------------------------------------------------------------------------------------------------------------------





# Survival on the Titanic with Machine Learning

This project aims to use Machine Learning techniques to predict whether or not a Titanic passenger survived the disaster. A historical dataset containing information about passengers, such as their age, gender, ticket class, among others, will be used to train various supervised classification models.

## Requirements

To run the project, you will need to have the following Python libraries installed:

-Python3
- panda
-numpy
-scikit-learn
-matplotlib
- seaborn

## Use
To use the project, simply run all the cells in the main ML.ipynb file. This file will load the dataset, perform data preprocessing, train various classification models (such as Logistic Regression, Random Forest, and SVM), and evaluate their performance using cross-validation.

It will save the responses in a .csv file in the folder it is in.

## Data set
The data set used in this project is located in the titanic folder and in two files (train.csv and test.csv) one to train and the other to test the model.
It contains information about Titanic passengers, including details such as age, gender, ticket class, number of siblings/spouse on board, number of parents/children on board, ticket cost, etc.

## Project Structure
The project is organized as follows:

- ML.ipynb: Main file that loads and processes the data, trains the models and evaluates their performance.
- EDA.ipynb: File that contains the exploratory analysis of the data to have a better idea of how to approach the data and the training.
- README.md: Document that describes the project and its operation.
- train.csv: File that contains the historical data of the passengers for the training of the model, that is, it has its objective variable.
- test.csv: File that contains the historical data of the passengers for the model test, that is, it does NOT contain its objective variable

## Credits
The Titanic dataset was obtained from the Kaggle website.
