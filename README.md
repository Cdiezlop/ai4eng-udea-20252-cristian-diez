# AI4ENG UDEA 2025-2 — Pruebas Saber Pro Colombia

## 🧠 Introducción
Este repositorio contiene el desarrollo del proyecto de la competencia **AI4ENG UDEA - Semestre 2025-2**, cuyo objetivo es aplicar técnicas de aprendizaje automático para predecir el **rendimiento global** de los estudiantes colombianos en las **Pruebas Saber Pro**, clasificándolos en cuatro categorías:  
**bajo, medio-bajo, medio-alto y alto.**

El trabajo se desarrolla como parte del curso **Modelos y Simulación de Sistemas** de la Universidad de Antioquia, en el programa de **Ingeniería de Sistemas**.  
Durante el semestre se realizarán tres entregas progresivas que incluyen exploración, preprocesamiento, modelado y envío de resultados a Kaggle.

---

## 👥 Integrantes del equipo

| Nombre completo | Cédula | Programa académico | Usuario de Kaggle |
|------------------|---------|--------------------|-------------------|
| Cristian Diez | 1036967493 | Ingeniería de Sistemas | [cdiezlop](https://www.kaggle.com/cdiezlop) |
| Rafael Ángel Alemán Castillo | 1001560844 | Ingeniería de Sistemas | — |
| Alejandro Gallego Alarcón | 1013104268 | Ingeniería de Sistemas | — |

---

## 📁 Contenido del repositorio

| Archivo | Descripción |
|----------|--------------|
| `01 - exploración.ipynb` | Carga y exploración inicial del dataset `train.csv` de la competencia. Se verifican dimensiones, tipos de datos, valores faltantes y distribución de la variable objetivo `RENDIMIENTO_GLOBAL`. |
| `README.md` | Información general del proyecto, integrantes y estructura de entregas. |

---

## 🎯 Objetivo del proyecto
Desarrollar un **modelo de clasificación multiclase** capaz de predecir el nivel de desempeño (`RENDIMIENTO_GLOBAL`) de estudiantes a partir de sus características socioeconómicas, académicas e institucionales.  

El proyecto se evalúa con base en:
- **Claridad**: notebooks comentados y entendibles.  
- **Compleción**: inclusión de los archivos requeridos por entrega.  
- **Reproducibilidad**: notebooks que puedan ejecutarse sin errores.

---

## 🧩 Descripción de la competencia

**Competencia en Kaggle:** [UDEA/AI4ENG 20252 - Pruebas Saber Pro Colombia](https://www.kaggle.com/competitions/udea-ai-4-eng-20252-pruebas-saber-pro-colombia)

- **Tarea:** Clasificación multiclase (4 clases)  
- **Variable objetivo:** `RENDIMIENTO_GLOBAL`  
- **Métrica de evaluación:** *Accuracy*  
- **Archivos principales:**  
  - `train.csv`: Datos de entrenamiento.  
  - `test.csv`: Datos de prueba (sin etiquetas).  
  - `sample_submission.csv`: Formato de envío a Kaggle.

---

## ⚙️ Tecnologías utilizadas
- Python (Google Colab)
- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- Kaggle API para descarga y envío de resultados
- GitHub para control de versiones

---

## 📆 Entregas del proyecto

1. **Entrega 1:** Exploración de datos (`01 - exploración.ipynb`)
2. **Entrega 2:** Preprocesamiento y análisis con video explicativo
3. **Entrega final:** Modelos, comparación y envío de resultados a Kaggle

---

## © Universidad de Antioquia
**Curso:** Modelos y Simulación de Sistemas  
**Semestre:** 2025-2  
**Docente:** Raúl Ramos Pollán  
**Institución:** Facultad de Ingeniería, Universidad de Antioquia
