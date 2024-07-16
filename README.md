# Clasificación de Flores con EfficientNetV2

Este proyecto demuestra cómo entrenar un clasificador de imágenes de flores utilizando TensorFlow y TensorFlow Hub con EfficientNetV2, una arquitectura avanzada de redes neuronales convolucionales. El modelo se entrena en un conjunto de datos de flores públicamente disponible y se evalúa en términos de precisión y pérdida.

## Visión General

El proyecto utiliza Google Colab para el entrenamiento en la nube, aprovechando los recursos de GPU para acelerar el entrenamiento del modelo. TensorFlow Hub proporciona acceso a modelos preentrenados como EfficientNetV2, que se ajusta para la clasificación de flores en este escenario.

## Configuración

Para ejecutar este proyecto, siga estos pasos:

1. Abra Google Colab y cree un nuevo cuaderno.
2. Copie los bloques de código proporcionados en celdas individuales en su cuaderno de Colab.
3. Ejecute cada celda secuencialmente para descargar el conjunto de datos, preparar los datos, construir el modelo, entrenarlo y evaluar su rendimiento.
4. Observe el progreso del entrenamiento y las métricas de validación mostradas después de cada época de entrenamiento.
5. Analice los gráficos finales de precisión y pérdida para evaluar el rendimiento del modelo.

## Estructura del Proyecto

- `flower_classification_efficientnet.ipynb`: Cuaderno Jupyter que contiene el código completo para entrenar y evaluar el modelo de clasificación de flores.
- `README.md`: Este archivo, proporcionando una descripción general del proyecto, instrucciones de configuración y pautas de uso.

## Dependencias

- TensorFlow
- TensorFlow Hub
- Matplotlib
- NumPy

## Resultados

El modelo logra una precisión competitiva en la clasificación de imágenes de flores después de unas pocas épocas de entrenamiento. Consulte los gráficos de precisión y pérdida en el cuaderno para obtener métricas detalladas de rendimiento.

## Mejoras Futuras

Las mejoras futuras podrían incluir experimentar con diferentes modelos preentrenados de TensorFlow Hub, explorar técnicas de aumento de datos y optimizar hiperparámetros para obtener un mejor rendimiento.



Siéntase libre de contribuir a este proyecto realizando mejoras o ajustes según sea necesario.

