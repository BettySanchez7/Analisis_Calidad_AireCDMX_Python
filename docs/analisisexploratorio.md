## Análisis exploratorio de los datos
(Puedes dirigirte a el notebook con el código para visualizarlos de una mejor manera)
El conjunto de datos por años desde 2005 hasta el 2018, está organizado de la siguiente manera:

- Fecha
- Hora
- Noroeste Ozono
- Noroeste dióxido de azufre
- Noroeste dioxido de nitrogeno
- Noroeste monóxido de carbono
- Noroeste PM10
- Noreste Ozono
- Noreste dióxido de azufre
- Noreste dioxido de nitrogeno
- Noreste monóxido de carbono
- Noreste PM10
- Centro Ozono
- Centro dióxido de azufre
- Centro dioxido de nitrogeno
- Centro monóxido de carbono
- Centro PM10
- Suroeste Ozono
- Suroeste dióxido de azufre
- Suroeste dioxido de nitrogeno
- Suroeste monóxido de carbono
- Suroeste PM10
- Sureste Ozono
- Sureste dióxido de azufre
- Sureste dioxido de nitrogeno
- Sureste monóxido de carbono
- Sureste PM10



En los años 2019 y 2020 se agregaron mediciones de partículas menores a 2.5 micras (PM2.5), también se modificó el nombre de las columnas:
- Fecha
- Hora
- NOO3
- NOSO2
- NONO2
- NOCO
- NOPM10
- NOPM2
- NEO3
- NESO2
- NENO2
- NECO
- NEPM10
- NEPM2
- CEO3
- CESO2
- CENO2
- CECO
- CEPM10
- CEPM2
- SOO3
- SOSO2
- SONO2
- SOCO
- SOPM10
- SOPM2
- SEO3
- SESO2
- SENO2
- SECO
- SEPM10
- SEPM2
Las mediciones de contaminantes en valor IMECA se registran cada hora los 365 días (o 366 en año bisiesto). Existen datos “-99” que, como se mencionó antes, corresponden a valores faltantes.
El conjunto total de datos cuenta con 140277 filas, cada una equivalente a una medición horaria.
En cuanto a las variables o columnas, se puede resumir que trabajaremos únicamente con 5 contaminantes:
- Ozono (O3)
- Dióxido de azufre (SO2)
- Dióxido de nitrógeno (NO2)
- Monóxido de carbono (CO)
- Partículas menores a 10 micras (PM10)
Y 5 zonas:
- Zona Sureste
- Zona Suroeste
- Zona Centro
- Zona Noreste
- Zona Noroeste

Para el análisis de la limpieza de datos se optó por algunos métodos que redujeron de forma considerable la cantidad de información. Esto se describe a continuación.


[Siguiente: limpieza de datos](https://github.com/BettySanchez7/Analisis_Calidad_AireCDMX_Python/blob/main/docs/limpiezadatos.md)
