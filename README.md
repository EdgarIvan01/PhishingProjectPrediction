# Detector de Phishing Basado en URLs Utilizando Naive Bayes

## Introducción

El phishing es una amenaza significativa en la seguridad en línea, donde atacantes utilizan URLs engañosas para obtener información confidencial de los usuarios. Este proyecto se centra en desarrollar un detector de phishing basado en características de las URLs, utilizando el algoritmo de Naive Bayes (NB).

## Objetivo

El objetivo principal es diseñar y evaluar un modelo de clasificación que identifique URLs de phishing con alta precisión y bajo número de falsos positivos. Para ello, nos enfocamos en:

1. **Extracción de Características:** Longitud de la URL, caracteres especiales, subdominios, uso de HTTPS, entre otros.
2. **Entrenamiento del Modelo:** Uso de un conjunto de datos etiquetados para entrenar el modelo NB.
3. **Evaluación del Modelo:** Medición del rendimiento con métricas como precisión, recall, F1-score y tasa de falsos positivos.

## Metodología

1. **Recopilación de Datos:** URLs legítimas y de phishing.
2. **Preprocesamiento:** Limpieza y extracción de características de las URLs.
3. **Entrenamiento y Evaluación:** Implementación del algoritmo NB y validación cruzada del modelo.
4. **Optimización:** Ajuste de parámetros para mejorar el rendimiento.

## Estructura del Documento

1. **Revisión de Literatura:** Métodos existentes en la detección de phishing.
2. **Descripción del Conjunto de Datos:** Detalles sobre la recopilación y características del conjunto de datos.
3. **Metodología:** Pasos en la implementación y evaluación del modelo.
4. **Resultados:** Análisis de los resultados obtenidos.
