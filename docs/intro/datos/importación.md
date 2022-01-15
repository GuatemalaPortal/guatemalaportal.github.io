---
layout: default
title: Importación de datos
parent: Ingreso de Datos
grand_parent: Primeros Pasos
nav_order: 2
---

# Importación de datos de fuentes externas
{: .no_toc }

<div class="code-example" markdown="1">
Colecciones en vivo
{: .label .label-blue }

Colecciones snapshot
{: .label .label-yellow }

Administradores
{: .label .label-green }

</div>

Si los encargados de colecciones ya cuentan con una base de datos externa, es posible importarla hacia el perfil en el Portal de Biodiversidad. La importación puede hacerse a partir de archivos de texto, archivos Darwin Core, o mediante una importación directa desde plataformas externas.  

**Únicamente los administradores de las colecciones tienen permisos para importar datos.**

## Contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Importación de archivos de texto

- Dirigirse al [Portal de Biodiversidad](https://biodiversidad.gt) e iniciar sesión.
- Una vez en el portal, ir a **“Mi Perfil”** (My profile).
- En “Mi Perfil”, seleccionar **"Manejo de Especímenes"** (Specimen Management).
- Al ingresar en Manejo de Especímenes, seleccionar la colección en la que se desea trabajar en el recuadro de **"Manejo de Colecciones"** (Collection Management).
- Al ingresar en la colección deseada, dirigirse al **Panel de Administración** y seleccionar **"Importar/Actualizar Registros de Especímenes"**. 

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/Importar%20registros.jpg?raw=true" alt="Logo" >


- Elegir **"Carga rápida de archivos"**.
- Cargar un archivo .csv con los [campos requeridos](https://docs.google.com/spreadsheets/d/1umCUAUWjfFIhBObihmrv9zCIyunEb6tK7wB0bm1lCYY/edit#gid=0), o mapear los campos a los aceptados por el Portal (formato DarwinCore). 
- Seleccionar “Match on Catalog Number” para evitar duplicados, en caso de que el registro ya estuviera ingresado previamente. Seleccionar “Start Upload” para cargar el archivo.
- Finalmente, seleccionar “Transfer Records to Central Specimen Table” .
- Si los datos fueron cargados correctamente aparecerán los siguientes mensajes. El último debe decir “Upload Procedure Complete”




