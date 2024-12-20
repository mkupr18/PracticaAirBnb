---
title: "Readme. Taller datos Inside Airbnb"
author: "Taller MAT3 GIN 24-25"
date: "2024-11-15"
output: 
  html_document: 
    toc: true
    number_sections: true
    keep_md: true
---



### Taller de Datos: Inside Airbnb

#### Contexto de los Datos 

La plataforma [Inside Airbnb](http://insideairbnb.com/) recopila y pone a disposición información detallada sobre apartamentos y residencias vacacionales en alquiler en diversas ubicaciones alrededor del mundo. Este sitio constituye una herramienta valiosa para analizar la oferta de Airbnb en distintas regiones, desde provincias y departamentos hasta condados y barrios.

Los datos disponibles son de acceso libre bajo una [licencia Open Source](https://www.redhat.com/es/topics/open-source/what-is-open-source), lo que permite su uso y análisis siempre que se respeten las condiciones especificadas en la [licencia del proyecto](http://insideairbnb.com/about.html). Si quieres sumergirte en el mundo de los datos y explorar sus posibilidades, puedes comenzar desde la [página principal de Inside Airbnb](http://insideairbnb.com/get-the-data.html) o consultar los recursos específicos que se detallan a continuación.

#### Recursos de Datos Disponibles

- **[Obtener datos](http://insideairbnb.com/get-the-data.html):** Enlace directo para descargar los datos.
- **[Diccionario de Datos](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=982310896):** Documentación detallada sobre las variables disponibles.
- **[Políticas de Datos](http://insideairbnb.com/data-policies.html):** Información sobre la disponibilidad de datos en relación con la misión del proyecto y las directrices de la comunidad.
- **[Solicitud de Datos](http://insideairbnb.com/data-requests.html):** Herramienta para acceder a datos archivados o de nuevas regiones (ten en cuenta que este servicio es de pago para datos de más de un año de antigüedad).

#### ¡Atención!
Si deseas consultar datos históricos que excedan un año, deberás recurrir al servicio de solicitud de datos, el cual implica un costo.

---

### Acceso y Descarga de los Datos

A través del enlace **[Get the data](http://insideairbnb.com/get-the-data.html)** puedes descargar diferentes archivos para cada ciudad, descritos en la siguiente tabla:

| **Nombre del Archivo**       | **Descripción**                                                                                      |  
|-------------------------------|------------------------------------------------------------------------------------------------------|  
| **listings.csv.gz**           | Datos detallados de las propiedades en la ciudad seleccionada.                                       |  
| **calendar.csv.gz**           | Datos detallados sobre la disponibilidad y precios de las propiedades en la ciudad.                 |  
| **reviews.csv.gz**            | Datos detallados de las reseñas relacionadas con las propiedades en la ciudad.                      |  
| **listings.csv**              | Información resumida y métricas generales, ideal para visualizaciones.                              |  
| **reviews.csv**               | Datos resumidos de reseñas, útiles para análisis temporales vinculados a cada propiedad.            |  
| **neighbourhoods.csv**        | Listado de vecindarios utilizados como filtro geográfico, basado en datos de la ciudad o fuentes GIS. |  
| **neighbourhoods.geojson**    | Archivo GeoJSON con las delimitaciones de los vecindarios de la ciudad.                             |  

¡Explorar estos datos es una gran oportunidad para visualizar y analizar las dinámicas del mercado de alquiler vacacional en distintas regiones del mundo! 🎯
