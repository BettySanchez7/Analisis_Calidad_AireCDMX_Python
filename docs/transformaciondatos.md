
## Transformación de datos
Revisando el tipo de dato por medio de la función dtypes, observamos que la fecha y hora estaban clasificadas de forma incorrecta, con valores de tipo string y float, respectivamente.

Se realizó un casting a la fecha transformando a tipo datetime especificando el uso de nanosegundos debido que al utilizar en milisegundos nos marcaba error. Consideramos que la hora en realidad no nos será tan útil en análisis posteriores, ya que pensamos agrupar por mes, sin embargo la cambiamos a tipo int para no generar confusiones.

Después de estos procesos de limpieza y transformación, guardamos los dataframes en archivos csv para poder utilizarlos en los siguientes análisis.

Como último paso del proceso de transformación de datos, decidimos calcular promedios mensuales de cada contaminante y zona, reduciendo así la cantidad de datos y quedándonos con valores representativos que nos puedan facilitar el análisis. Para llevar a cabo esta transformación usamos la función resample, agrupando por mes y calculando el promedio. Guardamos estos nuevos dataframes en archivos csv.

Puedes ver el proceso que se llevo a cabo en la sección "Transformación de datos" del notebook: 

[Siguiente: Resultados del proyecto](https://github.com/BettySanchez7/Analisis_Calidad_AireCDMX_Python/blob/main/docs/resultados.md)
