# M3 Causalidad, diseño experimental e IA

Curso intensivo de nueve días, organizado en dos paquetes según quién utilizará los materiales.

## Libro Quarto: dos ediciones

Abre el proyecto existente `m3-causalidad.Rproj`. `_quarto.yml` contiene opciones comunes; `_quarto-docente.yml` y `_quarto-estudiante.yml` definen capítulos y recursos independientes. `index.qmd` adapta su portada al perfil activo.

| Perfil | Contenido | Salida |
|---|---|---|
| `docente` (predeterminado) | Libro completo | `_book/docente/index.html` |
| `estudiante` | Programa, guías, actividades, lecturas y evaluación | `_book/estudiante/index.html` |

Ejecuta cada edición por separado:

```bash
quarto render --profile docente
quarto render --profile estudiante
```

Para vista previa, utiliza `quarto preview --profile docente` o `quarto preview --profile estudiante`. Sin perfil explícito se utiliza `docente`, también desde RStudio. No combines ambos perfiles en un comando. Los talleres requieren R y los paquetes `knitr`, `rmarkdown`, `ggplot2`, `dagitty` y `nlme`.

Para entregar el libro estudiantil, distribuye **toda la carpeta `_book/estudiante/`**, incluidos sus recursos y fuentes `.qmd` para los ejercicios. No compartas `_book/` completo. La antigua salida `_book/index.html` es la edición integral anterior; usa las nuevas rutas.

Agrega los nuevos capítulos al perfil correspondiente; los materiales estudiantiles deben figurar en ambos perfiles. Los recursos docentes se declaran únicamente en `_quarto-docente.yml`. Las fuentes conservan sus carpetas canónicas. La entrega vigente se reconstruye con el perfil correspondiente; los HTML junto a las fuentes son salidas independientes anteriores.

## Entradas principales

- **[Docencia: responsable del curso e instructores](00-docencia/README.md).** Diseño, reflexiones y decisiones pedagógicas, planificación, guías de facilitación, desarrollo y antecedentes.
- **[Estudiantes: materiales de entrega](01-estudiantes/README.md).** Descripción del curso, objetivos, guías, tareas, ejercicios, lecturas y evaluación.

## Estructura canónica

```text
m3-causalidad/
├── AGENTS.md
├── README.md
├── _quarto.yml
├── _quarto-docente.yml
├── _quarto-estudiante.yml
├── index.qmd
├── m3-causalidad.Rproj
├── 00-docencia/
│   ├── README.md
│   ├── 00-bitacora/
│   ├── 01-diseno-curso/
│   │   └── evaluacion/
│   ├── 02-guias-instructores/
│   ├── 03-desarrollo/
│   ├── 90-antecedentes/
│   │   └── vevox/
│   └── 99-archivo/
└── 01-estudiantes/
    ├── README.md
    ├── 00-curso/
    ├── 01-guias/
    ├── 02-actividades/
    │   ├── talleres-rstudio/
    │   └── controversias-ia/
    ├── 03-lecturas/
    └── 04-evaluacion/
```

## Regla de ubicación

Si un documento explica **por qué o cómo diseñamos y enseñamos**, pertenece a docencia. Si está redactado **para que el estudiante comprenda, haga, consulte o entregue algo**, pertenece a estudiantes. Los documentos mixtos se separan por destinatario. La bitácora de diseño pertenece a docencia; la guía para que cada alumno lleve su propia bitácora pertenece a estudiantes.

Para entregar el libro, compilar el perfil `estudiante` y compartir `_book/estudiante/`. Para compartir únicamente las fuentes de trabajo, utilizar `01-estudiantes/`. Sus enlaces locales no deben depender de docencia. Esta organización no impone permisos: compartir el repositorio completo también comparte el paquete docente.

Los `.qmd` son las fuentes editables y los HTML sus salidas de consulta. Una actualización de fuentes debe reflejarse en sus HTML antes de distribuirlos. Las guías docentes pueden enlazar materiales estudiantiles; el sentido inverso se evita.

El programa y la rúbrica para estudiantes se mantienen alineados con el diseño interno, sin trasladar al alumno el historial de decisiones. Los pesos de evaluación siguen siendo orientativos. El ejemplo ejecutable Snakemake permanece en desarrollo y todavía no se incluye como material disponible.

## Trazabilidad de la reorganización

La separación por destinatario fue solicitada por el responsable del curso. Los nombres y subcarpetas concretos implementan esa solicitud. Se conserva un respaldo íntegro y un [mapa de rutas anteriores y actuales](00-docencia/00-bitacora/migracion-estructura-2026-09-10.md).

La [bitácora docente](00-docencia/00-bitacora/bitacora-maestra.qmd) registra esta decisión. La [guía estudiantil de bitácora](01-estudiantes/01-guias/guia-bitacora-analitica.qmd) explica la competencia de reproducibilidad que practicarán los alumnos.


## Coherencia editorial

El programa estudiantil concentra objetivos y productos; su rúbrica concentra niveles y pesos propuestos. Los capítulos docentes desarrollan fundamentos, secuencia y facilitación sin duplicar esas consignas. La bitácora es el registro de decisiones; la síntesis de evolución sólo orienta su consulta.

La edición completa dispone la memoria y los antecedentes al final. La revisión está documentada en el [informe editorial](00-docencia/00-bitacora/revision-editorial-2026-09-11.md). Los respaldos conservan las versiones previas; la entrega vigente se genera desde los perfiles.
