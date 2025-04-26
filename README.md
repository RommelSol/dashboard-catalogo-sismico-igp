# Catálogo Sísmico 1960 - 2023

<p align="center">
  <img src="gif-de-presentacion/comp-3.gif" alt="Demo Dashboard Sísmico" width="700"/>
</p>

Un catálogo sísmico es una base de datos que contiene todos los parámetros que caracterizan a un sismo, calculados en las mismas condiciones, con el objetivo de constituirse como una base homogénea útil para la realización de estudios en sismología. El presente catálogo ha sido elaborado por el Instituto Geofísico del Perú (IGP), institución responsable del monitoreo de la actividad sísmica en el país, y contiene todos aquellos sismos percibidos por la población y registrados por la Red Sísmica Nacional desde 1960, fecha en la que se inicia la vigilancia instrumental de la sismicidad en el Perú.
    
### Dato y Medio de Distribución
- Catálogo Sísmico 1960-2023 - [Instituto Geofísico del Perú - IGP] [Descargar](https://datosabiertos.gob.pe/sites/default/files/Catalogo1960_2023.xlsx)
- Metadatos del Catálogo Sísmico 1960 -2023 - [Instituto Geofísico del Perú - IGP] [Descargar](https://datosabiertos.gob.pe/sites/default/files/Metadatos_38.docx)
- Diccionario de Datos del Catálogo Sísmico 1960 -2023 - [Instituto Geofísico del Perú - IGP] [Descargar](https://datosabiertos.gob.pe/sites/default/files/DiccionarioDatos_18.xlsx)
    
### Diccionario de datos
| Variable | Descripción | Tipo de dato | Tamaño | Información Adicional |
| -------- | ------- | ------- | ------- | ------- |
| FECHA_CORTE | Fecha de corte de información | Numérico | 8 | Formato: aaaammdd |
| FECHA_UTC | Hora universal coordinado (UTC), Es la fecha con cinco horas adelantadas con respecto a la hora local debido a que Peru se encuentra en una zona horaria UTC -5 | Numérico | 8 | Formato: aaaammdd |
| HORA_UTC | Hora universal coordinada (UTC), cinco horas adelantadas con respecto a la hora local debido a que Peru se encuentra en una zona horaria UTC -5 | Numérico | 6 | Formato: aaaammdd |
| LATITUD | Es la distancia en grados, minutos y segundos que hay con respecto al paralelo principal, que es el ecuador (0º). La latitud puede ser norte y sur | Float | | |
| LONGITUD | Es la distancia en grados, minutos y segundos que hay con respecto al meridiano principal, que es el meridiano de Greenwich (0º). | Float | | |
| PROFUNDIDAD | Profundidad del foco sísmico por debajo de la superficie | Numérico | | |
| MAGNITUD | Corresponde a la cantidad de energía liberada por el sismo y esta expresada en la escala de magnitud momento Mw. | Float | | |
