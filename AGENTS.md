# Instrucciones permanentes

- Este repositorio corresponde a un curso intensivo de 9 días sobre teoría causal, diseño experimental e inteligencia artificial.
- El curso mantiene un enfoque epistemológico de la causalidad.
- La IA se utiliza como herramienta de exploración, razonamiento, crítica y apoyo al trabajo científico, no como autoridad.
- Debe distinguirse explícitamente entre plausibilidad, evidencia, inferencia y causalidad.
- Las alucinaciones de IA se tratan como resultados posibles de una navegación probabilística insuficientemente anclada en evidencia.
- La creatividad expande el espacio de posibilidades; la evidencia lo restringe.
- El pensamiento contrafáctico es un puente central entre imaginación, causalidad e inferencia científica.
- La trazabilidad es un objetivo pedagógico: registrar decisiones, cambios de interpretación, evidencia y cambios de confianza.
- Los materiales para estudiantes deben poder utilizarse en modalidad free tier.
- Preferir Markdown y Quarto para los documentos.
- No modificar de forma destructiva documentos existentes.
- Antes de cambios grandes, revisar la estructura del repositorio y mantener consistencia de nombres.
- Cuando sea útil, registrar decisiones importantes en `00-docencia/00-bitacora/bitacora-maestra.qmd`.
- `00-docencia/00-bitacora/bitacora-maestra.qmd` es exclusivamente la bitácora del responsable del curso sobre decisiones de diseño. Registrar quién decide, fuente y estado; distinguir decisiones del usuario de propuestas del asistente y de su implementación.
- La bitácora analítica del estudiante es una competencia diferente. Sus instrucciones y plantilla están en `01-estudiantes/01-guias/guia-bitacora-analitica.qmd`; cada alumno o equipo la lleva en su proyecto. No mezclarla con la bitácora docente.

- La estructura canónica se divide por destinatario: `00-docencia/` contiene decisiones, reflexiones y diseño pedagógico, guías para instructores, desarrollo y antecedentes; `01-estudiantes/` contiene exclusivamente materiales redactados para entregar al alumno.
- Los documentos mixtos deben separarse por destinatario. No enlazar desde el paquete estudiantil a archivos docentes ni distribuir antecedentes, exportaciones de participación o guías de soluciones como parte de la entrega estudiantil.
- Mantener los README de ambos paquetes, enlaces relativos y HTML alineados con las fuentes. El programa y la rúbrica de entrega deben concordar con sus fundamentos docentes; las propuestas no se presentan como decisiones ya adoptadas.
- La bitácora de diseño vigente es `00-docencia/00-bitacora/bitacora-maestra.qmd`; la guía estudiantil es `01-estudiantes/01-guias/guia-bitacora-analitica.qmd`. No recrear las antiguas carpetas temáticas en la raíz.

- El libro utiliza perfiles Quarto: `docente` (predeterminado, completo) y `estudiante` (sólo entrega estudiantil). Mantener capítulos y recursos por perfil; no poner listas docentes en la configuración común. Compilar cada perfil por separado. Distribuir `_book/estudiante/` completo a alumnos; verificar que su navegación, búsqueda y recursos no incluyan `00-docencia/`.
