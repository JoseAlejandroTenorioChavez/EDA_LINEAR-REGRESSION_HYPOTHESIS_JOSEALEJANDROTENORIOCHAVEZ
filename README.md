# EDA_LINEAR-REGRESSION_HYPOTHESIS_JOSEALEJANDROTENORIOCHAVEZ

# Descripción
Este proyecto implica la exploración, limpieza y análisis de un conjunto de datos de envíos, con el objetivo final de construir un modelo de regresión lineal para predecir el costo del seguro del envío (line_item_insurance_usd).

# Conjunto de Datos
El conjunto de datos incluye información sobre envíos individuales, como el método de envío (shipment_mode), si la entrega fue tardía (late_delivery), y el costo del seguro del envío (line_item_insurance_usd).

# Dependencias
Python

pandas

numpy

matplotlib

seaborn

scikit-learn

.

# Limpieza y Preprocesamiento de Datos
Luego, limpiamos y preprocesamos los datos para prepararlos para el modelado. Esto incluyó el tratamiento de valores nulos, la conversión de variables categóricas y la identificación y tratamiento de outliers.

# Construcción del Modelo
Construimos un modelo de regresión lineal utilizando las variables que estaban más correlacionadas con line_item_insurance_usd. Dividimos los datos en conjuntos de entrenamiento y prueba, entrenamos el modelo en el conjunto de entrenamiento y luego hicimos predicciones en el conjunto de prueba.

# Evaluación del Modelo
Evaluamos el rendimiento del modelo utilizando el error cuadrático medio (Mean Squared Error) y el coeficiente de determinación (R^2 Score).

# Pruebas de Hipótesis
Realizamos una prueba de hipótesis para determinar si la proporción de entregas tardías era mayor al 6%.
