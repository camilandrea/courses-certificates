# Courses & Certificates

Repositorio personal para respaldar y organizar certificados, diplomas y constancias de cursos realizados, certificaciones obtenidas y formacion complementaria.

El objetivo es mantener una copia ordenada de los documentos y, posteriormente, generar paginas web simples que permitan visualizar el contenido de forma mas amigable.

## Contenido

| Seccion | Descripcion |
|---|---|
| [Cursos](courses/README.md) | Cursos, talleres y programas de formacion organizados por categoria. |
| [Certificaciones](certifications/README.md) | Certificaciones profesionales, vigentes o caducadas, con su informacion de emision y verificacion cuando exista. |

## Organizacion sugerida

```text
courses-certificates/
|-- courses/
|   |-- README.md
|   `-- <categoria>/
|       `-- <curso>/
|           |-- certificado.pdf
|           `-- README.md
|-- certifications/
|   |-- README.md
|   `-- <certificacion>/
|       |-- certificado.pdf
|       `-- README.md
`-- README.md
```

## Estado del repositorio

Este repositorio esta en etapa inicial. Los documentos se iran incorporando progresivamente junto con sus datos principales: institucion, fecha, categoria, estado y enlace de verificacion si corresponde.

## Campos recomendados por documento

| Campo | Uso |
|---|---|
| Nombre | Nombre oficial del curso, diploma o certificacion. |
| Institucion | Entidad que emitio el documento. |
| Categoria | Area tematica, por ejemplo desarrollo web, datos, cloud, ciberseguridad o idiomas. |
| Fecha | Anio o fecha de emision/finalizacion. |
| Estado | Vigente, caducado, completado o en progreso. |
| Archivo | Ruta al PDF, imagen o documento respaldado. |
| Verificacion | Enlace publico de validacion, si existe. |

