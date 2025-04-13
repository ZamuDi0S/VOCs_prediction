# 🌧️ Redes Neuronales Recurrentes (RNN) para Predicción Meteorológica

Aplicación de modelos de redes neuronales recurrentes (LSTM) como parte del Diplomado de Ciencia de Datos Primavera 2025.

## 📊 Descripción del Proyecto

Este proyecto utiliza modelos LSTM (Long Short-Term Memory) para predecir variables climáticas a partir de datos meteorológicos históricos de la ciudad de Seattle. El modelo es capaz de aprender dependencias temporales y realizar predicciones basadas en secuencias.

## 🗂️ Dataset

Se utiliza el dataset **`seattle_weather`** proveniente de [Vega Datasets](https://github.com/vega/vega/blob/main/docs/data/seattle-weather.csv), el cual contiene información diaria del clima en Seattle entre 2012 y 2015.

> ⚠️ Si el enlace original no está disponible, puedes usar el archivo CSV adjunto en este repositorio.

## 🧠 Tecnologías utilizadas

- Python
- TensorFlow / Keras
- scikit-learn
- pandas / numpy / matplotlib
- Google Colab
- vega_datasets

## ⚙️ Estructura del modelo

Se entrena una red LSTM para predecir una variable específica (por ejemplo, la temperatura máxima) a partir de una secuencia de datos climáticos como precipitación, viento, etc.

