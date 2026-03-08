# Predicción de Rotación de Empleados con Machine Learning

Este proyecto utiliza Machine Learning para predecir si un empleado abandonará la empresa, utilizando datos del área de Recursos Humanos.

## Dataset

El dataset contiene información sobre empleados como:

- Nivel de satisfacción
- Evaluación del desempeño
- Número de proyectos
- Horas mensuales trabajadas
- Años en la empresa
- Accidentes laborales
- Promociones
- Departamento
- Nivel salarial

## Modelo utilizado

Se utilizó el algoritmo **K-Nearest Neighbors (KNN)**.

Antes del entrenamiento se realizaron los siguientes pasos:

- Codificación de variables categóricas
- División de datos en entrenamiento y prueba
- Escalado de variables con StandardScaler
- Selección del valor óptimo de K

## Evaluación del modelo

Métricas obtenidas:

- Accuracy: 0.95
- AUC: 0.94

También se analizaron:

- Matriz de confusión
- Curva ROC

## Tecnologías utilizadas

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Objetivo

Demostrar el uso de técnicas de Machine Learning para analizar la rotación de empleados y apoyar la toma de decisiones en Recursos Humanos.
