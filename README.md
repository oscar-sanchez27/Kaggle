# KAGGLE 2021-2022 APC
[Este es un resumen del kaggle, el trabajo completo se encuentra en la carpeta notebook] 
### Nom: Óscar Sánchez Lima
### Niu: 1527377  
### URL DATASET: https://www.kaggle.com/purumalgi/music-genre-classification

## Resum
La base de datos en la que nos centraremos en este proyecto, se basa en datso especificos relacionados con el tema musical. En el dataset podemos ver 16 atributos, que són: el nombre del artista, track name, Popularity, danceability,	energy,	key,	loudness,	mode,	speechiness,	acousticness,	instrumentalness,	liveness,	valence,	tempo,	duration_in min/ms,	time_signature,	Class. De todos estos atributos el atributo objetivo es el atributo 'Class' que nos indica a que genero musical pertenece cada artista. 

## Objetivo
El objetivo de esta practica es hacer la predicción mediante la Regresión Logística y ver cual es el mejor metodo para clasificar.

## Experiments
Durante el desarrollo de esta práctica he hecho la implementación de la Regresión Logística y con la ayuda de la libreria pycaret he analizado todos los modelos para poder escoger el más óptimo. 

## Conslusion
Con la libreria pycaret me ha ayudado para poder analizar todos los modelos. Una vez hemos sacado todos los datos de cada uno de los modelos, la accuracy, recall, precision, he observado que el modelo más eficiente de todos es el Gradient Boosting. 
![image](https://user-images.githubusercontent.com/65301069/149672412-3aeb37e7-e180-4c6c-9185-00838706b06a.png)

Como conclusion, he podido observar como el modelo más optimo para clasificar nuestra base de datos ha sido Gradient Boosting Classifier con un Accuracy de 0.5381.A parte de tener el accuracy más óptimo, también da mejores resultados en precision o en recall. A parte de este modelo, también podemos ver otros como el Random Forest que seria el tercer clasificador más eficiente. 
Como trabajos futuros podemos implementar diferentes modelos de clasificacion, asi como otra formas de predicción. 

