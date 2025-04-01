# Logistic Regression

**Logistic Regression**: Estima la probabilidad de que ocurra un evento,basándose en un conjunto de datos determinado de variables independientes.

Este tipo de modelo estadístico (conocido también como _logit_), se utiliza a menudo para la clasificación y el análisis predictivo. Dado que el resultado es una probabilidad, la variable dependiente está limitada entre 0 y 1. En la regresión logística, se aplica una transformación _logit_ a las probabilidades, es decir, la probabilidad de éxito dividida entre la probabilidad de fracaso.

Hay tres tipos de modelos de regresión logística, que se definen en función de la respuesta categórica.

- **Regresión logística binaria**: En este enfoque, la respuesta o variable dependiente es dicotómica, es decir, solo tiene dos resultados posibles (por ejemplo, 0 o 1). Algunos ejemplos populares de su uso incluyen predecir si un correo electrónico es spam o no.
- **Regresión logística multinomial**: La variable dependiente tiene tres o más resultados posibles; sin embargo, estos valores no tienen un orden específico. Por ejemplo, los estudios cinematográficos buscan predecir el género de película que probablemente verá un espectador para comercializarla de forma más eficaz. Un modelo multinomial puede ayudar al estudio a determinar la influencia que la edad, el sexo y la situación sentimental de una persona pueden tener en el tipo de película que prefiere. De esta forma, el estudio puede orientar una campaña publicitaria de una película específica hacia un grupo de personas con probabilidades de ir a verla.
- **Regresión logística ordinal**: Este tipo de modelo de regresión logística se utiliza cuando la variable de respuesta tiene tres o más resultados posibles, pero en este caso, estos valores tienen un orden definido. Ejemplos de respuestas ordinales incluyen escalas de calificación de la A a la F o escalas de valoración del 1 al 5.