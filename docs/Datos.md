
## Descripción y obtención de los datos

 
Al principio no fue tan sencillo encontrar los datos para investigar la temática de la calidad del aire, pero finalmente decidimos trabajar con las bases de datos del **IMECA** (Índice Metropolitano de la Calidad del Aire) puesto que nos pareció más informativo y claro usar su escala adimensional; además resume la información de las 34 estaciones de monitoreo existentes en cinco zonas representativas del Valle de México: Noroeste, Noreste, Centro, Suroeste, Sureste.

La mayoría de los datos los descargamos en [este enlace](http://www.aire.cdmx.gob.mx/estadisticas-consultas/consultas/download_imeca.php) de la Dirección de Monitoreo Atmosférico, sin embargo los datos del 2019 se encontraban incompletos. Tras una búsqueda más profunda encontramos [otro enlace](http://www.aire.cdmx.gob.mx/default.php?opc=%27aqBjnmU=%27) y seleccionando la opción “índice de calidad del aire” accedimos a los datos completos del 2019.

La base de datos estaba conformada por un archivo con extensión .xls para cada año. Cada uno de estos archivos incluye información sobre la fecha y hora de medición, así como las mediciones para cada zona y contaminante criterio. Elegimos trabajar con los datos de los años **2005-2020** porque consideramos que es un buen rango para analizar y observar cambios en el tiempo, así como hacer comparaciones y responder nuestras preguntas de investigación. Una vez que descargamos los datos, los convertimos a archivos CSV para manejarlos más fácilmente en cualquier entorno y con cualquier lenguaje de programación.
Por último es importante resaltar que el diccionario de la base de datos nos indica que los datos nulos se identifican con la etiqueta -99.

Los siguientes son los datasets que se recolectaron del IMECA:

[Datasets recolectados](https://github.com/BettySanchez7/Analisis_Calidad_AireCDMX_Python/tree/main/datos_IMECA/csv)


[Siguiente: analisis exploratorio de datos](https://github.com/BettySanchez7/Analisis_Calidad_AireCDMX_Python/blob/main/docs/analisisexploratorio.md)
