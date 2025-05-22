# Bootcamp de Prompt Engineering

## 📘 Descripción

Este repositorio contiene materiales de apoyo y herramientas prácticas relacionadas con el **Prompt Engineering** y el uso de **Modelos de Lenguaje de Gran Escala (LLMs)**.

Está basado en el contenido impartido por **Lesly Zerna**, Google Developer Expert en Inteligencia Artificial.

El objetivo principal es comprender cómo interactuar con modelos de lenguaje utilizando técnicas efectivas de prompting, así como explorar capacidades avanzadas como generación de código, interacción multimodal y personalización de modelos mediante Fine-Tuning y RAG (Retrieval-Augmented Generation).

---

## 🧠 Temas Principales

### 1. Introducción a los LLMs y el Arte del Prompting
- Qué es un LLM y cómo funciona.
- Fundamentos del prompting:  
  - **Zero-shot prompting**
  - **Few-shot prompting**
  - **Chain-of-Thought (CoT)**
- Comprensión de tokens, embeddings y generación de texto.

### 2. Modelos LLM Multimodales
- Modelos capaces de procesar **texto, imágenes y audio**.
- Ejemplos de uso con Gemini:
  - Descripción de imágenes.
  - Transcripción de audio.
  - Análisis de sentimiento.
- Consideraciones sobre parámetros como temperatura y modelo.

### 3. Generación de Código y Hugging Face
- Cómo generar y explicar código a través de prompts.
- Uso de la librería **Transformers** de Hugging Face.
- Ventajas y desafíos del uso de LLMs para programación:
  - Ahorro de tiempo
  - Automatización de tareas
  - Riesgos como alucinaciones o generación de código inseguro

### 4. Fine-Tuning y RAG (Retrieval-Augmented Generation)
- Personalización de modelos LLM con datos específicos.
- Diferencias entre **Fine-Tuning** y **RAG**:
  - Fine-Tuning: entrenamiento adicional del modelo.
  - RAG: recuperación de información relevante desde fuentes externas sin modificar el modelo base.
- Casos de uso, ventajas y desventajas de cada enfoque.

---

## 🧰 Dependencias y versiones

Este proyecto utiliza las siguientes versiones de Python y bibliotecas:

```toml
python = ">=3.11.11,<3.13"
google-generativeai = "^0.8.5"
google-genai = "^1.16.1"
googletrans = "^4.0.2"
transformers = "^4.52.3"
sacremoses = "^0.1.1"
pillow = "^11.2.1"
requests = "^2.32.3"
sentencepiece = "^0.2.0"
torch = "^2.7.0"
ipywidgets = "^8.1.7"
litellm = "1.68.0"
crewai = "^0.121.0"