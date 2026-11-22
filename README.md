# Práctica 03 — El Perceptrón

## Inteligencia Artificial

**Universidad:** Universidad Politécnica Salesiana  
**Carrera:** Ingeniería en Ciencias de la Computación  
**Asignatura:** Inteligencia Artificial  
**Estudiante:** Anthony Josue Basantes Aguirre  
**Herramienta:** Google Colab  
**Lenguaje:** Python

## Descripción

Esta práctica consiste en implementar un perceptrón desde cero utilizando Python, sin librerías de aprendizaje automático.

El objetivo es comprender cómo funciona la clasificación binaria mediante el entrenamiento de un modelo que aprende a separar dos clases (-1 y +1) a través de la actualización de sus pesos.

Se utiliza un conjunto de datos de 23 instancias con dos variables de entrada.

## Objetivos

- Implementar manualmente un perceptrón.
- Comprender la función de activación bipolar.
- Entrenar el modelo mediante la actualización de pesos.
- Visualizar la evolución de la frontera de decisión.
- Analizar el error durante el entrenamiento.
- Evaluar nuevas instancias.
- Comparar diferentes tasas de aprendizaje.

## Desarrollo de la práctica

La práctica está organizada en nueve fases:

1. **Exploración del Dataset:** carga, inspección y visualización de los datos.
2. **Fundamento del Perceptrón:** inicialización de pesos, función de activación y cálculo de salida.
3. **Visualización de la Frontera:** representación gráfica de la frontera inicial.
4. **Entrenamiento del Perceptrón:** implementación de la regla de aprendizaje y registro de errores y pesos.
5. **Entrenamiento con lr = 0.5:** entrenamiento y visualización de la frontera final.
6. **Predicción con Nuevas Instancias:** clasificación de tres puntos nuevos.
7. **Evolución de la Frontera:** visualización de los cambios durante el entrenamiento.
8. **Evolución del Error:** análisis gráfico del error por época.
9. **Comparación de Tasas:** entrenamiento con tasas de aprendizaje de 0.3, 0.5 y 0.8.

## Tecnologías utilizadas

- Python
- Google Colab
- Matplotlib
- Librería estándar `random`

## Archivo principal

`Practica_03_El_Perceptron.ipynb`

El notebook contiene el código, las gráficas, las respuestas a las preguntas guía y los análisis correspondientes a cada fase.

## Ejecución

1. Abrir el archivo `.ipynb` en Google Colab.
2. Seleccionar **Entorno de ejecución → Ejecutar todas**.
3. Revisar los resultados y las gráficas generadas.

## Conclusión

Esta práctica permite comprender el funcionamiento del perceptrón como clasificador lineal, desde la inicialización de los pesos hasta su entrenamiento y evaluación.

Además, permite analizar cómo influyen las tasas de aprendizaje en la actualización de los pesos, la evolución del error y la frontera de decisión.
