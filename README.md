# 💬 NLP: INTRODUCCIÓN A LOS MODELOS DE LENGUAJE Y EXPRESIONES REGULARES

[![NLP](https://img.shields.io/badge/NLP-4285F4?style=flat&logo=TensorFlow&logoColor=white)](https://es.wikipedia.org/wiki/Procesamiento_de_lenguaje_natural)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white)](https://www.python.org/)
[![Detección de Idiomas](https://img.shields.io/badge/Modelo%20de%20Lenguaje-0099D8?style=flat&logo=Google%20Translate&logoColor=white)](https://es.wikipedia.org/wiki/Modelo_de_lenguaje)

Este proyecto es una introducción avanzada al **Procesamiento de Lenguaje Natural (NLP)**, centrado en el desarrollo de un **Modelo de Lenguaje** con la finalidad de realizar la **Detección de Idiomas**. El notebook profundiza en los desafíos matemáticos de la construcción de modelos, como el problema de la Perplejidad Infinita, y cómo resolverlos mediante técnicas de suavizado.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Conceptos Fundamentales de NLP
- **Introducción:** Se explora el concepto de **NLP** como el puente de comunicación entre el lenguaje humano y el lenguaje de máquina.
- **Modelos de Lenguaje:** Se define el concepto de **Modelo de Lenguaje**, tomando como ejemplo práctico un detector de idiomas (similar al Traductor de Google).

### 2️⃣ Datos y Desafíos Matemáticos
- **Dataset:** Se trabaja con un conjunto de datos de preguntas de **Stack Overflow** en tres idiomas: **Español, Portugués e Inglés**.
- **Perplejidad:** Se introduce la **perplejidad** como un indicador clave para validar la corrección del modelo de lenguaje.
- **Suavizado de Laplace:** Se aborda el problema de la **perplejidad infinita** causada por la probabilidad cero y se implementa la técnica de suavizado de **Laplace** para mitigar este desafío.

### 3️⃣ Expresiones Regulares
- **Aplicación:** Aunque no se detalla en el *snippet*, el título del cuaderno indica el uso de **Expresiones Regulares** para el procesamiento y limpieza avanzada de los datos textuales.

---

## 🛠️ Librerías Utilizadas

| Librería | Uso principal |
|:---:|:---:|
| **Pandas** | Carga, manipulación y preparación del conjunto de datos. |
| **`re` (Módulo de Python)** | Implementación de **Expresiones Regulares** para el preprocesamiento de texto (implícito por el título). |
| **Módulos de NLP** | Creación de las estructuras de datos y funciones para implementar la lógica del modelo de lenguaje y el cálculo de la perplejidad. |

---

## 🎯 Objetivo del Proyecto

El objetivo principal es **crear y entrenar un Modelo de Lenguaje** capaz de identificar y clasificar un texto según el idioma en el que fue escrito (**Detección de Idiomas**).

Objetivos secundarios incluyen:
- Entender el concepto y la importancia de la **perplejidad** como métrica de evaluación.
- Demostrar cómo el suavizado de **Laplace** resuelve el problema de las probabilidades cero y la perplejidad infinita en modelos basados en **Máxima Verosimilitud (MLE)**.

---

## 📈 Resultados Clave

- **Modelo de Detección de Idiomas Operacional:** Se consiguió entrenar un modelo funcional capaz de clasificar textos en tres idiomas (Español, Portugués e Inglés).
- **Alta Precisión (*Accuracy*):** El modelo final demostró una **precisión (*accuracy*) del 97% o superior** en el conjunto de datos de prueba (100 preguntas), con solo tres errores de clasificación.
- **Solución del Desafío de Perplejidad:** Se implementó exitosamente el suavizado de **Laplace** para evitar la perplejidad infinita, asegurando que el entrenamiento y la validación del modelo se pudieran completar de manera correcta.
