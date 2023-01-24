# Predicción de precios de propiedades en venta
Este proyecto tiene como objetivo utilizar un modelo de clasificación con aprendizaje supervisado y otro con aprendizaje no supervisado para predecir categoria de precios de las propiedades en venta. Se proporcionan dos archivos parquet: train.parquet y test.parquet para entrenar y testear los modelos.

Categorías de precios
Se consideran las siguientes categorías de precios:

'low': para precios entre 0 y 999 dólares.
'medium': para precios entre 1000 y 1999 dólares.
'high': para precios desde 2000 dólares en adelante.

Modelos de clasificacion

Se utiliza un modelo de clasificación con aprendizaje supervisado para clasificar el precio de las propiedades en venta. Se usa la métrica Accuracy para evaluar el rendimiento del modelo.

Se utiliza un modelo de clustering para agrupar las propiedades según las 3 categorías a las que pueden pertenecer. La métrica Silhouette score se usa para evaluar el rendimiento del modelo.

Modo de implementación

Descargue el repositorio en su computadora.
Asegúrese de tener las librerías necesarias para ejecutar el código.
abra el archivo "datathon.ipynb" y siga las instrucciones en el notebook para ejecutar el código.
El código genera un archivo GyGuillermo.csv con las predicciones para ambos modelos.



