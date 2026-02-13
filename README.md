# Clasificación de Fashion MNIST con Autoencoders y Transfer Learning

Este proyecto implementa un flujo de trabajo de aprendizaje profundo para la clasificación de prendas de vestir utilizando la arquitectura de Autoencoders.

## Estructura del Proyecto
* **Etapa 1 (Autoencoder)**: Entrenamiento de un modelo para reducir la dimensionalidad de las imágenes (28x28) a un vector latente de 64 dimensiones.
* **Etapa 2 (Transfer Learning)**: Uso del Encoder pre-entrenado con capas congeladas para entrenar un clasificador final de 10 categorías.

## Archivos Principales
* `PARTE1.ipynb`: Preprocesamiento y entrenamiento del Autoencoder.
* `PARTE2.ipynb`: Construcción del clasificador y evaluación del modelo.
* `*.keras`: Modelos exportados en formato nativo de Keras.
