# Proyecto Integrador de Aprendizaje Automático

**Integrantes:**
- María Clara Ávila Chinchia
- Mateo José Giraldo Castillo
- Miguel Angel Lugo Cozzarelli
- Hector David Sanjuan Fábregas

---

La segmentación celular en imágenes microscópicas constituye una de las tareas más relevantes dentro del análisis biomédico asistido por inteligencia artificial, debido a su impacto en áreas como diagnóstico clínico, investigación médica y análisis automatizado de tejidos. Sin embargo, este problema presenta múltiples desafíos relacionados con la variabilidad morfológica de las células, la presencia de superposición entre estructuras y el desbalance existente entre diferentes tipos celulares.

En este bloque se implementaron y compararon múltiples arquitecturas modernas de Deep Learning para segmentación celular utilizando el dataset **Sartorius Cell Instance Segmentation** (Kaggle, 2021), compuesto por 606 imágenes de microscopía de campo brillante correspondientes a tres líneas celulares: `shsy5y`, `astro` y `cort`. El objetivo principal fue evaluar el desempeño de diferentes enfoques de segmentación biomédica mediante métricas especializadas, identificando fortalezas, limitaciones y capacidad de generalización de cada arquitectura.

Para ello, se desarrolló un pipeline completo que incluyó análisis exploratorio de datos (EDA), reconstrucción de máscaras mediante Run Length Encoding (RLE), preprocesamiento de imágenes, técnicas de data augmentation, entrenamiento de modelos y evaluación cuantitativa. Entre las arquitecturas implementadas se encuentran **U-Net++**, **HoverNet**, **Cellpose 2.0**, **Segment Anything Model (SAM)** y **Mask R-CNN con Swin Transformer**.

Los modelos fueron evaluados utilizando métricas especializadas de segmentación, tales como Dice Score, Intersection over Union (IoU), Precision, Recall, AUC, Hausdorff Distance y Balanced Accuracy, permitiendo realizar una comparación integral del desempeño de cada arquitectura en escenarios de microscopía celular.

La clasificación automática de texto constituye uno de los problemas de mayor impacto práctico dentro del Procesamiento del Lenguaje Natural, con aplicaciones directas en reclutamiento, gestión documental y análisis de contenido a escala. En el contexto del reclutamiento masivo, un clasificador preciso puede reducir el tiempo de filtrado de currículos de horas a milisegundos, mientras que un sistema mal calibrado puede sistematizar sesgos en los procesos de selección.

En este bloque se implementaron y compararon cinco enfoques de NLP para la clasificación automática de currículos en categorías laborales, utilizando el dataset **Jarvis Calling Hiring Contest** (Kaggle, 2023), compuesto por 2.484 currículos en texto plano distribuidos en 25 categorías profesionales. El objetivo principal fue comparar el rendimiento de paradigmas fundamentalmente distintos: desde transformers preentrenados de última generación hasta métodos clásicos de Machine Learning, pasando por redes recurrentes bidireccionales, redes convolucionales y representaciones por n-gramas de caracteres.

Se desarrolló un pipeline completo que incluyó análisis exploratorio del corpus textual (distribución de clases, longitud de textos, frecuencia de palabras y n-gramas), limpieza y normalización del texto, tokenización, eliminación de stopwords, búsqueda de hiperparámetros mediante Grid Search y Random Search, y evaluación en conjunto de test fijo. Las arquitecturas implementadas fueron **RoBERTa** (fine-tuning), **Word2Vec + BiLSTM**, **CNN-1D**, **TF-IDF + XGBoost** y **FastText**.

Los modelos fueron evaluados con métricas de clasificación multiclase: Accuracy, Precision weighted, Recall weighted, F1-score weighted y ROC-AUC OvR weighted, permitiendo una comparación robusta entre paradigmas con distintas capacidades de representación semántica.

---

## Objetivo general del proyecto

Aplicar de forma integral las técnicas de Deep Learning y Machine Learning estudiadas en el curso a dos dominios de aplicación con problemáticas distintas —visión computacional y lenguaje natural— evaluando sistemáticamente múltiples arquitecturas, comparando su desempeño mediante métricas especializadas y extrayendo conclusiones críticas sobre las condiciones bajo las cuales cada enfoque resulta más adecuado.

Este trabajo busca evidenciar la importancia de las arquitecturas especializadas en cada dominio, el impacto del preprocesamiento y las estrategias de regularización, y el rol del transfer learning como factor diferenciador en escenarios con datos limitados.

