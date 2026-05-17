# Proyecto Integrador de Aprendizaje Automático

Integrantes:
- María Clara Ávila Chinchia
- Mateo José Giraldo Castillo
- Miguel Angel Lugo Cozzarelli
- Hector David Sanjuan Fábregas

La segmentación celular en imágenes microscópicas constituye una de las tareas más relevantes dentro del análisis biomédico asistido por inteligencia artificial, debido a su impacto en áreas como diagnóstico clínico, investigación médica y análisis automatizado de tejidos. Sin embargo, este problema presenta múltiples desafíos relacionados con la variabilidad morfológica de las células, la presencia de superposición entre estructuras y el desbalance existente entre diferentes tipos celulares.

En este proyecto se implementaron y compararon múltiples arquitecturas modernas de Deep Learning para segmentación celular utilizando el dataset Sartorius Cell Instance Segmentation. El objetivo principal fue evaluar el desempeño de diferentes enfoques de segmentación biomédica mediante métricas especializadas, identificando fortalezas, limitaciones y capacidad de generalización de cada modelo.

Para ello, se desarrolló un pipeline completo que incluyó análisis exploratorio de datos (EDA), reconstrucción de máscaras mediante Run Length Encoding (RLE), preprocesamiento de imágenes, técnicas de data augmentation, entrenamiento de modelos y evaluación cuantitativa. Entre las arquitecturas implementadas se encuentran U-Net++, HoverNet, Cellpose 2.0, Segment Anything Model (SAM) y Mask R-CNN con Swin Transformer.

Los modelos fueron evaluados utilizando métricas especializadas de segmentación, tales como Dice Score, Intersection over Union (IoU), Precision, Recall, AUC, Hausdorff Distance y Balanced Accuracy, permitiendo realizar una comparación integral del desempeño de cada arquitectura en escenarios de microscopía celular.

Finalmente, este trabajo busca evidenciar la importancia de las arquitecturas especializadas en visión biomédica y analizar el impacto del preprocesamiento, la densidad celular y las técnicas de generalización en tareas avanzadas de segmentación profunda.
