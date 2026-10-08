# Revisión editorial general — 11 de septiembre de 2026

## Alcance y criterio

Revisión solicitada por el responsable del curso para depurar repeticiones, redundancias e inconsistencias del proceso de rediseño. Se examinaron las fuentes de ambas ediciones: diseño, secuencia, guías, evaluación, actividades, índices y memoria. Los PDF de lectura y XLSX históricos se conservaron; esta revisión no equivale a una nueva evaluación bibliográfica ni a un análisis de participación.

Se conservaron los nueve días, la pregunta propia como hilo conductor, los productos, el enfoque epistemológico y la prioridad de reproducibilidad. Los pesos existentes siguen siendo propuestos. Las simplificaciones de redacción y organización son implementación del asistente, no nuevas decisiones sustantivas atribuidas al responsable.

## Hallazgos y cambios

| Hallazgo | Depuración |
|---|---|
| Listas de objetivos reiteradas y ligeramente distintas | Una lista agrupada en ocho objetivos en el programa estudiantil; diseño y secuencia remiten a ella |
| Rúbrica completa duplicada en la edición docente | Descriptores y pesos en la rúbrica estudiantil; fundamentos y aplicación en el capítulo docente |
| Principios epistemológicos repetidos en casi todos los documentos de diseño | Desarrollo conceptual en el marco y referencias breves en los demás capítulos |
| Propuestas de Snakemake, tiempos y pesos presentadas a veces como decisiones | Estado explícito y uniforme; el piloto ejecutable continúa pendiente |
| Inventarios antiguos, contexto conversacional y diseños futuros dentro de la lectura vigente | Memoria al final del libro; textos históricos preservados y contexto actual resumido |
| Una salida en algunas consignas y tabla más figura en otras | Un resultado principal con valores de comprobación; salidas complementarias opcionales |
| Riesgo de multiplicar fichas y entradas por cada actividad | Ficha como índice del anexo final; bitácora y registros enlazados, sin transcripción obligatoria |
| Categorías que mezclaban tipo de afirmación, respaldo y causalidad | Tres dimensiones explícitas; «verificada» debe indicar qué se comprobó |
| Auditoría estudiantil con instrucciones internas para preparar errores | Consigna operativa, con el caso de germinación disponible como punto de partida |
| Dos escenarios de asignación tratados como revelaciones acumulativas | Escenarios A y B explícitamente alternativos; cuatro sitios y dos decisiones aleatorias por pares |
| Información «nueva» ya anunciada en la controversia de ajuste | Rondas de revisión del estimando y la selección; aclaración del alcance de la salida de Dagitty |
| Minirreportes que pedían conservar sólo el texto resumido | Diferenciar informe de lectura y fuentes ejecutables; conservar ambos |
| Figura factorial con desplazamiento aleatorio sin semilla propia | Semilla explícita para la posición de los puntos |
| Arquitectura con `lmer` frente a taller disponible en `nlme` | Alinear la descripción con `nlme::lme`; separar extensiones no desarrolladas |
| Evaluación de actualización selectiva sin flujo disponible | Distinguirla de reconstrucción completa y exigir práctica previa antes de evaluarla |

En los documentos comparables se revisaron 36 fuentes con cambios. Pasaron de 43,257 a 28,380 palabras aproximadamente (34.4 % menos), excluyendo este informe nuevo. La reducción incluye el traslado de historia a respaldos y la sustitución de repeticiones por referencias, no la eliminación de capacidades de aprendizaje.

## Correspondencia de objetivos

La agrupación no elimina capacidades de la lista anterior:

| Objetivo actual | Objetivos anteriores integrados |
|---|---|
| 1. Pregunta y contraste causal | 1, 2, 6 |
| 2. Representación y supuestos | 3, 4 |
| 3. Comparaciones y validez | 5, 7 |
| 4. Afirmaciones y pruebas | 8, 9, 10 |
| 5. IA crítica y gratuita | 8, 11, 13 |
| 6. Trazabilidad y continuidad | 12, 14 |
| 7. Reconstrucción y auditoría | 16, 17 |
| 8. Reflexión argumentada | 15 |

## Preservación

Las 43 fuentes previas, incluida la configuración y el proyecto RStudio, están en [el respaldo con manifiesto SHA-256](../99-archivo/fuentes-antes-depuracion-2026-09-11.zip). También se conserva la bitácora previa completa y el contexto histórico en el archivo. Los antecedentes no se reescribieron como decisiones nuevas.

## Verificación

Comprobaciones completadas:

- Fuentes y capítulos presentes: 40 páginas docentes y 20 estudiantiles.
- Nueve jornadas; tiempos integrados de 250 minutos y pesos propuestos que suman 100 %, sin cambiar su estado de propuesta.
- Compilación HTML completa de ambos perfiles, con ejecución de los talleres R.
- Revisión de 1 201 enlaces, recursos y destinos internos en estudiantes y 3 071 en docente: sin errores. Se verificaron también los identificadores de sección.
- Edición estudiantil sin archivos, navegación ni referencias de búsqueda a `00-docencia/`, con sus fuentes `.qmd` disponibles.
- Archivo RStudio intacto, comprobado mediante SHA-256.
- Búsqueda complementaria de párrafos idénticos de al menos 40 palabras entre capítulos activos: sin duplicados encontrados.

El [registro técnico](verificacion-editorial-2026-09-11.json) conserva los resultados de la verificación HTML completa. Los conteos corresponden al libro antes de agregar este cierre; la actualización de esta página añade enlaces de documentación.

## Pendientes que conserva el curso

Confirmar ponderaciones y carga mediante decisión docente; desarrollar y probar el flujo de orquestación y su entorno; pilotar las actividades. Compilar y revisar los textos no demuestra todavía eficacia pedagógica ni reproducibilidad de un flujo inexistente.
