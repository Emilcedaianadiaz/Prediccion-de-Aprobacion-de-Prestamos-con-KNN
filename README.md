# Predicción de Aprobación de Préstamos con KNN

## Descripción

Este proyecto consiste en el desarrollo de un modelo de Machine Learning para predecir la aprobación o el rechazo de solicitudes de préstamos bancarios utilizando el algoritmo **K-Nearest Neighbors (KNN)**.

El objetivo fue recorrer el flujo completo de un problema de clasificación supervisada: desde la preparación del conjunto de datos hasta la evaluación del modelo.

---

## Objetivos

* Explorar un conjunto de datos de solicitudes de préstamos.
* Preparar los datos para su utilización en un algoritmo de Machine Learning.
* Entrenar un modelo de clasificación utilizando KNN.
* Comparar distintos valores del parámetro **K**.
* Evaluar el rendimiento del modelo mediante métricas de clasificación.

---

## Tecnologías utilizadas

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Dataset

Se utilizó un conjunto de datos de préstamos bancarios obtenido desde Kaggle, que contiene información sobre los solicitantes, incluyendo variables demográficas, económicas y crediticias.

Algunas de las variables utilizadas fueron:

* Edad
* Ingresos
* Nivel educativo
* Experiencia laboral
* Tipo de vivienda
* Historial crediticio
* Estado del préstamo (variable objetivo)

---

## Desarrollo del proyecto

El trabajo se realizó siguiendo las siguientes etapas:

### 1. Carga del dataset

Se descargó y cargó el conjunto de datos para comenzar el análisis.

### 2. Exploración de los datos

Se revisó la estructura del dataset, los tipos de variables y la distribución de la variable objetivo.

### 3. Preparación de los datos

Las variables categóricas fueron transformadas a formato numérico para permitir el entrenamiento del modelo.

### 4. Visualización

Se realizaron gráficos exploratorios para observar el comportamiento de algunas variables y su relación con la aprobación de préstamos.

### 5. División del dataset

Los datos se separaron en conjuntos de entrenamiento y prueba utilizando `train_test_split`.

### 6. Entrenamiento del modelo

Se implementó un clasificador **K-Nearest Neighbors**, evaluando distintos valores de **K** para comparar su rendimiento.

### 7. Evaluación

El desempeño del modelo se analizó mediante:

* Accuracy
* Matriz de confusión

---

## Resultados

Después de evaluar distintas configuraciones, el mejor desempeño se obtuvo utilizando:

* **K = 15**
* **Accuracy: 83,37%**

La matriz de confusión permitió analizar el comportamiento del modelo frente a cada clase y detectar los tipos de errores más frecuentes durante la clasificación.

---

## Aprendizajes

Este proyecto permitió reforzar conceptos relacionados con:

* Clasificación supervisada.
* Preparación y transformación de datos.
* Entrenamiento de modelos con Scikit-learn.
* Selección de hiperparámetros.
* Evaluación de modelos mediante métricas de clasificación.
* Interpretación de resultados para apoyar la toma de decisiones.

Proyecto desarrollado como práctica de Machine Learning para fortalecer conocimientos en Ciencia de Datos utilizando Python y Scikit-learn.
