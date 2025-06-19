# 📄 Survey: Generación Automática de Resúmenes con Técnicas de Deep Learning

Este repositorio contiene el artículo académico en formato LaTeX titulado **“Generación Automática de Resúmenes: Estudio y Análisis del Modelo PEGASUS”**, que analiza las técnicas más relevantes en el campo del resumen automático de textos, incluyendo bases de datos, métricas de evaluación y modelos recientes como PEGASUS.

## 📌 Contenido

- `main.tex`: Documento principal en LaTeX.
- `/figures`: Carpeta con todas las imágenes utilizadas en el artículo.
  - `pegasus (2).png`: Arquitectura del modelo PEGASUS.
  - `rouge.png`: Comparación de modelos según métricas ROUGE.
  - `vocab_vs_rouge.png`: Impacto del vocabulario en ROUGE.
  - `modelo.png`: Arquitectura SELF-MEM.
- `bibliografia.bib`: Archivo BibTeX con todas las referencias citadas en el artículo.
- `README.md`: Este archivo.

## 🧠 Temas principales

- Definición del problema de resumen automático
- Desafíos actuales en la generación de resúmenes
- Bases de datos estándar (CNN/DailyMail, XSum, PubMed, etc.)
- Métricas de evaluación (ROUGE, BLEU, Exact Match)
- Modelos basados en transformers (PEGASUS, GPT-3)
- Técnicas de atención y modelos de discurso
- Enfoques abstractivos y análisis de resultados

## 📊 Resultados

El modelo PEGASUS fue evaluado en múltiples datasets y métricas. Se incluyeron visualizaciones de:

- Arquitectura interna del modelo.
- Comparaciones de ROUGE frente a otros modelos.
- Influencia del tamaño del vocabulario.
- Esquemas de atención avanzada (modelo SELF-MEM).

## 🛠 Cómo compilar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/pegasus-summary-survey.git
   cd pegasus-summary-survey
