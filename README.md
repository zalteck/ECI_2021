# ECI_2021
Guiones de prácticas para la asignatura extracción de características en imágenes. Utilizados en el master en Ciencia de Datos y Arquitectura de los Computadores de la Universidad de Granada (DATCOM-UGR) en el curso 2021/2022. Se incluyen 3 guiones en formato jupyter notebook .ipynb, detallados a continuación.

~~~
Extracción de Características en Imágenes.
Master en Ciencia de Datos y Arquitectura de los Computadores.
Universidad de Granada.


Fernando Pérez Bueno - fpb@ugr.es
Rafael Molina Soriano - rms@decsai.ugr.es
~~~

# Práctica 1: Análisis de Componentes Principales (PCA)

Vamos a utilizar el análisis de componentes principales sobre una base de datos de caras para reducir la dimensionalidad de cada cara extrayendo un conjunto de variables latentes. Estas variables latentes podrían, con posterioridad, utilizarse, por ejemplo, en problemas de clasificación siempre que los errores de reconstrucción de las caras usando las variables latentes fuese pequeño. También podrían usarse en problemas de detección de anomalías.

La base de datos ERRDfaces.mat contiene una base de datos de caras almacenada por filas en la matriz `X`. Cada fila corresponde a una cara de 32x32=1024 píxeles niveles de gris. El número de ejemplos es N_T=5000.

# Práctica 2: Análisis de Componentes Principales Probabilístico (PPCA)

En este guión, vamos a estudiar la versión probabilistica del análisis de componentes principales. Esto nos va a permitir, por un lado, mirar al modelo PCA que hemos estudiado desde otro punto de vista (modelo generativo) y, por otro,  introducir un modelo  que nos va a permitir avanzar hacia los Variational AutoEncoders (VAEs) y Generative Adversarial Networks (GANs).

Vamos a trabajar con el mismo dataset de caras de la practica de PCA. Veremos qué ocurre cuando tenemos que aprender el modelo con datos ruidosos.

# Práctica 3: Auto Encoder Variacional (VAE)

En este guión veremos la implementación de una VAE en Keras. 
Esta implementación ha sido obtenida de los ejemplos de Keras:
https://keras.io/examples/generative/vae/
