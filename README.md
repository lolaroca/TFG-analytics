# TFG PHYD
AUTOR: María Dolores Roca Morlán

GRADO: 5ºGITT + BA

### Descripción del proyecto
Este proyecto se centra en predecir las variables que más afectan en los accidentes de tráfico. Se han obtenido datos desde 2017 a 2022 sobre las distintas variables que afectan en los accidentes de tráfico, estos datos se han obtenido de la web oficial de la DGT. Para realizar esta predicción se han utilizado 3 modelos: Random Forest, ANN y Regresión Lasso. También se ha realizado un exhaustivo análisis de los datos y la limpieza de los mismos. 


### Estructura del Proyecto

**Carpeta DatosMunicipales:**
Principales cifras de siniestralidad vial a nivel municipal. Datos consolidados. Son datasets que abarcan desde el año 2017 a 2022. Se realiza un análisis exploratorio de estos datos y una limpieza para el posterior tratamiento de los datos. Variables de interés
- Fallecidos: personas fallecidas en los 30 días posteriores a la ocurrencia del accidente.
- Heridos hospitalizados: personas que requirieron ingreso hospitalario de al menos 24 horasa consecuencia de un accidente de tráfico 
- Heridos no hospitalizados: personas heridas en un accidente de tráfico que no hayan precisado hospitalización superior a veinticuatro hora

**Carpeta Datos Siniestralidad**
Información sobre la composición del parque de vehículos y su antigüedad, y del censo de conductores. Datos consolidados. Son datasets que abarcan desde el año 2017 a 2022. Se realiza un análisis exploratorio de estos datos y una limpieza para el posterior tratamiento de los datos. Variables de interés
- Municipios Información sobre el municipio: Código municipio, nombre del municipio, provincia del municipio y CCAA del municipio.
- Población a 1 de enero del año de referencia Padrón Municipal.
- Censo de conductores Titulares de algún permiso o licencia de conducción en vigor. 31 de diciembre del
- Número de automóviles registrados. Se excluyen vehículos en situación de baja definitiva o temporal.
- Número de los vehículos con menos de 25 años en los que no consta ITV en vigor. N
- Número de vehículos en función de la antigüedad del parque con menos de 25 años para cada clase de vehículos.
- Antigüedad media Promedio de la antigüedad del parque con menos de 25 años para cada clase de vehículos.

**Carpeta ModelosRealizados**
En esta carpeta se encuentra el archivo en el que se aplican los 3 modelos a las 3 variables a predecir con las medidas realizadas para poder compararlos entre sí

