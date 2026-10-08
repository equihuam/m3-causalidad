# Reorganización por destinatario — 10 de septiembre de 2026

**Decisión del responsable del curso:** separar un paquete propio y para instructores, con reflexiones y decisiones pedagógicas, de otro con todo lo que se entrega a estudiantes.

**Implementación del asistente:** nombres `00-docencia/` y `01-estudiantes/`, distribución interna, adaptación de documentos mixtos e índices. Se mantuvo la finalidad y la secuencia del curso.

## Preservación y comprobación

Se respaldaron los 154 archivos previos (sin `.git`) en `../99-archivo/estructura-anterior-2026-09-10.zip`. Se trasladaron 152 archivos y se verificó su SHA-256 antes de editar enlaces y separar contenidos. Sólo se retiraron directorios antiguos vacíos. El [manifiesto](migracion-carpetas-2026-09-10.json) conserva rutas y huellas anteriores.

## Materiales adaptados

- Programa para estudiantes: derivado de los objetivos y la secuencia del diseño interno, con descripción y productos, sin reflexiones sobre el rediseño.
- Rúbrica estudiantil: conserva los ocho criterios, niveles y pesos orientativos. La propuesta completa con justificación permanece en docencia. Mantener ambas alineadas cuando cambien los criterios.
- Auditoría de reproducibilidad: la preparación técnica se trasladó a una guía docente; la actividad conserva las consignas y evidencias exigidas.
- Índices de talleres y controversias: redactados para alumnos; las guías de facilitación quedaron en docencia. El código guiado y los ejemplos resueltos que forman parte de la secuencia de aprendizaje siguen en las actividades.
- Lecturas PDF: en el paquete estudiantil. Exportaciones Vevox y archivo histórico: exclusivamente en docencia.

Las rutas de esta tabla documentan la migración. No deben copiarse como una estructura adicional activa.

## Mapa de fuentes y materiales

| Origen anterior | Destino actual |
|---|---|
| `00-bitacora/bitacora-maestra.qmd` | `00-docencia/00-bitacora/bitacora-maestra.qmd` |
| `00-bitacora/Prompt de arrastre para m3-causalidad.md` | `00-docencia/00-bitacora/Prompt de arrastre para m3-causalidad.md` |
| `01-diseno-curso/arquitectura-actividades-rstudio.qmd` | `00-docencia/01-diseno-curso/arquitectura-actividades-rstudio.qmd` |
| `01-diseno-curso/competencia-reproducibilidad-analitica.qmd` | `00-docencia/01-diseno-curso/competencia-reproducibilidad-analitica.qmd` |
| `01-diseno-curso/contenido-tematico-y-experiencia-de-aprendizaje.qmd` | `00-docencia/01-diseno-curso/contenido-tematico-y-experiencia-de-aprendizaje.qmd` |
| `01-diseno-curso/decisiones-y-evolucion-del-curso.qmd` | `00-docencia/01-diseno-curso/decisiones-y-evolucion-del-curso.qmd` |
| `01-diseno-curso/diseno-general-curso.qmd` | `00-docencia/01-diseno-curso/diseno-general-curso.qmd` |
| `01-diseno-curso/marco-epistemologico-ia-causalidad.qmd` | `00-docencia/01-diseno-curso/marco-epistemologico-ia-causalidad.qmd` |
| `02-materiales-docente/ensenar-bitacora-analitica.qmd` | `00-docencia/02-guias-instructores/ensenar-bitacora-analitica.qmd` |
| `03-materiales-estudiantes/ficha-entrega-reproducible.qmd` | `01-estudiantes/01-guias/ficha-entrega-reproducible.qmd` |
| `03-materiales-estudiantes/guia-bitacora-analitica.qmd` | `01-estudiantes/01-guias/guia-bitacora-analitica.qmd` |
| `04-guias-cheatsheets/guia-continuidad-ia-free-tier.qmd` | `01-estudiantes/01-guias/guia-continuidad-ia-free-tier.qmd` |
| `05-actividades/2026-m3-bienvenida_2026-02-07_12-00-0600.xlsx` | `00-docencia/90-antecedentes/vevox/2026-m3-bienvenida_2026-02-07_12-00-0600.xlsx` |
| `05-actividades/2026-m3-epistemología_2026-01-31_12-59-0600.xlsx` | `00-docencia/90-antecedentes/vevox/2026-m3-epistemología_2026-01-31_12-59-0600.xlsx` |
| `05-actividades/2026-m3-Prueba_estadística_de_hipótesis_2026-01-27_15-41-0600.xlsx` | `00-docencia/90-antecedentes/vevox/2026-m3-Prueba_estadística_de_hipótesis_2026-01-27_15-41-0600.xlsx` |
| `05-actividades/auditoria-epistemologica-ia.qmd` | `01-estudiantes/02-actividades/auditoria-epistemologica-ia.qmd` |
| `05-actividades/auditoria-reproducibilidad-analitica.qmd` | `01-estudiantes/02-actividades/auditoria-reproducibilidad-analitica.qmd` |
| `05-actividades/lectura-1.pdf` | `01-estudiantes/03-lecturas/lectura-1.pdf` |
| `05-actividades/lectura-2.pdf` | `01-estudiantes/03-lecturas/lectura-2.pdf` |
| `05-actividades/lectura-3.pdf` | `01-estudiantes/03-lecturas/lectura-3.pdf` |
| `06-rubricas/rubrica-proyecto-y-reflexion.qmd` | `00-docencia/01-diseno-curso/evaluacion/rubrica-proyecto-y-reflexion.qmd` |
| `99-archivo/bitacora-mixta-antes-separacion-2026-09-10.qmd` | `00-docencia/99-archivo/bitacora-mixta-antes-separacion-2026-09-10.qmd` |
| `99-archivo/reporte_conversacion_agentes.md` | `00-docencia/99-archivo/reporte_conversacion_agentes.md` |
| `05-actividades/controversias-ia/01-germinacion-y-causalidad.qmd` | `01-estudiantes/02-actividades/controversias-ia/01-germinacion-y-causalidad.qmd` |
| `05-actividades/controversias-ia/02-controlar-todas-las-variables.qmd` | `01-estudiantes/02-actividades/controversias-ia/02-controlar-todas-las-variables.qmd` |
| `05-actividades/controversias-ia/03-muchas-observaciones-pocas-replicas.qmd` | `01-estudiantes/02-actividades/controversias-ia/03-muchas-observaciones-pocas-replicas.qmd` |
| `05-actividades/controversias-ia/guia-docente-controversias.qmd` | `00-docencia/02-guias-instructores/guia-docente-controversias.qmd` |
| `05-actividades/controversias-ia/README.md` | `01-estudiantes/02-actividades/controversias-ia/README.md` |
| `05-actividades/prototipos-rstudio/00-introduccion-dagitty-web-r.qmd` | `01-estudiantes/02-actividades/talleres-rstudio/00-introduccion-dagitty-web-r.qmd` |
| `05-actividades/prototipos-rstudio/01-factorial-completamente-aleatorizado.qmd` | `01-estudiantes/02-actividades/talleres-rstudio/01-factorial-completamente-aleatorizado.qmd` |
| `05-actividades/prototipos-rstudio/02-bloques-aleatorizados.qmd` | `01-estudiantes/02-actividades/talleres-rstudio/02-bloques-aleatorizados.qmd` |
| `05-actividades/prototipos-rstudio/03-parcela-dividida.qmd` | `01-estudiantes/02-actividades/talleres-rstudio/03-parcela-dividida.qmd` |
| `05-actividades/prototipos-rstudio/guia-docente-prototipos.qmd` | `00-docencia/02-guias-instructores/guia-docente-prototipos.qmd` |
| `05-actividades/prototipos-rstudio/README.md` | `01-estudiantes/02-actividades/talleres-rstudio/README.md` |

## Fuentes nuevas de entrega

- `01-estudiantes/00-curso/programa-del-curso.qmd`.
- `01-estudiantes/04-evaluacion/rubrica-proyecto-y-reflexion.qmd`.
- `00-docencia/02-guias-instructores/preparar-auditoria-reproducibilidad.qmd`.

Los README se renovaron por destinatario. Los HTML afectados deben regenerarse desde las fuentes vigentes. Los cuatro talleres con código R conservan sus salidas de referencia si no cambió su contenido analítico; su traslado no acredita una nueva ejecución científica.

## Verificación de cierre

Se completó la generación de las 26 fuentes e índices que requerían HTML actualizado y se revisaron 34 HTML en total, incluidos los materiales sin cambios de contenido. Se comprobaron 117 enlaces de fuentes y 325 enlaces o recursos HTML, sin errores ni dependencias del paquete estudiantil hacia docencia. Los enlaces HTML que disponen de una versión de lectura apuntan a esa versión; los enlaces de fuentes conservan sus destinos editables.

Los 154 archivos originales tienen un destino registrado; lecturas, exportaciones y antecedentes archivados conservaron sus huellas. Las rúbricas interna y estudiantil mantienen los mismos ocho pesos, con total 100 %. El [informe de verificación](verificacion-estructura-2026-09-10.json) conserva los resultados. Esta comprobación valida organización y navegación, no vuelve a ejecutar los análisis científicos de los talleres ni el futuro flujo Snakemake.
