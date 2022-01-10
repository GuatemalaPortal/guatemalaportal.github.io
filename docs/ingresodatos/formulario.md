---
layout: default
title: Ingreso directo de datos
parent: Ingreso de Datos
nav_order: 1
---

# Ingreso directo de datos
{: .no_toc }

<div class="code-example" markdown="1">
Colecciones en vivo
{: .label .label-blue }

Administradores
{: .label .label-green }

Editores
{: .label .label-purple }
</div>


El ingreso directo de datos es una de las características principales de las colecciones manejadas en vivo. Aquí pueden transcribirse directamente los datos que encontramos en las etiquetas de los especímenes, para digitalizarlos.

**Unicamente los administradores y editores de cada colección tienen acceso a ingresar datos directamente.**


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Formulario de ingreso de datos

- Dirigirse al [Portal de Biodiversidad](https://biodiversidad.gt) e iniciar sesión.
- Una vez en el portal, ir a **“Mi Perfil”** (My profile).
- En “Mi Perfil”, seleccionar **"Manejo de Especímenes"** (Specimen Management).
- Al ingresar en Manejo de Especímenes, seleccionar la colección en la que se desea trabajar en el recuadro de **"Manejo de Colecciones"** (Collection Management).
- Al ingresar en la colección deseada, seleccionar **“Agregar Nuevo Registro de Ocurrencia”** (Add New Occurrence Record).
- El formulario está listo para ingresar los datos de los especímenes. 

Notar que cada sección de campos puede expandirse, dando click en el ícono del lápiz.

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/Formulario.jpg?raw=true" >
### Descripción de los campos de datos 

El formulario de ingreso del Portal de Biodiversidad de Guatemala (y del resto de portales Symbiota) está basado en el estándar para datos de biodiversidad **Darwin Core**. Cada campo debe contener información específica, en cierto formato para cumplir con el estándar. Es importante mencionar que no es necesario rellenar todos los campos si no se conocen. A continuación se describe el contenido de cada uno de los campos del formulario:

1. Información del Colector
- **Catalog number:** Número de catálogo (p.e. ABC0000001). Etiqueta física que se encuentra en el espécimen.
- **Other Catalog Numbers:** Otros números de catálogo contenidos en etiquetas físicas previas asociadas al espécimen.
- **Collector:** Colector principal (uno solo).
- **Date:** Fecha en formato año-mes-día (aaaa-mm-dd con números).
- **Associated collectors:** Del segundo colector en adelante.
- **Verbatim date:** Fecha exactamente como está en la etiqueta (puede tener letras).
- **Calculate End Day of Year [desplegar campo adicional]:** Fecha final (si la colecta fue de más de un día) en formato aaaa-mm-dd (el resto de casillas se rellenan automáticamente).

2. Última Identificación
- **Scientific name:** Nombre científico. Preferiblemente, género y especie. También puede agregarse a nivel de familia, subfamilia, tribu, o solamente género. Los nombres están previamente agregados en la base de datos, el autor y la familia se añadirán automáticamente. Si no aparece un nombre, solicitar al administrador que se añada al árbol taxonómico, no escribirlo directamente en el formulario.
- **Author:** Autor. Se añade automáticamente al agregar el nombre. Si no aparece, notificar al administrador.
- **ID Confidence:** Nivel de confianza en la identificación (de absoluto, a necesita revisión).
- **Family:** Se añade automáticamente al agregar el nombre científico. Si no aparece, añadirlo de forma manual. 
- **Identified By:** Nombre del determinador (p.e. J.C. Schuster).
- **Date Identified:** Año de identificación.
- **ID References [desplegar campo adicional]:** Colocar la cita del artículo o libro que contenga la clave o descripción, de estar disponible (muy recomendado). 

3. Localidad
- **Country:** País (seleccionar entre las opciones que aparecen). 
- **State/Province:** En el caso de Guatemala, departamento (añadir manualmente). 
- **County:** Agregar el nombre del municipio (p.e. Purulhá).  
- **Municipality:** Dejarlo en blanco.
- **Locality:** Localidad específica, como está indicado en la etiqueta. 
- **Location Remarks [desplegar campo adicional]:** Notas muy importantes acerca de la localidad, de existir.
- **Latitude:** Latitud en grados decimales. Revisar el signo (para Guatemala, positivo). 
- **Longitud:** Longitud en grados decimales. Revisar el signo (para Guatemala, negativo). 
- **Uncertainty:** Error del GPS, si se conoce, o buscarlo con GeoLocate. Debe ser mayor a 0 metros.
- **Datum:** WGS84 es el más utlizado.
- **Verbatim Coordinates:** Coordenadas en grados, minutos y segundos, si se indica de esta forma en la etiqueta (al agregar este tipo de coordenadas, se transforman automáticamente en grados decimales). 
- **Elevation in Meters:** Elevación en metros (sólo números).
- **Verbatim Elevation:** Agregar si la elevación está en otro tipo de medida, por ejemplo, pies.
- **Georeferenced By [desplegar campo adicional]:** Nombre de la persona que está añadiendo las coordenadas.
- **Georeference Sources [desplegar campo adicional]:** Fuente de las coordenadas. Si es la etiqueta, colocar “label”. Otras posibles fuentes son “GeoLocate”, “GoogleEarth” o “GoogleMaps”.

4. Miscelánea
- **Habitat:** Tipo de hábitat (p.e. bosque seco). 
- **Substrate:** Sustrato (más utilizado para plantas y hongos, pero podría agregarse “hojarasca”, por ejemplo). No es un campo Darwin Core.
- **Notes (Occurrence Remarks):** Datos de la colecta (p.e. trampa de luz cerca de río, colecta nocturna). 
- **Life stage:** Adulto, larva. 
- **Sex:** Macho, hembra, indeterminado.
- **Sampling Protocol:** Tipo de trampa o protocolo de muestreo (p.e. trampa Malaise, UV light trap, trampa Sherman).
 
 
5. Curación
- **Type Status:** Agregar “type”, “paratype”, etc. si el espécimen entra en estas categorías. 
- **Basis of Record:** PreservedSpecimen (espécimen preservado).
-Los campos “Institution Code”, “Collection Code” se rellenan automáticamente al añadir el registro. 



