# MLTutorial

## Integrantes:

1. Garcia Cristian Alejandro
2. Perdomo Laura Sofia
3. Rueda Juan Sebastian

## Solucion de las preguntas:
### 1. Del script de forest fires:
#### ¿Se desea resolver el problema utilizando aprendizaje supervisado o no supervisado? ¿Es un problema de clasificación o de regresión?
El problema que se busca resolver es utilizando el aprendizaje supervisado ya que cuenta con datos numericos y esta informacion previa es la utilizada para entrenar el modelo, complementando, es un problema de regresion puesto que la respuesta es un dato continuo, y segun la evaluacion del modelo podemos ver que se busca una regresion de los datos.
#### ¿Qué interpretación le puede dar a los resultados obtenidos?
A pesar de que el coeficiente de determinacion, que busca predecir futuros incendios forestales es de cerca del 0.8% vemos que tiene una media de error absoluto de alrededor del 20% el cual es demasiado alto como para tomarlo como una prediccion confiable

### 2. Del script de recursos humanos (rrhh):
#### ¿Cuál es la clase para la que el modelo más se equivoca? ¿Por qué?
La clase para la que el modelo mas se equivoca es para el de High, porque a comparacion del resto es la que presenta mayores errores
#### ¿Cuál cree que es el propósito del parámetro max_depth usado al momento de instanciar el modelo de árbol de decisión?
El proposito del parametro max_depth es definir la profundidad del arbol de decision con el fin de limitar la cantidad de nodos hijos del arbol de decision.
#### Para este caso particular, ¿por qué cree que es difícil obtener un buen clasificador?
Consideramos que es mas dificil obtener un buen clasificador porque se esta haciendo con 3 clases y no con 2.

### 3. Identificación de géneros musicales:
#### Para el caso binario (jazz and blues vs. soul and reggae) ¿Es posible obtener mejores métricas entrenando un modelo basado en Random Forest?
Entrenando el modelo basado en random forest se obtiene un buen resultado del valor f, pero de todas maneras no se obtienen mejores metricas puesto que el modelo que en promedio saco mejores metricas fue el modelo de maquinas de vectores de soporte.
#### Escoja otro par de géneros, entrene un conjunto de modelos y documente los resultados del mejor que se haya obtenido.
#### Para el caso multi-clase, ¿cuál es la clase para la que el modelo más se equivoca? ¿Por qué?
#### Para el caso multi-clase, el modelo basado en red neuronal parece estar mayoritariamente sesgado hacia un género particular. ¿Cuál género cree que es?


### 4. Segmentación de cajas de compensación familiar (subsidio):
#### ¿Qué cajas de compensación parecen ser mayoritariamente diferentes a las demás?
#### ¿A partir de qué características utilizadas para el entrenamiento del modelo se podría explicar la razón por la que las cajas anteriores fueron agrupadas en clusters tan pequeños?
#### ¿Se pueden obtener resultados más homogéneos utilizando cantidades diferentes de clusters para el entrenamiento? Entienda homogeneidad como clusters con cantidades similares de instancias de datos.
