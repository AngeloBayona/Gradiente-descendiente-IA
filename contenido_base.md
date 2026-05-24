# Inteligencia Artificial – 20/05/2026

## Tema
Gradiente descendiente.

## Nombre
Gradiente descendiente aplicado a la Inteligencia Artificial.

## Descripción
El gradiente descendiente es un algoritmo de optimización utilizado para encontrar el valor mínimo de una función. En inteligencia artificial, se usa especialmente para minimizar una función de costo o pérdida, es decir, para reducir el error que comete un modelo cuando hace predicciones.

Su importancia está en que permite que un modelo aprenda ajustando sus parámetros poco a poco. En lugar de encontrar una solución exacta de una sola vez, el algoritmo realiza aproximaciones sucesivas: calcula la dirección en la que el error aumenta más rápido y luego avanza en la dirección contraria para disminuirlo.

## Explicación didáctica
Una forma sencilla de entenderlo es imaginar una persona en una montaña con neblina que quiere llegar al punto más bajo. Como no puede ver todo el paisaje, revisa la inclinación del terreno donde está parada y da un paso hacia abajo. Luego vuelve a revisar la inclinación y repite el proceso hasta acercarse al valle.

En IA, la montaña representa la función de error; la posición representa los parámetros del modelo; la inclinación representa el gradiente; y el tamaño del paso representa la tasa de aprendizaje. Si el paso es demasiado pequeño, el aprendizaje será lento. Si es demasiado grande, el algoritmo puede saltarse el mínimo y no estabilizarse.

La fórmula general es:

θ(t+1) = θ(t) − α∇J(θ)

Donde:
- θ representa los parámetros del modelo.
- J(θ) es la función de costo.
- ∇J(θ) es el gradiente de la función.
- α es la tasa de aprendizaje.

## Tipos principales
- Gradiente descendiente batch: usa todos los datos de entrenamiento en cada actualización. Es estable, pero puede ser lento en bases grandes.
- Gradiente descendiente estocástico: actualiza los parámetros usando un dato a la vez. Es más rápido, pero más variable.
- Mini-batch gradient descent: usa pequeños grupos de datos. Es el más común en entrenamiento de redes neuronales porque equilibra velocidad y estabilidad.

## Ejemplos relacionados con aplicación del concepto

### Regresión lineal
Se usa para ajustar una recta que minimice la diferencia entre valores reales y predichos. Por ejemplo, estimar el precio de una vivienda con base en variables como área, ubicación o número de habitaciones.

### Redes neuronales
En el entrenamiento de redes neuronales, el gradiente descendiente permite actualizar los pesos de la red para reducir el error en tareas como clasificación de imágenes, reconocimiento de voz o predicción de series temporales.

### Clasificación de imágenes
Un modelo de visión artificial ajusta sus parámetros para identificar patrones visuales. Cada iteración reduce la diferencia entre la clase predicha y la clase real.

### Aprendizaje de métricas de distancia
En algoritmos basados en similitud, como kNN o k-means, la optimización permite ajustar métricas de distancia para que los datos similares queden más cerca y los diferentes más separados.

## Cierre
El gradiente descendiente es fundamental en IA porque convierte el aprendizaje en un proceso de mejora progresiva. Su lógica es simple: medir el error, calcular la dirección de corrección, ajustar los parámetros y repetir hasta encontrar una solución aceptable.