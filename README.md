# Explorando factores de comportamiento en NovaRetail+

Introducción:

NovaRetail+ es una plataforma de comercio electrónico en Latinoamérica con millones de usuarios. Para el cierre de este año 2024, el equipo de Crecimiento y Retención busca entender:

¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado?

Para ello, hare un análisis correlacional completo sobre un nuevo dataset en español.

🎯 Procedimiento:

Integrar múltiples técnicas de correlación en un solo análisis.
Identificar relaciones significativas entre variables mediante el uso de scatterplots y heatmaps.
Detectar correlaciones engañosas.
Documentar supuestos y limitaciones.
Convertir hallazgos en recomendaciones de negocio.
Escribir un reporte profesional.

🛠️ Herramientas 
Jupyter Notebook
Python: pandas, numpy, seaborn, matplotlib

---

📂 Dataset del proyecto

Nombre: '/datasets/novaretail_comportamiento_clientes_2024.csv'

📏 Tamaño: 15,000 filas

---


## 📂 Contenido del repositorio

- `NovaRetail_factores_comportamineto.ipynb`
  → Notebook  completo de limpieza y análisis exploratorio de datos (EDA) hasta la generación de insights listos para tomar decisiones de negocio.

- `data`
  → Carpeta que contiene los documentos csv necesarios para reproducir el analisis.   

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/Alezgo-ui/adb_mobility_economy_project/blob/main/adb_mobility_economy_project.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `NovaRetail_factores_comportamineto.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Resumen del análisis

- Tabla principal: dataset de comportamiento de clientes ('/datasets/novaretail_comportamiento_clientes_2024.csv').
- Métrica foco: ingresos_mensuales (valor generado por cada cliente).
- Naturaleza del análisis: correlacional y exploratorio, no causal.
- Tipos de relaciones analizadas:
    - Numéricas (lineales y monotónicas)
    - Binarias vs. numéricas
    - Categóricas
- Resultado final: un reporte de análisis de correlación que combine:
    - Evidencia visual
    - Evidencia numérica
    - Interpretación responsable
    - Implicaciones de negocio
