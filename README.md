# 01. Uso de Qgis y R para conocer la población de una Área de Influencia📊 

## Descripción: 
Supongamos que se tiene georeferenciada polígono de un proyecto. Sin embargo, para evaluar la viabilidad y el imapacto social de dicho proyecto se requiere conocer ¿cuál es el Área de Influencia de dicho proyecto? y ¿ A cuantas personas potencialmente afectaría nuestro proyecto?

✅ Ver el reporte completo 👉 [analisis.html](https://tuusuario.github.io/mi-proyecto/analisis.html)

##  Requisitos e insumos
- R
- Qgis
- Archivo que nos permita georeferenciar nuestro proyecto en Qgis. Se recoienda que sea en formato KMZ o shp (con sus archivos complementarios.)
- Archivo que muestre y georeferencie las localidades que estan en el Área de Influenci del proyecto. Para el caso de México existe el [Marco Geoestadístico. Censo de Población y Vivienda 2020](https://www.inegi.org.mx/app/biblioteca/ficha.html?upc=889463807469), publicado por INEGI. Dentro del conjuntos de datos de este marco, se encuentran las localiades existentes, tanto amanzanadas como rurales puntuales.
-  Archivo que muestre la población de cada una de las localidades dentro del Área de Influencia. Para ello contamos con el Censo de Población y Vivienda 2020. Si bien se puede usar la base de datos de todo el censo, para mayor comodidad se puede usar el [Sistema de Consulta de Integración Territorial, Entorno Urbano y Localidad.(SCITEL)](https://www.inegi.org.mx/app/scitel/Default?ev=9). Este sistema permite consultar de manera interactiva y focalizada los principales resultados por localidad del censo. Sólo es cuestión de elegir la o las entidades federativas de nuestro interés.

## Paqueterías a utilizar:
- tidyverse
- readr
- kableExtra

## Metodología:

- Generar el Área de Influencia con Qgis.
- Identificar las localidades dentro del Área de Influencia.
- Limpiar las bases de datos que indican la población del Área de Influencia.
- Unir las tablas para obtener los datos deseados.
- Visualizar los resultados.

## Resultados
Siguiendo los pasos de la metodología se obiene un mapa que enemos un mapa que nos indica el Área de Influencia de nustro proyecto, asi como sus diferentes niveles, y tenemos una tabla que nos indica cuales localidades se encuentran en el AI, y su población correspondiente.




