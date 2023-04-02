---
layout: default
title: Directorio GRSciColl
parent: Perfiles de Colecciones 
nav_order: 8
---


# Directorio Global de Colecciones GRSciColl
{: .no_toc }

<div class="code-example" markdown="1">
Herramienta externa
{: .label .label-red }
</div>


La Instalación Global de Información de Biodiversidad [(GBIF)](https://gbif.org) resguarda desde 2019 al Directorio Global de Colecciones, conocido por las siglas en inglés [GRSciColl](https://www.gbif.org/es/news/5kyAslpqTVxYqZTwYn1cub/gbif-provides-new-home-for-the-global-registry-of-scientific-collections). Este directorio busca ser un recurso centralizado para integrar la información de las Colecciones Biológicas en el mundo. 
{: .fs-5 .fw-300 }

---

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Integración de Información de Colecciones Biológicas en GRSciColl

El directorio [GRSciColl](https://www.gbif.org/es/grscicoll) es un recurso independiente y no es actualizado automáticamente a partir de los perfiles de publicadores institucionales (p.e. perfil del [CECON USAC](https://www.gbif.org/es/publisher/1eb0746b-24c4-40b7-9ed7-3381428e9648)) o de los perfiles de cada colección publicada en GBIF (p.e. [Colección de Moluscos USAC](https://www.gbif.org/es/dataset/a48ce09c-1e88-44bc-aa65-9db0d4c545db)). Las instituciones y colecciones biológicas, aún sin estar digitalizadas en el [Portal de Biodiversidad](https://biodiversidad.gt) o compartidas en GBIF (https://tinyurl.com/portalGBIF), deben dirigirse directamente a GRSciColl para ser registradas.  

[<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/GRSciColl.jpg?raw=true" alt="GRSciColl">
](https://www.gbif.org/es/grscicoll)

El directorio GRSciColl permite registrar información en dos categorías: **Información de Instituciones**, e **Información de Colecciones**. 

- Las **Instituciones** por lo general son universidades, institutos o museos que cuentan con una o varias colecciones biológicas o herbarios. El concepto de institución va a depender de los encargados y puede variar. Por lo general, estas decisiones se ven reflejadas últimamente en cómo los publicadores son inscritos en GBIF, pero puede variar en GRSciColl. Si vemos algunos casos en Guatemala, una universidad completa fue ser considerada una institución (p.e. [Universidad del Valle de Guatemala](https://www.gbif.org/publisher/5c1a4c27-795a-4294-aecc-46d7176706b7)), o dos departamentos dentro de la misma universidad pueden ser consideradas instituciones independientes (p.e. el [Centro de Estudios Conservacionistas](https://www.gbif.org/publisher/1eb0746b-24c4-40b7-9ed7-3381428e9648) y el [Sistema de Colecciones Biológicas de la Escuela de Biologia](https://www.gbif.org/es/publisher/bae69d55-51ab-4e97-a219-596ede861a55), ambos de la USAC). 

- Las **Colecciones** son cada uno de los subconjuntos de especímenes almacenados bajo una institución, generalmente agrupados por taxón. En ocasiones, varias colecciones comparten el mismo espacio físico, pero son distinguidas en sus perfiles digitales en el Portal de Biodiversidad y en GBIF. Por ejemplo, todas las colecciones de invertebrados acuáticos comparten el mismo espacio físico dentro del Sistema de Colecciones Biológicas USAC (en el Museo de Historia Natural), pero cada grupo posee su [perfil digital asociado a esta institución](https://www.gbif.org/dataset/search?publishing_org=bae69d55-51ab-4e97-a219-596ede861a55) y pueden ser registradas así en GRSciColl. Nuevamente, esta clasificación va a depender únicamente de cómo los encargados prefieran organizar las colecciones. 


<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/Jerarqu%C3%ADaGRSciColl.jpg?raw=true" alt="Jerarquía">


## Procedimiento para integrar instituciones y colecciones a GRSciColl

Antes de iniciar, los encargados deben tener clara la información y la organización de sus respectivas instituciones y colecciones. La información del Directorio únicamente puede ser cambiada por los editores autorizados de GBIF, pero cualquier persona asociada con las colecciones puede hacer sugerencias para que los datos sean actualizados. Es necesario dejar un correo como contacto, para que GBIF confirme la información sugerida.

### Instituciones

**1.** Ingresar en el [Directorio de GBIF](https://registry.gbif.org/institution/) y buscar las instituciones disponibles para [Guatemala](https://registry.gbif.org/institution/search?q=Guatemala). Si ve su institución, puede dar clic en el botón de **Sugerencia** para ver el formulario. Si no ve su institución, dar clic en el botón de **Crear Nuevo**.

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/GRSciCollInstituci%C3%B3n.jpg?raw=true" alt="GRSciColl Institución">

**2.** Completar o actualizar la información de la institución. 

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/GRSciCollSugerencia.jpg?raw=true" alt="GRSciColl Sugerencia">

**3.** Añadir información y correo electrónico al final del formulario, guardar y enviar.

**4.** La información será actualizada por un editor autorizado de GBIF.

**5.** Revisar que el acrónimo de la institución registrado en GRSciColl sea el mismo que se utiliza en el [Portal de Biodiversidad](htttps://biodiversidad.gt) para que los registros sean también vinculados al perfil de GRSciColl. Esta acción no es indispensable para la publicación adecuada de las colecciones en GBIF, pero evita el error "Institution match none", "Collection match none" y "Collection match fuzzy". 

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/InstitutionFuzzy.jpg?raw=true" alt="Institution Fuzzy">


### Colecciones

 Tener en cuenta que la Institución a la que pertenece la colección debe estar registrada en GRSciColl para poder vincular la información. 

**1.** Ingresar en el [Directorio de GBIF](https://registry.gbif.org/institution/) y buscar las colecciones disponibles para [Guatemala](https://registry.gbif.org/institution/search?q=Guatemala). Si ve su institución, puede dar clic en el botón de **Sugerencia** para ver el formulario.

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/GRSciCollColecci%C3%B3n.jpg?raw=true" alt="GRSciColl Colección">

**2.** Completar o actualizar la información de la colección. 

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/GRSciCollColSugerencia.jpg?raw=true" alt="GRSciColl Sugerencia">

**3.** Añadir información y correo electrónico al final del formulario, guardar y enviar.

**4.** La información será actualizada por un editor autorizado de GBIF.

**5.** Revisar que el acrónimo de la colección registrado en GRSciColl sea el mismo que se utiliza en el Portal de Biodiversidad para que los registros sean también vinculados al perfil de este directorio. Esta acción no es indispensable para la publicación adecuada de las colecciones en GBIF, pero evita el error "Collection match none" con el acrónimo. Próximamente será posible agregar el GUID generado en el Portal de Biodiversidad para cada colección como identificador Symbiota en GRISciColl. Esto evitará el error de "Collection match none" en campo Collection ID (actualización en progreso por el equipo de GBIF). 

<img src="https://github.com/GuatemalaPortal/guatemalaportal.github.io/blob/main/static/portal/CollectionFuzzy.jpg?raw=true" alt="Institution Fuzzy">


## Colecciones compartidas en el Portal de Biodiversidad 

A continuación se presenta un listado de colecciones compartidas en el Portal de Biodiversidad de Guatemala, bajo sus respectivas instituciones. La información ingresada en cada perfil es mantenida por los curadores y encargados de las colecciones, por lo que podría ser utilizado como guía para sugerir actualizaciones en GRSciColl.

### Universidad del Valle de Guatemala
- [Colección de Artrópodos (UVGC)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=16): Ocurrencias, especímenes preservados.
- [Colección de Crustáceos (UVGCR)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=48): Ocurrencias, especímenes preservados.
- [Colección de Equinodermos (UVGEC)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=44): Ocurrencias, especímenes preservados.
- [Colección de Moluscos (UVGMOL)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=27): Ocurrencias, especímenes preservados.
- [Colección de Anfibios (UVGA)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=3): Ocurrencias, especímenes preservados.
- [Colección de Aves (UVGAV)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=2): Ocurrencias, especímenes preservados.
- [Colección de Mamíferos (UVGM)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=4): Ocurrencias, especímenes preservados.
- [Colección de Peces (UVGFI)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=5): Ocurrencias, especímenes preservados.
- [Colección de Reptiles (UVGR)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=6): Ocurrencias, especímenes preservados.
- [Colección de Orquídeas (UVGO)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=22): Ocurrencias, especímenes vivos.
- [Colección de Bromelias (UVGB)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=104): Ocurrencias, especímenes vivos.
- [Colección de Registros Fotográficos (UVGF)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=7): Ocurrencias, observaciones.
- [Colección de Tejidos (UVGT)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=81): Ocurrencias, especímenes preservados/muestras.
- [Herbario UVAL (UVAL)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=19): Ocurrencias, especímenes preservados.

### Escuela de Biología, Universidad de San Carlos
- [Colección de Anélidos Clitelados (USACClitellata)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=110): Ocurrencias, especímenes preservados.
- [Colección de Cnidarios (USACCni)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=73): Ocurrencias, especímenes preservados.
- [Colección de Entomología (USAC)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=17): Ocurrencias, especímenes preservados.
- [Colección de Equinodermos (USACEchi)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=74): Ocurrencias, especímenes preservados.
- [Colección de Moluscos (USACMol)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=26): Ocurrencias, especímenes preservados.
- [Colección de Porifera (USACPor)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=75): Ocurrencias, especímenes preservados.
- [Colección de Aves (USACA)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=9): Ocurrencias, especímenes preservados.
- [Colección de Mamíferos (USACM)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=1): Ocurrencias, especímenes preservados.
- [Colección Ictiológica (USACI)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=10): Ocurrencias, especímenes preservados.
- [Colección Paleontológica (USACPal)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=50): Ocurrencias, fósiles.
- [Colección de Registros Fotográficos de Vertebrados (USACF)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=8): Ocurrencias, observaciones.

### Centro de Estudios Conservacionistas, Universidad de San Carlos
- [Herbario USCG-CECON (USCG)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=21): Ocurrencias, especímenes preservados.
- [Herbario USCG-CECON Hongos (USCG-Hongos)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=69): Ocurrencias, especímenes preservados.
- [Herbario USCG-CECON Líquenes (USCG-Líquenes)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=91): Ocurrencias, especímenes preservados.

### Centro Universitario de Zacapa
- [Colección de Aves de Zacapa (CAZ)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=49): Ocurrencias, especímenes preservados.
- [Colección de Insectos de Zacapa (IZC)](https://biodiversidad.gt/portal/collections/misc/collprofiles.php?collid=43): Ocurrencias, especímenes preservados.

<div class="code-example" markdown="1">

<span class="fs-5">
[Ir a Documentación de Symbiota](https://biokic.github.io/symbiota-docs/es/coll_manager/data_publishing/gbif/){: .btn .btn-green }
</span>

</div>
