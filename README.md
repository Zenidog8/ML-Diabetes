# Predicción de Diabetes con Machine Learning

Este repositorio contiene el desarrollo del proyecto final del curso de Aprendizaje Automático, donde se aplica un enfoque supervisado para predecir la probabilidad de que un paciente tenga diabetes, utilizando un conjunto de datos médicos y técnicas de regresión.

## Contexto

La diabetes mellitus es una enfermedad crónica que afecta la forma en que el cuerpo convierte los alimentos en energía. El modelo desarrollado en este proyecto busca predecir si un paciente tiene diabetes a partir de atributos clínicos como nivel de glucosa, presión arterial, masa corporal, entre otros.

El uso de modelos de machine learning en el diagnóstico temprano puede facilitar intervenciones oportunas, lo que puede reducir significativamente los costos en salud pública y mejorar la calidad de vida de los pacientes.

## Algoritmos utilizados

Se implementaron y compararon los siguientes modelos de regresión:

- Regresión Lineal
- Soporte Vectorial (SVR)
- XGBoost Regressor

## Dataset

El [dataset](diabetes.csv) utilizado proviene de fuentes públicas relacionadas con estudios clínicos sobre diabetes. Las variables incluyen:

- Glucosa
- Presión arterial
- Índice de masa corporal (IMC)
- Edad
- Número de embarazos
- Nivel de insulina, entre otros

## Preprocesamiento

- Imputación de valores faltantes con la mediana
- Escalamiento de variables numéricas
- División del dataset en conjunto de entrenamiento y prueba
- Validación cruzada y ajuste de hiperparámetros

## Evaluación de Modelos

Los modelos fueron evaluados usando métricas como:

- Error Absoluto Medio (MAE)
- Error Cuadrático Medio (MSE)
- Coeficiente de Determinación (R²)
- Matriz de confusión para clasificación binaria tras umbralización

## Uso

Se puede ejecutar el notebook directamente desde Google Colab o Jupyter.
