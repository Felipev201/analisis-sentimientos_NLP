# Actividad integradora 1 NLP

Esta actividad expande el analizador de sentimientos de twitter.

## Nuevos datos de entrenamiento
Se buscó en Kaggle datos etiquetados para realizar el entrenamiento de un analizador de sentimientos. Los datos son tweets que estan calificados como positivos o negativos basados en su contenido. Los datos fueron tomados de [Sentiment140 dataset with 1.6 million tweets](https://www.kaggle.com/kazanova/sentiment140).

## Entrenamiento de modelos
Para poder predecir si un texto nuevo se clasifica como ositivo o negativo, se utilizaron los siguientes modelos básicos
-. Bayes Ingenuo (Multinomial y Bernoulli)
-. Regresion logística
-. Maquinas de ectores de soporte

Asi como algunos modelos más complejos como utilizando 3 arquitecturas de redes neuronales recurrentes ***describir las arquitecturas*** y un modelo de Representación de Codificador Bidireccional de Transformadores (BERT).

## Predicciones
Para las predicciones se realizo un scrapper de redes sociales como reddit y twitter, de esta última con la funcionalidad de poder obtener tweets por nombre de usuario, tambien se añadió la caracteristica de convertir audio a texto de archivos .wav 

## Como correr el código
Solo se necesita un ambiente que trabaje con archivos .ipynb como Jupyter notebook o Google Colab. Sin embargo si se quiere correr la parte de obtener usuarios de twitter se debe añadir un archivo .py llamado 'private.py' donde estén las claves y llaves de acceso al API de twitter. En este repositorio se pone un archivo muestra para saber como llenar las claves.

##### Contribuidores
* [Roberto]()
* [Felipe Villaseñor](https://github.com/Felipev201)
* [Esteban]
* [Jesus]()
