# PANDAS PROJECT:Shark_attack

## ¿Son los tiburones más agresivos según la zona geográfica?
Bajo esta hipótesis se desarrollará todo el estudio realizado en el archivo shark_attack.¿Existe una relación directa entre el número de ataques de tiburón y la zona dónde surgen?¿En qué zonas se dan más ataques?¿Qué tipo de víctima hay?
### Parte I:Visualización de datos.
El primer paso es importar los modulos necesarios para trabajar,en este caso ya que vamos a trabajar con un archivo csv,y lo más adecuado es usar un dataframe importaremos el módulo de trabajo pandas.Lo siguiente será buscar la ruta relativa del archivo al que queremos acceder e importarlo al jupyter-notebook utilizando el encoding adecuado para que sea legible y creando un 'dataframe'.

En esta segunda parte de la visualización,lo que queremos es conocer los datos que contiene nuestro archivo para tener una visión global del conjunto con el que se va a trabajar.Por ello,mostramos por pantalla las primeras columnas del 'dataframe'.A continuación se utliza la función 'shape' para conocer la dimensión del dataframe,de esta forma se puede conocer cuantas columnas y filas tiene.

Después se visualiza cuántos espacios están en blanco en este dataframe usando la función'isnull' y después haciendo una suma 'sum' de todos ellos.Una vez hecho esto miraremos el tipo de dato con el que se va a trabajar y los nombres de las columnas para poder llamarlas cuando sea necesario.

### Parte II:Selección y limpieza de datos.
Selección de las columnas con las que se interesa trabajar.Una vez hecho esto,eliminamos los valores vacíos para descargar de contenido inservible,usando'drop' para las columnas que interesan y su posterior visualización.
Realizamos la misma acción paar los valores duplicados.

### Parte III:Elaboración de análisis.

Utilizando la función 'groupby' se analiza la relación entre el dato y 
