# Análisis y Predicción de Precios de Vehículos BMW

![BMW Logo](https://img.shields.io/badge/BMW-0066B2?style=for-the-badge&logo=bmw&logoColor=white)

Este proyecto realiza un análisis exploratorio de datos (EDA) y desarrolla un modelo de Machine Learning para predecir el precio de vehículos BMW de segunda mano basándose en sus características.

## 📄 Descripción del Proyecto

El objetivo es entender qué factores (como el kilometraje, el año, el tipo de motor o el modelo) influyen más en el precio de un coche BMW. El análisis culmina con la implementación y evaluación de un modelo de regresión para estimar precios.

El análisis completo y el desarrollo del modelo se encuentran en el Jupyter Notebook: `analisis_precios_bmw.ipynb`.

##  datasets

El dataset utilizado es `bmw_pricing.csv`, que contiene información sobre varios modelos de BMW, incluyendo:
* `mileage`: Kilometraje del vehículo.
* `engine_power`: Potencia del motor.
* `fuel_type`: Tipo de combustible.
* `year`: Año de fabricación.
* `price`: Precio del vehículo (nuestra variable objetivo).
* ...y otras características.

## 🛠️ Tecnologías Utilizadas

* **Python 3**
* **Pandas:** Para la manipulación y análisis de datos.
* **NumPy:** Para operaciones numéricas.
* **Matplotlib & Seaborn:** Para la visualización de datos.
* **Scikit-learn:** Para el preprocesamiento de datos y la creación del modelo de Machine Learning.


## 📈 Resultados

El análisis reveló una fuerte correlación negativa entre el precio y el kilometraje, y una correlación positiva con el año de fabricación.
