<p align="center">
  <img src="banner.jpg" alt="Big Data y Machine Learning para Economía Aplicada" width="100%">
</p>

<h1 align="center">Big Data y Machine Learning para Economía Aplicada</h1>

<p align="center">
  <strong>MECA 4107 · Universidad de los Andes · 2026-20</strong><br>
  Diapositivas y cuadernos de las clases magistrales
</p>

<p align="center">
  <img src="https://img.shields.io/badge/curso-MECA--4107-1f4e5f" alt="Curso">
  <img src="https://img.shields.io/badge/semestre-2026--20-2a7f9e" alt="Semestre">
  <img src="https://img.shields.io/badge/cr%C3%A9ditos-4-4f8a4f" alt="Créditos">
  <img src="https://img.shields.io/badge/lenguaje-R-276DC3" alt="R">
  <img src="https://img.shields.io/badge/slides-Beamer%20(PDF)-c9a227" alt="Beamer">
</p>

---

## Sobre el curso

Este es un curso de herramientas de *big data* y aprendizaje de máquinas con un enfoque especial en lo que resulta relevante para economistas y para las ciencias sociales. Está dirigido a estudiantes interesados en investigación aplicada y en el análisis de datos grandes y no estructurados.

La tensión que organiza el semestre es la que existe entre **predicción** e **inferencia**. Un modelo puede predecir muy bien y no decir nada sobre el efecto de una política; otro puede identificar un efecto causal y predecir pésimo. Buena parte del curso consiste en saber cuál de las dos preguntas estamos haciendo, y elegir la herramienta que corresponde.

El énfasis está en el análisis de datos reales y en la aplicación de metodologías concretas: encuestas de hogares, precios de propiedades, datos espaciales, texto y datos obtenidos de internet. El curso se dicta principalmente en `R`.

> [!NOTE]
> Las herramientas de IA son parte del flujo de trabajo actual en análisis de datos y pueden usarse como asistente. Pero estos programas se aprenden usándolos: depender de la IA sin entender el código limita el aprendizaje y el desempeño en las evaluaciones.

## Qué hay en este repositorio

Las **diapositivas y cuadernos de las clases magistrales** (miércoles). Las diapositivas están en Beamer compilado a PDF; los cuadernos, en formato Jupyter/`R`. Una carpeta por sesión:

```
BDML_2026_20/
├── banner.jpg
├── README.md
├── Lecture01/
│   ├── Lecture_01.pdf
│   ├── L01_01_LR.ipynb
│   └── figures/
├── Lecture02/
│   └── ...
└── ...
```

El material se publica **a medida que avanza el semestre**, típicamente el mismo día de la sesión o el día anterior. Si una carpeta todavía no aparece, es porque esa sesión aún no se ha dictado.

> [!IMPORTANT]
> Este repositorio contiene **solo el material de las clases magistrales**. Los talleres, los quizzes, las lecturas, las actividades asincrónicas y los anuncios del curso viven en **Bloque Neón**.

## Cronograma

| Duración | Tema | ¿Qué estudiaremos? |
|:--|:--|:--|
| ~2 semanas | **Introducción a big data y machine learning** | Objetivos del curso y fundamentos del aprendizaje de máquinas desde una perspectiva predictiva. Ejemplos motivadores y flujo de trabajo en proyectos de ML aplicados a economía |
| ~2 semanas | **Sobreajuste, validación cruzada y bootstrap. Adquisición de datos web** | Evaluación de modelos mediante validación cruzada y *bootstrap*; cómo prevenir el sobreajuste; herramientas básicas de adquisición de datos desde la web (*scraping*, APIs) |
| ~2 semanas | **Selección de modelos y regularización** | Comparación y selección de modelos predictivos; regularización con Ridge y Lasso para mejorar la generalización y seleccionar variables |
| ~2 semanas | **Clasificación** | Modelo Logit y métricas específicas (precisión, *recall*, F1, AUC); desbalance de clases y técnicas para enfrentarlo |
| ~2 semanas | **Árboles, bosques y boosting** | Árboles de decisión, *Bagging* y Bosques Aleatorios; *Boosting*, *Gradient Boosting* y XGBoost |
| ~2 semanas | **Redes neuronales y aprendizaje profundo** | Redes de una y múltiples capas; entrenamiento (*backpropagation*), regularización (*dropout*, *batch norm*) y aplicaciones en problemas económicos |
| ~2 semanas | **Datos espaciales y texto como datos** | Análisis de datos espaciales, validación cruzada espacial y técnicas básicas de procesamiento de texto como datos |

## Evaluación

| Evaluación | Peso | Detalle |
|:--|:--:|:--|
| **Quizzes** (7 individuales, virtuales) | 28% | 4% cada uno; se elimina la nota más baja. El Quiz 0 es opcional y no tiene peso |
| **Talleres** (3 grupales) | 72% | 24% cada uno: 18% presentación oral y 6% repositorio público en GitHub |

Los talleres se entregan en formato **completamente reproducible**, con evidencia de contribución de todos los miembros del equipo. Cada estudiante es responsable de todo el contenido del taller, independientemente de cómo se organice el trabajo interno.

**Fechas tentativas:** quizzes el 17 y 31 de agosto, 14 y 28 de septiembre, 19 de octubre, 2 y 16 de noviembre. Talleres el 9 de septiembre, 28 de octubre y 25 de noviembre.

## Prerrequisitos

Microeconomía 3 y Econometría 2 o Microeconometría Aplicada; se recomienda haber cursado Econometría Avanzada del PEG. Se necesita experiencia básica en manejo de datos y en `R` o `Python`. Quienes no tengan experiencia pero sí ganas de aprender son bienvenidos previa consulta con el profesor.

Los quizzes son virtuales y supervisados con *LockDown Browser* y *Respondus Monitor*, así que se requiere cámara web funcional y un computador compatible.

## Bibliografía

- Békés, G., & Kézdi, G. (2021). *Data Analysis for Business, Economics, and Policy*. Cambridge University Press.
- James, G., Witten, D., Hastie, T., & Tibshirani, R. (2021). *An Introduction to Statistical Learning: With Applications in R* (2.ª ed.). Springer.
- Hastie, T., Tibshirani, R., & Friedman, J. (2009). *The Elements of Statistical Learning: Data Mining, Inference, and Prediction* (2.ª ed.). Springer.
- Berk, R. A. (2008). *Statistical Learning from a Regression Perspective*. Springer.
- Davidson, R., & MacKinnon, J. G. (2004). *Econometric Theory and Methods*. Oxford University Press.
- Chernozhukov, V., Hansen, C., Kallus, N., Spindler, M., & Syrgkanis, V. (2024). *Applied Causal Inference Powered by ML and AI*. arXiv:2403.02467.
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.

## Equipo docente

| | | |
|:--|:--|:--|
| **Profesor** | Ignacio Sarmiento-Barbieri | [i.sarmiento@uniandes.edu.co](mailto:i.sarmiento@uniandes.edu.co) |
| **Profesor complementario** | Julián David Rojas Aguilar | [j.rojas27@uniandes.edu.co](mailto:j.rojas27@uniandes.edu.co) |

**Horarios:** clase magistral, miércoles de 6:00 a 8:50 pm · clase complementaria, sábados de 9:30 a 10:50 am

**Atención a estudiantes:** con el profesor, [agendar cita aquí](https://ignaciomsarmiento.github.io/) · con el profesor complementario, jueves de 6:00 a 7:00 pm por Zoom, [agendar cita aquí](https://calendly.com/judrojasag/30min)

---

<p align="center">
  <sub>Material docente de la Facultad de Economía, Universidad de los Andes.<br>
  Libre para uso académico y educativo, citando la fuente.</sub>
</p>
