# Paquete de diseño y trabajo docente

Este paquete pertenece al responsable del curso y a los instructores. Reúne reflexiones pedagógicas, decisiones, planificación, preparación de las sesiones y antecedentes. El paquete para entregar a estudiantes está separado en [01-estudiantes](../01-estudiantes/README.md).

## Recorrido recomendado

1. Leer el [diseño general](01-diseno-curso/diseno-general-curso.qmd) y el [marco epistemológico](01-diseno-curso/marco-epistemologico-ia-causalidad.qmd).
2. Consultar la [secuencia de nueve días](01-diseno-curso/contenido-tematico-y-experiencia-de-aprendizaje.qmd) y las guías de facilitación.
3. Revisar el programa, las actividades y la rúbrica en la parte estudiantil, que concentra las instrucciones de entrega.
4. Acudir a la [síntesis de decisiones](01-diseno-curso/decisiones-y-evolucion-del-curso.qmd), la bitácora y los antecedentes cuando se necesite examinar el rediseño.

El libro completo presenta primero diseño y facilitación, después materiales estudiantiles y al final memoria, desarrollo y organización. Los archivos mantienen sus carpetas por destinatario.

## Organización

| Carpeta | Contenido |
|---|---|
| `00-bitacora/` | Decisiones del responsable del curso, contexto de continuidad y registro de migración |
| `01-diseno-curso/` | Marco epistemológico, objetivos de diseño, progresión, arquitectura didáctica y propuesta de evaluación |
| `02-guias-instructores/` | Facilitación, pistas, soluciones orientativas, observación del aprendizaje y preparación técnica |
| `03-desarrollo/` | Materiales en preparación que todavía no se entregan, incluido el futuro ejemplo de orquestación |
| `90-antecedentes/` | Exportaciones de Vevox y otros insumos de revisión del curso |
| `99-archivo/` | Documentos históricos y respaldo de la estructura anterior |

## Guías para preparar las clases

- [Enseñar la bitácora analítica](02-guias-instructores/ensenar-bitacora-analitica.qmd).
- [Talleres RStudio: propósitos, pistas y soluciones](02-guias-instructores/guia-docente-prototipos.qmd).
- [Controversias: facilitación y revelación por rondas](02-guias-instructores/guia-docente-controversias.qmd).
- [Preparar la auditoría de reproducibilidad](02-guias-instructores/preparar-auditoria-reproducibilidad.qmd).

## Diseño y entrega son documentos distintos

Los [fundamentos docentes de evaluación](01-diseno-curso/evaluacion/rubrica-proyecto-y-reflexion.qmd) conservan sus motivos y estado de discusión. La [rúbrica estudiantil](../01-estudiantes/04-evaluacion/rubrica-proyecto-y-reflexion.qmd) contiene criterios, niveles y autoevaluación, sin el historial de rediseño. Si se modifican criterios o pesos, deben concordar en ambas versiones antes de una entrega. Los porcentajes actuales siguen siendo orientativos.

El [programa estudiantil](../01-estudiantes/00-curso/programa-del-curso.qmd) presenta descripción, objetivos, recorrido y productos; la secuencia interna explica cómo y por qué enseñarlos. No distribuir este paquete completo como material estudiantil.

La separación de carpetas organiza la entrega, pero no cambia permisos de acceso. Para distribuir el libro estudiantil, ejecutar `quarto render --profile estudiante` y compartir toda la carpeta `_book/estudiante/`. El perfil `docente` genera el libro completo en `_book/docente/`.
