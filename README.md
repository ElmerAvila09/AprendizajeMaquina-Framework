# Portafolio: Aprendizaje Maquina (Uso de Framework)
## Modelo: Árbol de Decisión / Métrica Calidad de Información: Entropía
Se realiza un modelo para predecir la clase a la que pertenecen cada uno de los registros de vinos en el dataset wines.data

## Dataset
wines.data

El dataset provee las cantidades de 13 constituyentes que se encuentran en tres tipos de vinos, así como el tipo de vino al que pertenece cada registro.

## Librerias Empleadas
* Pandas: Empleado para el manejo de dataframes.
* Sklearn: Empleado para el desarrollo del modelo.
* Graphviz: Empleado para graficar el modelo obtenido.

## Desempeño del Modelo / Métrica

Métrica: ***Presición (Accuracy)***

Precisión con Datos de Entranamiento: 1.0

Presición con Datos de Prueba: 0.98148

La métrica empleada fue obtenida con el método score() perteneciente al modelo instanciado de la libreria sklearn, en este caso al tratarse de un modelo de clasificicación, la métrica regresada corresponde a la precisión (accuracy) del modelo la cual atañe al número de predicciones correctas dividido por el número total de predicciones.
El resultado nos indica que tanto la precisión del modelo con los datos de entrenamiento como con los datos de prueba es excelente, de este modo se puede decir que el modelo tiene un ***buen balance***.

## Tabla de predicciones, resultado del modelo.
| Real | Predicción    |
| ---- | ------------- |
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|
1    |   1|


## Archivos a revisar
Aprendizaje_Maquina_Framework.ipynb

Aprendizaje_Maquina_Framework.py
