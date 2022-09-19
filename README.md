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
| Clase Real | Predicción de la Clase  | Alcohol |	Malic Acid |	Ash |	Alcalinity of Ash |	Magnesium	| Total Phenols |	Flavanoids |	Nonflavanoid phenols |	Proanthocyanins	| Color intensity	| Hue	| OD280/OD315 of diluted wines	| Proline |
|---|---|---|---|---|---|---|---|---|---|---|---|---| ---- | ------------- |
1    |   1| 14.23|  1.71|	2.43|	15.6|	127|	2.80|	3.06|	0.28|	2.29|	5.64|	1.04|	3.92|	1065|
1    |   1| 13.20|	1.78|	2.14|	11.2|	100|	2.65|	2.76|	0.26|	1.28|	4.38|	1.05|	3.40|	1050|
1    |   1| 13.16|	2.36|	2.67|	18.6|	101|	2.80|	3.24|	0.30|	2.81|	5.68|	1.03|	3.17|	1185|
1    |   1| 14.37|	1.95|	2.50|	16.8|	113|	3.85|	3.49|	0.24|	2.18|	7.80|	0.86|	3.45|	1480|
1    |   1| 13.24|	2.59|	2.87|	21.0|	118|	2.80|	2.69|	0.39|	1.82|	4.32|	1.04|	2.93|	735|


## Archivos a revisar
Aprendizaje_Maquina_Framework.ipynb

Aprendizaje_Maquina_Framework.py
