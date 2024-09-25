# price-airbnb-predictive-model

Este proyecto tiene como objetivo desarrollar un modelo predictivo que estime los precios por noche de los alojamientos turísticos disponibles en Airbnb en la ciudad de Barcelona. La predicción precisa de precios es esencial tanto para los anfitriones que desean optimizar sus ingresos como para los potenciales huéspedes que buscan opciones de alojamiento adecuadas a su presupuesto. Utilizando técnicas de análisis de datos y ciencia de datos, implementaremos un pipeline completo en Python con Jupyter Lab, donde abordaremos la limpieza, el análisis y la modelización de datos.

Etapas del Proyecto:

- Recolección y Exploración de Datos: Utilizaremos datasets públicos de Airbnb que incluyen información detallada sobre los alojamientos en Barcelona, como características del inmueble.
- Limpieza de Datos: Para asegurar la calidad de los datos, realizaremos una serie de pasos de preprocesamiento que incluyen: Manejo de valores nulos, estandarización de variables categóricas y numéricas, tratamiento de outliers que puedan sesgar el modelo, transformación de variables (por ejemplo, normalización de precios, conversión de fechas), análisis exploratorio de datos (EDA): Mediante técnicas de visualización y análisis estadístico, investigaremos las relaciones entre las variables independientes y el precio por noche.
- Modelización Predictiva: Para la predicción del precio, implementaremos diferentes modelos de machine learning supervisado como: Random Forest y Regresión Lineal. Evaluaremos el rendimiento de cada modelo utilizando métricas como el error cuadrático medio (RMSE) y la R² (coeficiente de determinación). Además, realizaremos ajuste de hiperparámetros para mejorar la precisión del modelo.
- Validación del Modelo: Utilizaremos técnicas de validación cruzada para evaluar la generalización de los modelos y prevenir el sobreajuste. Además, se analizará la importancia de las variables en la predicción final para entender qué factores tienen un mayor impacto en la estimación del precio.

Herramientas Utilizadas:

- Lenguaje: Python
- Entorno: Jupyter Lab
- Librerías de Análisis y Manipulación de Datos: Pandas, NumPy
- Librerías de Visualización: Matplotlib, Seaborn, Plotly
- Modelos de Machine Learning: Scikit-learn, XGBoost
- Validación y Ajuste de Modelos: GridSearchCV, Cross-validation
