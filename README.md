# ShoeSync

Sistema de gestión de inventario y sincronización de stock para **ShoeStore Ecuador**.

ShoeSync controla el stock por modelo, talla y color en cada sucursal, registra las entradas, salidas y ajustes desde un módulo móvil, y envía automáticamente el stock disponible a la tienda en línea, para que nunca se venda en línea un par que no existe en bodega.

| | |
|---|---|
| **Cliente** | ShoeStore Ecuador — representante: Martha Villacís |
| **Curso** | Ingeniería de Software I — ESPOL — PAO II 2026 |
| **Docente** | Dr. Carlos Mera-Gómez |
| **Entregable** | Proyecto de medio término: Especificación de Requerimientos de Software (IEEE 830) |

## Integrantes — Grupo 2

- Ayala Hurtado Danna Antonella
- Echeverría Moreno Samuel Javier
- Estrada Lara Windsor Alexander
- Gualotuña Andrade Juan Andrés
- Torres Garcés Zuleyka Nathalie

## Enlaces principales

- 📄 **Documento de requerimientos (PDF):** [documento/ShoeSync-SRS-v3.pdf](documento/ShoeSync-SRS-v3.pdf)
- 🖥️ **Prototipo navegable (Figma):** [abrir prototipo](https://www.figma.com/LINK) <!-- reemplazar por el enlace real -->
- 🗺️ **Flujo de pantallas:** [prototipo/flujo-pantallas.png](prototipo/flujo-pantallas.png)

## Contenido del repositorio

| Carpeta | Qué contiene |
|---|---|
| [`documento/`](documento/) | PDF final del SRS, código LaTeX de Overleaf y versiones anteriores (CONOPS v1.0, borrador v2.0) |
| [`evidencias/entrevistas/`](evidencias/entrevistas/) | Guía de entrevista, actas firmadas y grabaciones (con permiso) |
| [`evidencias/observacion/`](evidencias/observacion/) | Notas y fotos de la observación del trabajo en bodega y tienda |
| [`evidencias/analisis-documental/`](evidencias/analisis-documental/) | Muestra anonimizada del registro de inventario actual y notas del análisis |
| [`evidencias/cuestionario/`](evidencias/cuestionario/) | Formulario, respuestas y resumen de resultados |
| [`evidencias/revision-requerimientos/`](evidencias/revision-requerimientos/) | Hallazgos de la revisión entre pares y con la clienta, y cómo se corrigieron |
| [`evidencias/validacion/`](evidencias/validacion/) | Acta de la sesión de validación del prototipo, acta de conformidad firmada y comunicaciones |
| [`prototipo/`](prototipo/) | Enlace al prototipo, capturas P-01 a P-15, diagrama de flujo y prompt usado en Figma Make |
| [`gestion/`](gestion/) | Product backlog, cronograma y mapa de stakeholders |

## Técnicas de levantamiento de requerimientos

| Técnica | Con quién | Fecha | Evidencia |
|---|---|---|---|
| Entrevista estructurada | Martha Villacís | 2026-10-18 | [entrevistas/](evidencias/entrevistas/) |
| Entrevista de seguimiento | Martha Villacís | 2026-10-18 | [entrevistas/](evidencias/entrevistas/) |
| Análisis documental | Área administrativa | AAAA-MM-DD | [analisis-documental/](evidencias/analisis-documental/) |
| Prototipado | Martha Villacís y un bodeguero | 2026-11-09 | [prototipo/](prototipo/), [validacion/](evidencias/validacion/) |
| Revisión de requerimientos | Equipo y clienta | AAAA-MM-DD | [revision-requerimientos/](evidencias/revision-requerimientos/) |

## Metodología

El equipo trabaja con **Scrum**: product backlog con las historias de usuario del Apéndice A del documento, sprints de 2 semanas y una reunión de revisión con la clienta al final de cada sprint. Protocolo de comunicación acordado con la clienta: cada reunión genera un acta, y un documento se considera aprobado si no hay respuesta en 48 horas.

## Resumen del documento

- **61 requerimientos funcionales** (38 Must, 18 Should, 5 Could), agrupados por módulo: usuarios, sucursales, catálogo, inventario, movimientos, sincronización, reportes, componente académico e integración con GP.
- **30 requerimientos no funcionales**, clasificados según Sommerville (producto, organizacionales y externos), cada uno con métrica y criterio de validación.
- **Historias de usuario** con criterios de aceptación y trazabilidad a los requerimientos.
- **Prototipo** web (Administrador) y móvil (Bodeguero y Vendedor).

## Privacidad

Las evidencias no contienen datos personales de clientes ni empleados de ShoeStore Ecuador (Ley Orgánica de Protección de Datos Personales). Las grabaciones y fotos se publican solo con autorización.
