---
layout: default
title: Intercambio de Información
has_children: false
nav_order: 12
---


# Intercambio de Información desde el Portal de Biodiversidad de Guatemala
{: .no_toc }

<div class="code-example" markdown="1">
Plataformas externas
{: .label .label-yellow }
</div>


El [**Portal de Biodiversidad de Guatemala**](https://biodiversidad.gt) permite descargar archivos .csv, .txt o Darwin Core, lo cual permite el **intercambio de la información** con otras plataformas, en cumplimiento con los principios [FAIR](https://www.go-fair.org/fair-principles/) de facilidad de búsqueda, accesibilidad, interoperabilidad y reutilización de los datos.
{: .fs-5 .fw-300 }

|![GBIF_EXPORT2](https://user-images.githubusercontent.com/69399374/233875610-96e3b7c3-3a47-4af6-818d-4640b64cc0e1.jpg)|

---

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Global Biodiversity Information Facility

La Instalación Global de Información de Biodiversidad (GBIF) es un agregador de datos, que incorpora los registros digitalizados en distintas plataformas a nivel mundial. Esta plataforma busca facilitar el libre acceso a los datos de biodiversidad del mundo y está integrada por representantes gubernamentales o científicos de los países miembros, coordinados desde el Secretariado GBIF en Copenhague, Dinamarca (Guatemala participa como país asociado desde diciembre de 2021. 

|![GBIF](https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/GBIF.jpg?raw=true)|

Para publicar datos de Colecciones en GBIF se necesita cumplir con tres puntos importantes:

1. La institución que aloja físicamente la colección debe contar con un **perfil de publicador** activo en GBIF. Esto se tramita directamente con [GBIF](https://www.gbif.org/become-a-publisher).
2. Los datos de las colecciones deben estar en **formato estandarizado** Darwin Core (y los respectivos formatos estandarizados para extensiones). Esto se logra utilizando Sistemas de Manejo de Colecciones, como el **Portal de Biodiversidad de Guatemala** (se obtienen Archivos Darwin Core), o rellenando una plantilla en Excel (se obtienen archivos .csv).
3. Solicitar acceso a una Instalación que permita la publicación de este archivo Darwin Core o .csv hacia GBIF. En Guatemala existen dos opciones: la instalación Symbiota del [**Portal de Biodiversidad de Guatemala**](https://www.gbif.org/installation/81a4adb0-0d86-420e-8b5e-7583985d1b6f) (activa desde septiembre de 2020), y la instalación IPT de GBIF Guatemala (activa desde mayo 2022).


- Para utilizar la instalación Symbiota del **Portal de Biodiversidad de Guatemala**, ir a la sección **Colecciones** > [**Publicación en GBIF**](https://guatemalaportal.github.io/docs/colecciones/gbif/publicar/).

- Para aprender más acerca de intercambio de información (archivos .csv) con la Integrated Publishing Tool, consultar con el nodo GBIF Guatemala.

|![Ruta](https://user-images.githubusercontent.com/69399374/233875671-dd39e593-1b84-453e-bdc4-b1ac1ad78a21.jpg)|
|:--:|
|Rutas para publicar datos de Colecciones Biológicas de Guatemala en GBIF|.

---

## Sistema Nacional de Información Sobre Diversidad Biológica de Guatemala -SNIBgt-

El SNIBgt es un agregador de información basado en el [Atlas of Living Australia](https://living-atlases.gbif.org/participants/snibgt/). Esta plataforma es el agregado de información oficial del país, y es manejado por el Consejo Nacional de Áreas Protegidas.

|![LivingAtlas](https://user-images.githubusercontent.com/69399374/233875542-a8016d94-67b7-4fb4-9862-5f950e84cf70.jpg)|
|

Los datos de especímenes que integran este agregador provienen directamente de **GBIF**, por lo que las colecciones publicadas desde la instalación del **Portal de Biodiversidad de Guatemala** serán incorporadas automáticamente (aunque no actualizadas). No existe documentación disponible para conocer el procedimiento para actualizaro las colecciones captadas por el SNIBgt desde GBIF. 

Un tipo de archivo que sí puede ser incorporado directamente en el SNIBgt son los Listados de Especies. Desde el **Portal de Biodiversidad de Guatemala** se pueden generar búsquedas de ciertas regiones o grupos taxonómicos para elaborar estos listados (ver la sección de [**Listados de Especies en el Portal de Biodiversidad**](https://guatemalaportal.github.io/docs/listados/listados/)). Una vez generados estos listados, pueden ser incorporados al SNIBgt como un archivo de texto. 

- **Descarga de Listado de Especies desde el Portal de Biodiversidad**

**1.** Realizar una búsqueda con los parámetros deseados para generar un listado de especies.

|![PortalChecklist1](https://user-images.githubusercontent.com/69399374/233867636-6e87bd79-2da3-4f20-9980-eb8f657954b7.jpg)|

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


