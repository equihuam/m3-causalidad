# Entorno de trabajo en Codex: DeskTop

Verificación realizada el 8 de octubre de 2026, a solicitud del responsable del curso tras copiar el proyecto desde su LapTop.

## Proyecto local

La aplicación tiene registrado `m3-causalidad` como proyecto local en:

```text
C:\Users\equih\1 Nubes\OneDrive - El Instituto de Ecología\IA\2-Codex\m3-causalidad
```

Este chat utiliza esa carpeta como directorio de trabajo. Para continuar, abrir el proyecto `m3-causalidad` en Codex y trabajar en su carpeta local. `AGENTS.md` en la raíz contiene las instrucciones permanentes; conservarlo junto con las fuentes al trasladar el proyecto.

No se requieren rutas de la LapTop ni ajustes de modelo específicos para editar los materiales. Se mantienen los permisos y preferencias de la sesión de Codex.

## Estado comprobado

- Git disponible; rama `main`, sin commits ni remoto configurado. Los 256 archivos que ya estaban en el índice se conservaron. No se creó un commit ni se alteró el índice.
- Quarto 1.10.18 disponible desde la instalación de RStudio.
- Rscript disponible, con R 4.6.0.
- `nlme` disponible; `knitr`, `rmarkdown`, `ggplot2` y `dagitty` no disponibles en las bibliotecas de la sesión verificada.
- Los perfiles `docente` y `estudiante` mantienen salidas separadas. No se recompiló el libro durante esta preparación.

La edición con Codex está disponible. La compilación de los talleres requiere completar los paquetes de R; en una consola de R puede utilizarse:

```r
install.packages(c("knitr", "rmarkdown", "ggplot2", "dagitty"))
```

Después, desde la raíz del proyecto, compilar por separado:

```powershell
quarto render --profile docente
quarto render --profile estudiante
```

Antes de entregar a alumnos, comprobar navegación, búsqueda y recursos de `_book/estudiante/` y distribuir esa carpeta completa.

## Diagnóstico reutilizable

Desde la raíz del proyecto:

```powershell
quarto --version
git status --short --branch
Rscript --vanilla -e 'p <- c("knitr", "rmarkdown", "ggplot2", "dagitty", "nlme"); for (x in p) cat(x, requireNamespace(x, quietly=TRUE), "\n")'
```

El inicio normal de R emitió avisos de configuración regional `C.UTF-8`; revisar los archivos de inicio de R antes de compilar si esos avisos persisten. Esta preparación no cambió la configuración global de R.

## Trazabilidad

- **Decisión del usuario:** trabajar la copia en Codex desde el DeskTop.
- **Implementación del asistente:** verificar el registro local, las instrucciones, Git y las herramientas; documentar el entorno sin modificar los materiales del curso.
- **Pendiente técnico al diagnóstico inicial:** instalar los paquetes faltantes y validar ambas compilaciones cuando se necesite generar el libro.

## Actualización del 8 de octubre de 2026

**Decide:** responsable del curso. **Fuente:** solicitud explícita en el chat de instalar los paquetes faltantes, realizar el primer commit y utilizar `main` como rama principal de producción. **Implementa y registra:** asistente.

Instalados desde CRAN en la biblioteca personal de R del DeskTop y verificados en una sesión nueva:

| Paquete | Versión |
|---|---|
| knitr | 1.52 |
| rmarkdown | 2.32 |
| ggplot2 | 4.0.3 |
| dagitty | 0.3.4 |
| nlme (ya disponible) | 3.1.169 |

La biblioteca personal está en `C:/Users/equih/AppData/Local/R/win-library/4.6`. En esta sesión, el entorno restringido de Codex no puede acceder a ella; la comprobación con acceso autorizado sí carga los cinco paquetes. Las futuras compilaciones desde Codex pueden requerir ese acceso.

Se mantiene `main` como rama principal de producción y se prepara el commit inicial de esta copia. No hay remoto configurado ni publicación remota. La compilación de ambos perfiles continúa pendiente; instalar y cargar paquetes no verifica el libro completo.

Referencia sobre carpetas de proyectos y detección de instrucciones: [documentación oficial de OpenAI](https://learn.chatgpt.com/docs/projects).
