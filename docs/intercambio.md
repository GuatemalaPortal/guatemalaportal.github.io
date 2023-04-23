---
layout: default
title: Intercambio de Información
has_children: false
nav_order: 9
---


# Intercambio de Información desde el Portal de Biodiversidad de Guatemala
{: .no_toc }

<div class="code-example" markdown="1">
Plataformas externas
{: .label .label-yellow }
</div>


El Portal de Biodiversidad de Guatemala permite descargar archivos .csv, .txt o Darwin Core, lo cual permite el intercambio de la información con otras plataformas.
{: .fs-5 .fw-300 }

---

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Global Biodiversity Information Facility

Para aprender más acerca del intercambio de datos de colecciones hacia GBIF desde el **Portal de Biodiversidad de Guatemala**, ir a la sección Colecciones > [Publicación en GBIF](https://guatemalaportal.github.io/docs/colecciones/gbif/publicar/).

Para aprender más acerca de intercambio de información (archivos .csv) con la Integrated Publishing Tool, consultar con el nodo GBIF Guatemala.

---

## Sistema Nacional de Información Sobre Diversidad Biológica de Guatemala -SNIBgt-

El SNIBgt es un agregador e información basado en el [Atlas of Living Australia](https://living-atlases.gbif.org/participants/snibgt/). Esta plataforma es el agregado de información oficial del país, y es manejado por el Consejo Nacional de Áreas Protegidas.

No existe documentación disponible para conocer acerca del intercambio de **datos de colecciones** (registros de especímenes). Sin embargo, fue posible hacer el ejercicio de subir un listado de especies y los pasos serán descritos a continuación. 

- **Descarga de Listado de Especies desde el Portal de Biodiversidad**

**1.** Realizar una búsqueda con los parámetros deseados para generar un listado de especies.

|-![PortalChecklist1](https://user-images.githubusercontent.com/69399374/233867636-6e87bd79-2da3-4f20-9980-eb8f657954b7.jpg)|

**2.** Obtener el listado de especies a partir de la búsqueda.
|![PortalChecklist2](https://user-images.githubusercontent.com/69399374/233867659-5ce59d35-6bd8-4fa9-9cb9-eaf69492adfe.jpg)|


**3.** Descargar el listado de especies como archivo .csv (requerido por el SNIBgt).

|![PortalChecklist3](https://user-images.githubusercontent.com/69399374/233864166-e78ae202-0445-4e65-8fba-808fff458b54.jpg)|

**4.** Por alguna razón, el SNIBgt en realidad no acepta archivos .csv.

|![Checklist6](https://user-images.githubusercontent.com/69399374/233864188-25cdd3fa-2319-4ac8-8a37-3148cfcd196d.jpg)|

**5.** Entonces, es necesario abrir la descarga en Excel...

|![Checklist4](https://user-images.githubusercontent.com/69399374/233864275-5c42a786-7aae-4a72-8e00-f4be901ef584.jpg)|

**6.** Y transformarla en un "archivo de texto delimitado por tabulaciones", que sí es aceptado por el SNIBgt.

|![Checklist5](https://user-images.githubusercontent.com/69399374/233864300-46d02cdc-941c-4757-b0aa-a81bedccea69.jpg)|

---
- **En el SNIBgt**

**1.** Ingresar a su cuenta.

|![Login](https://user-images.githubusercontent.com/69399374/233863662-dfce2dc5-6958-4522-9f2d-efcaf1ea3272.jpg)|

**2.** Dirigirse a la opción "Listados de Especies" en el menú a la izquierda, y luego "Upload Checklist" en el menú superior derecho. Elegir el archivo (.txt delimitado por tabulaciones) que desea subir.

|![Checklist7](https://user-images.githubusercontent.com/69399374/233864380-9435fd6c-0f4a-4f83-a6a5-acfab18a736b.jpg)|

**3.** Revisar el archivo, para observar los campos incluidos.

|![Checklist8](https://user-images.githubusercontent.com/69399374/233864640-9e148d77-31af-4c42-9cd6-d527898ec19e.jpg)|

**4.** Agregar la información requerida de título, descripción y ubicación. Subir el listado.

|![Checklist9](https://user-images.githubusercontent.com/69399374/233864732-a433ab49-2d0e-4ae3-85e4-195742a3c9f1.jpg)|

**5.** El listado está incorporado en el SNIBgt. Se puede seleccionar la opción de "Ver Registros" pero no cambia la ventana (se asume) porque este tipo de archivos no contiene registros de especímenes u observaciones.

|![Checklist10](https://user-images.githubusercontent.com/69399374/233864831-cd03b780-e35a-4d5c-90d1-214aadb8aa5e.jpg)|

**6.** Revisar el listado y editar especies si es necesario.

|![Checklist11](https://user-images.githubusercontent.com/69399374/233864899-8fae4d38-df64-4007-b6be-231b538a12b8.jpg)|

**7.** Puede seleccionar la opción "Download" para intentar descargar el listado, pero no funciona.

|![Download](https://user-images.githubusercontent.com/69399374/233865508-d2f5efd1-3871-43b0-a4a7-85146c83e1cb.jpg)|

**8.** Seleccionar la opción de "Ver en Portal Espacial":

|![Checklist12](https://user-images.githubusercontent.com/69399374/233865073-90701ff5-7b46-4567-b6d2-1e7a6db5e8db.jpg)|

**9.** Saldrá un mensaje de error (se asume) porque este tipo de archivos no contienen registros de especímenes u observaciones.

|![Checklist12](https://user-images.githubusercontent.com/69399374/233864951-319d3c97-63ad-42cf-b95b-f5a546a2317f.jpg)|

**10.** Ir a la página principal de Listados de Especies, su listado aparecerá junto a todos los disponibles para el público. Si su listado es privado, sólo usted podrá observarlo.

|![Checklist14](https://user-images.githubusercontent.com/69399374/233865151-3eb0e9a6-c747-442c-aeda-354fd278348d.jpg)|

**11.** Ir a "Mis Listados" para ver únicamente su listado.

|![Checklist16](https://user-images.githubusercontent.com/69399374/233865188-bf20267e-2294-4467-93d6-85d9c4862fd3.jpg)|

**12.** Seleccionar la opción "Reload" para editar o actualizar el listado.

|![Checklist17](https://user-images.githubusercontent.com/69399374/233865296-de07ac62-9092-48f6-bb27-8f4b19d669cf.jpg)|

**13.** Seleccionar el archivo con el que desea sustituir o actualizar el listado.

![Checklist18](https://user-images.githubusercontent.com/69399374/233865274-6554e329-5183-4057-8b2e-5a9f853a044b.jpg)


**14.** Seleccionar la opción "Delete" si quiere borrar el listado.

|![Checklist19](https://user-images.githubusercontent.com/69399374/233865326-e18f9e4f-21a2-406b-a15b-ebb18b564516.jpg)|

**15.** El listado ha sido eliminado.

|![Checklist20](https://user-images.githubusercontent.com/69399374/233865350-368e1bed-fcc3-402d-82bd-6f91c7c05de1.jpg)|
