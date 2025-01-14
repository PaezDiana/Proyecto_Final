# Proyecto_Final
Este repositorio contiene el proyecto final de la asignatura Inteligencia Articial aplicada al territorio 

**Autores originales**:
Ankur Mahesh (University of California Berkeley)
Mel Hanna (Climate Change AI)
Presentado originalmente en la Escuela de verano de IA sobre cambio climático 2022

**Modificado po** : Diana Liseth Páez Velasquéz  y Diego Alejandro Piña Gonzalez  
**año de modificación**: 2025

-----
## Contenido
Este repositorio explora diversos enfoques para predecir el índice Niño3.4, relacionado con el fenómeno ENSO, utilizando técnicas de aprendizaje automático. Se incluyen tres ejercicios clave: el primero optimiza algoritmos para predecir el índice con un horizonte de 5 meses, experimentando con redes neuronales profundas, bosques aleatorios y ensamblado de modelos, ajustando hiperparámetros clave y explorando mejoras en el preprocesamiento. 

El segundo ejercicio convierte un problema de regresión a clasificación binaria, mapeando valores del índice a 0 o 1, e implementan y comparan dos enfoques: una red neuronal profunda con PyTorch, optimizada con la función de nn.BCEWithLogitsLoss, y un modelo de regresión logística con Scikit-learn. Ambos modelos se entrenan con datos de 2000-2006 y se evalúan con datos de 2007-2017, calculando la precisión de las predicciones. Este ejercicio permite analizar cómo diferentes enfoques y arquitecturas abordan un problema reformulado como clasificación, destacando la importancia de la selección de métricas y funciones de pérdida en tareas de ML. 

Finalmente el tercer ejercicio evalúa cómo la calidad y antigüedad de los datos afectan el desempeño de los modelos, comparando un modelo entrenado con datos antiguos (1900-1930) frente a otro con datos más recientes (1975-2005) mediante un conjunto Cobe SST, y se analizan las predicciones con gráficos que ilustran el impacto de la incertidumbre en los datos histórico. Todos los ejercicios se evalúan en un rango de datos de prueba (2007-2017/2018) y resaltan el equilibrio entre complejidad del modelo, sobreajuste y capacidad de generalización, ofreciendo una base sólida para mejorar sistemas de predicción de ENSO.
