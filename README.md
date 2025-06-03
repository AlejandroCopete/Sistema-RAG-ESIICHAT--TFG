# Sistema RAG – ESIIChat (TFG)

Este repositorio contiene el código desarrollado como parte del Trabajo de Fin de Grado (TFG) en Ingeniería Informática, centrado en la creación de un sistema RAG (Retrieval-Augmented Generation) aplicado a un chatbot académico denominado **ESIIChat**, diseñado específicamente para la Escuela Superior de Ingeniería Informática (ESII).

## Descripción del proyecto

El objetivo del proyecto es implementar un sistema inteligente capaz de responder preguntas relacionadas con el plan de estudios y el profesorado de la ESII, integrando recuperación de información relevante y generación de respuestas naturales mediante un modelo de lenguaje.

Para ello, se ha utilizado la biblioteca **[Unsloth](https://github.com/unslothai/unsloth)**, que permite la carga eficiente de modelos LLM optimizados mediante cuantización a 4 bits, reduciendo considerablemente los recursos necesarios para la inferencia.

## Características principales

- Sistema RAG completo (recuperación + generación)
- Chatbot temático para información académica
- Modelos LLM cuantizados con Unsloth
- Prototipo web básico (HTML, CSS, JS) para visualización
- Procesamiento de cualquier PDF dado su ruta

## Entorno de ejecución

Este código ha sido diseñado para su ejecución en **Google Colab**, e incluye los comandos necesarios (`pip install`) para instalar todas las dependencias requeridas en el propio entorno.

## Estructura del repositorio

Sistema-RAG-ESIICHAT--TFG/
    colab_notebook.ipynb # Notebook principal con todo el sistema RAG
    docs/ # Documentos usados (PDF y JSON)
    web_app/ # Prototipo HTML/CSS/JS para testeo
    utils/ # Funciones auxiliares para procesamiento
    README.md # Este archivo
    LICENSE # Licencia del proyecto

markdown
Copiar
Editar

## Requisitos

- Entorno: Google Colab (recomendado)
- Python 3.10+
- Dependencias principales:
  - `unsloth`
  - `transformers`
  - `langchain`
  - `faiss-cpu`
  - `pypdf`
  - `chromadb`

> Todas las dependencias se instalan automáticamente en el notebook mediante `pip`.

## Licencia

Este proyecto se distribuye bajo la **Licencia Apache 2.0**. Consulta el archivo [`LICENSE`](./LICENSE) para más detalles.

## Enlace al proyecto

📂 Repositorio público del TFG:  
[https://github.com/AlejandroCopete/Sistema-RAG-ESIICHAT--TFG](https://github.com/AlejandroCopete/Sistema-RAG-ESIICHAT--TFG)
