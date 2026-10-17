
# Semana 8 — Algoritmos de clasificación

**Autora:** Sandra Yurani Ayala Herrera  
**Institución:** Universidad de Cundinamarca  
**Asignatura:** Introducción a Machine Learning — CADI

## Descripción del proyecto

Este proyecto implementa y compara cinco algoritmos de clasificación supervisada utilizando Python, Pandas y Scikit-learn, sobre el conjunto de datos Breast Cancer Wisconsin Diagnostic.

## Algoritmos implementados

- Decision Tree (Árbol de Decisión)
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (K-NN)
- Naive Bayes (GaussianNB)

## Metodología

Se utiliza una partición común de los datos: 80 % para entrenamiento y 20 % para prueba, con `random_state=42` y `stratify=y`.

Los modelos se evalúan mediante las métricas Accuracy, Precision, Recall, F1-score y matrices de confusión. Para SVM y K-NN se aplica estandarización de las variables.

## Resultados principales

Random Forest y SVM obtuvieron los mejores resultados en la partición de prueba, con Accuracy de 97,37 %, Precision de 100 %, Recall de 92,86 % y F1-score de 96,30 %.

Ambos modelos registraron tres falsos negativos y ningún falso positivo. La selección es provisional y corresponde exclusivamente a esta evaluación.

## Archivos del proyecto

- `Semana8_Algoritmos_Clasificacion_SandraYuraniAyalaHerrera.ipynb`: notebook con el código, las métricas y las interpretaciones.
- `README.md`: descripción y documentación del proyecto.

## Fuente de datos

Breast Cancer Wisconsin Diagnostic, disponible mediante `sklearn.datasets.load_breast_cancer`.

## Alcance académico

Este ejercicio tiene fines académicos. Los resultados no constituyen una herramienta de diagnóstico clínico.
