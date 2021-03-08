## Limpieza de datos
Uno de los pasos más importante al momento de trabajar con bases de datos es el paso anterior al procesamiento, que requiere de una limpieza de información. Nos topamos con dificultades que se presentaron por la forma en la que los datos fueron almacenados en el archivo CSV: columnas completas sin información, filas adicionales vacías y cambios de nombres de las columnas entre los años, como se comentó con anterioridad.

Durante la limpieza de datos, al momento de revisar el tamaño de los Data Frame por año, descubrimos que no todos tenían el mismo número de filas, había unos que tenían más. Pero esto no es  ningún error, más bien algo de sentido común. Cada cuatro años, tenemos un año bisiesto, es decir, los años que tienen filas “de más” realmente corresponde a 24 exactamente, que serían las mediciones de un día completo, el 29 de Febrero.

Limpieza de valores NaN

Las columnas y 21 filas vacías fueron eliminadas durante este procedimiento. Estudiando el Data Frame, hallamos valores faltantes (-99 equivalentes a NaN). La estrategia que se eligió fue sustituir los valores de tipo NaN por el promedio de la columna correspondiente, de esta manera facilitamos la programación y no fue necesario eliminar filas que podrían dificultar el procesamiento en programación.
 
Una vez casi concluida la fase de limpieza de datos descubrimos que existían filas de fechas y horas con valores NaN, lo cual no debería ser posible porque los documentos csv estaban completos en todas las fechas. Realizando una análisis más profundo descubrimos que este fenómeno se daba en el cambio de año del 2013 al 2014, donde el archivo csv del 2013 tenía exactamente 21 filas vacías, pero estas filas eran adicionales a las que ya estaban contempladas en el año, por lo cual no se perdió en ningún momento información y solo las descartamos.

Puedes ver la limpieza de los datos en la sección "Limpieza de datos" del notebook

[NOTEBOOK CON LIMPIEZA DE DATOS]()
