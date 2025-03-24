# Deteccion-de-Sexismo-y-Misoginia
Tesis de Licenciatura con el tema "Detección de Sexismo y Misoginia en Tweets en Español con Aprendizaje Automático".

Este proyecto realiza una comparación sistemática de modelos de aprendizaje automático como SVC y Regresión Logística contra el modelo de aprendizaje profundo SaBERT.
Las bases de datos utilizadas fueron: AMI IberEval 2018, MeTwo 2020 y EXIST IberLEF 2021.

El preprocesamiento de los datos se realizó aplicando el modelo de texto propuesto por S.Téllez en 2028 incluido en Micro Clasificación de Texto (https://microtc.readthedocs.io/en/docs/).

El desempeño de los modelos fue evaluado con distintas medidas de desempeño; en términos de Accuracy, se obtuvieron los siguientes resultados en el conjunto de prubea:

1. SaBERT: 0.766
2. Reg-Log: 0.732
2. SVM Lineal: 0.732
4. SVM RBF: 0.717
