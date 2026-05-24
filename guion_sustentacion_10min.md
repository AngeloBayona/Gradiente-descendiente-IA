# Guion de sustentación – 10 minutos

## 0:00–1:00 | Introducción
Buenos días. El tema que voy a explicar es el gradiente descendiente, uno de los métodos más importantes dentro de la inteligencia artificial y el aprendizaje automático. Su función principal es ayudar a los modelos a aprender reduciendo el error que cometen al hacer predicciones.

## 1:00–2:30 | ¿Qué problema resuelve?
Cuando entrenamos un modelo de IA, este inicia con parámetros que no necesariamente son correctos. Por eso, al comparar sus predicciones con los valores reales, aparece un error. Ese error se representa mediante una función de costo o pérdida. El objetivo del entrenamiento es minimizar esa función.

## 2:30–4:00 | Analogía didáctica
Podemos imaginar el proceso como una persona que está en una montaña con neblina y quiere llegar al punto más bajo. Como no puede ver todo el paisaje, revisa la inclinación del terreno donde está y da un paso hacia abajo. Luego repite el proceso. En el algoritmo, la montaña es la función de error, la pendiente es el gradiente y el tamaño del paso es la tasa de aprendizaje.

## 4:00–5:30 | Fórmula
La fórmula general es θ(t+1) = θ(t) − α∇J(θ). θ representa los parámetros del modelo, J es la función de costo, ∇J indica la dirección donde el error aumenta más rápido y α es la tasa de aprendizaje. Como queremos reducir el error, nos movemos en dirección contraria al gradiente.

## 5:30–7:00 | Tipos de gradiente descendiente
Existen varias formas de aplicarlo. El método batch usa todos los datos en cada actualización, lo que lo hace estable pero lento. El método estocástico actualiza con un dato a la vez, por eso es más rápido pero más inestable. El método mini-batch usa grupos pequeños de datos y es muy usado en redes neuronales porque equilibra velocidad y estabilidad.

## 7:00–8:30 | Aplicaciones
El gradiente descendiente se usa en regresión lineal, clasificación, redes neuronales, visión artificial, reconocimiento de voz y sistemas de recomendación. Por ejemplo, en una red neuronal, permite ajustar los pesos internos para que el modelo aprenda a reconocer patrones y reduzca sus errores.

## 8:30–9:30 | Ventajas y limitaciones
Su principal ventaja es que es sencillo, eficiente y aplicable a muchos modelos. Sin embargo, depende mucho de la tasa de aprendizaje. Si la tasa es muy pequeña, el entrenamiento será lento; si es muy grande, puede no encontrar el mínimo. Además, en problemas complejos puede quedarse en mínimos locales.

## 9:30–10:00 | Conclusión
En conclusión, el gradiente descendiente es una base del aprendizaje automático porque transforma el aprendizaje en un proceso de corrección progresiva. Gracias a este algoritmo, muchos modelos de IA pueden mejorar sus predicciones a partir de sus propios errores.