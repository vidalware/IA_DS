# IA_DS – Prueba Técnica de Ciencia de Datos (Consultora Ambiental DSS)

## Descripción del Proyecto y Contexto

Este repositorio contiene el desarrollo de una **prueba técnica de ciencia de datos** realizada para la consultora ambiental **DSS**. El proyecto se enfoca en el análisis de datos de **hechos sancionados en materia ambiental**, es decir, incidentes o infracciones al reglamento ambiental que han resultado en sanciones por parte de la autoridad. El objetivo principal es explorar estos datos y construir un modelo predictivo que ayude a **clasificar la gravedad de nuevos incidentes ambientales**, permitiendo a la organización priorizar la atención en aquellos casos más **graves**.

A lo largo del proyecto se siguen las etapas típicas de un pipeline de ciencia de datos:

- **Exploración de Datos**: análisis exploratorio inicial para comprender la estructura y calidad de los datos.  
- **Preprocesamiento**: limpieza de datos, codificación de variables categóricas, tratamiento de nulos.  
- **Modelado (Clasificación)**: entrenamiento de un modelo de clasificación, con enfoque en **Random Forest**.  
- **Importancia de Variables**: análisis de los factores más influyentes en la predicción de la gravedad.  
- **Evaluación del Desempeño**: métricas de precisión, recall, F1 y matriz de confusión.  
- **Reflexión Final**: discusión sobre la priorización de la detección de hechos graves.

---

## Estructura del Repositorio

- **`prueba_tecnica_dss.ipynb`** → Notebook principal con todo el flujo de trabajo (EDA, preprocesamiento, modelado, resultados).  
- **`/datos_prueba.csv`** → Dataset probolema 1.
- **`/datos_prueba_2.csv`** → Dataset probolema 1.
- **`README.md`** → Documento actual con la descripción del proyecto.

---

## Requisitos del Entorno y Dependencias

- **Python 3.8+**  
- **Jupyter Notebook / Jupyter Lab**  
- Librerías principales:  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  
  - `matplotlib`  
  - `seaborn`
 
  - 
