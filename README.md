# Courses & Certificates

Repositorio personal para respaldar y organizar certificados, diplomas y constancias de cursos realizados, certificaciones obtenidas y formación complementaria.

El objetivo es mantener una copia ordenada de los documentos y, posteriormente, generar páginas web simples que permitan visualizar el contenido de forma más amigable.

## Contenido

| Sección | Descripción |
|---|---|
| [Cursos](courses/README.md) | Cursos, talleres y programas de formación organizados por categoría. |
| [Certificaciones](certifications/README.md) | Certificaciones profesionales, vigentes o caducadas, con su información de emisión y verificación cuando exista. |

## Organización sugerida

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

Este repositorio está en etapa inicial. Los documentos se irán incorporando progresivamente junto con sus datos principales: institución, fecha, categoría, estado y enlace de verificación si corresponde.

## Campos recomendados por documento

| Campo | Uso |
|---|---|
| Nombre | Nombre oficial del curso, diploma o certificación. |
| Institución | Entidad que emitió el documento. |
| Categoría | Área temática, por ejemplo desarrollo web, datos, cloud, ciberseguridad o idiomas. |
| Fecha | Año o fecha de emisión/finalización. |
| Estado | Vigente, caducado, completado o en progreso. |
| Archivo | Ruta al PDF, imagen o documento respaldado. |
| Verificación | Enlace público de validación, si existe. |

