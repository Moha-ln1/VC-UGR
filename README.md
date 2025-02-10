# Computer Vision Assignments (P1, P2, P3)

Este repositorio contiene las prácticas resueltas de la asignatura de **Visión por Computador** (Curso 2024/2025). 
A continuación, se presenta un resumen de cada una de las prácticas:

---

## Práctica 1: Procesamiento de Imágenes

### Objetivos
- Aprender a implementar filtros de convolución y, en particular, el cálculo de derivadas de una imagen.
- Mostrar cómo, utilizando técnicas de filtrado lineal, es posible extraer información relevante de una imagen para permitir su interpretación.

### Ejercicios
1. **Cálculo de máscaras 1D**: Implementación de máscaras Gaussianas y sus derivadas.
2. **Convoluciones 2D**: Uso de convoluciones separables para aplicar filtros Gaussianos y derivados.
3. **Cálculo del gradiente y Laplaciano**: Implementación del gradiente y Laplaciano de una imagen.
4. **Convolución manual**: Implementación de una función de convolución separable y comparación con `cv2.GaussianBlur`.

### Resultados
- Detección de bordes y detalles en imágenes utilizando filtros Gaussianos y derivados.
- Visualización del gradiente y Laplaciano de una imagen.

---

## Práctica 2: Deep Learning para Visión por Computador

### Objetivos
- Aprender a implementar redes neuronales convolucionales (CNN) utilizando **fastai** y **PyTorch**.
- Entender los conceptos de extracción de características y fine-tuning.
- Familiarizarse con conceptos básicos de **Explainable AI** (IA explicable).

### Ejercicios
1. **BaseNet en CIFAR100**: Creación y entrenamiento de una red neuronal simple (BaseNet) en el conjunto de datos CIFAR100.
2. **Mejora de BaseNet**: Mejora de la red BaseNet utilizando técnicas como aumento de datos, normalización por lotes, regularización y early-stopping.
3. **Transferencia de aprendizaje con ResNet50**: Fine-tuning de ResNet50 para la predicción de edad a partir de radiografías (SPR X-Ray Age Prediction Challenge).
4. **Explainable AI con Grad-CAM**: Visualización de las regiones de la imagen que son relevantes para la predicción utilizando Grad-CAM.

### Resultados
- Entrenamiento y mejora de redes neuronales convolucionales.
- Aplicación de transferencia de aprendizaje y fine-tuning en problemas de clasificación y regresión.
- Visualización de las regiones de interés en imágenes utilizando Grad-CAM.

---

## Práctica 3: Extracción de Características y Composición de Mosaicos

### Objetivos
- Aprender a detectar regiones relevantes en imágenes utilizando el algoritmo de detección de esquinas de Harris.
- Encontrar correspondencias entre imágenes utilizando descriptores como SIFT, HOG y LBP.
- Crear un mosaico o panorama a partir de un conjunto de imágenes superpuestas.

### Ejercicios
1. **Detección de puntos clave con Harris**: Implementación del detector de esquinas de Harris para identificar puntos clave en una imagen.
2. **Emparejamiento de descriptores**: Uso de descriptores SIFT, HOG y LBP para encontrar correspondencias entre imágenes.
3. **Composición de mosaicos**: Estimación de homografías y creación de un panorama a partir de imágenes superpuestas.

### Resultados
- Detección de puntos clave en imágenes utilizando el detector de Harris.
- Emparejamiento de descriptores entre imágenes utilizando diferentes métodos.
- Creación de un mosaico o panorama a partir de un conjunto de imágenes superpuestas.

---

## Requisitos

- **Python**: El código está escrito en Python.
- **OpenCV**: Utilizado para el procesamiento de imágenes en las prácticas 1 y 3.
- **PyTorch y fastai**: Utilizados para la implementación de redes neuronales en la práctica 2.
- **Dependencias**: Instala las dependencias necesarias con `pip install -r requirements.txt`.

