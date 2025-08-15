# **TELECOM X Parte 2**

## Descripción

Este proyecto tiene como objetivo predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones, utilizando técnicas de Machine Learning y análisis exploratorio de datos.
Se parte de un dataset con información demográfica, de uso y de facturación de los clientes, para identificar patrones y variables clave que influyen en la probabilidad de cancelación.


## Flujo de Trabajo

  * Carga y Limpieza de Datos
  * Eliminación de columnas irrelevantes o redundantes.
  * Tratamiento de valores nulos y codificación de variables categóricas.
  * Análisis Exploratorio (EDA)
  * Análisis de correlación.
  * Distribución de variables y detección de patrones.
  * Identificación de posibles desbalances de clases.
  * Preparación de Datos
  * Codificación One-Hot Encoding.
  * Escalado de variables numéricas.
  * División de datos en entrenamiento y prueba.
  * Modelado
  * Entrenamiento de modelos como:
    * Naive Bayes
    * Regresión Logística
  * Validación cruzada.
  * Optimización de hiperparámetros
  
## Evaluación

  * Métricas: accuracy, precision, recall, f1-score.
  * Selección del modelo basado en recall para priorizar la detección de cancelaciones reales.
  * Análisis de Importancia de Variables
  * Identificación de las características más relevantes para la predicción.
  * Recomendaciones estratégicas para reducir la tasa de churn.

## Resultados

El modelo con mejor rendimiento fue Regresión Logística, obteniendo un balance entre recall y precisión.
Las variables más influyentes fueron:

  * tenure
  * Contract
  * MonthlyCharges
  * PaymentMethod
