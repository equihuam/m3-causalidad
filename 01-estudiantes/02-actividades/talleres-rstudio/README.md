# Talleres en RStudio

Trabaja en parejas y escribe tu predicción antes de ejecutar el código. Alternen quién conduce RStudio y quién revisa las decisiones.

1. [Introducción a Dagitty: web y R](00-introduccion-dagitty-web-r.qmd).
2. [Factorial completamente aleatorizado](01-factorial-completamente-aleatorizado.qmd).
3. [Bloques aleatorizados](02-bloques-aleatorizados.qmd).
4. [Parcela dividida](03-parcela-dividida.qmd).

Cada taller incluye código guiado y preguntas que debes completar. Conserva seis componentes en el minirreporte: pregunta, predicción, diseño y unidades, resultados, interpretación y límites. El código de ejemplo forma parte de la práctica; no sustituye tus decisiones ni tu explicación.

Necesitas R, RStudio y Quarto; los talleres utilizan `ggplot2`, `dagitty` y, para parcela dividida, `nlme`. El equipo docente indicará el entorno preparado para la clase. Las simulaciones se generan dentro de los documentos y no necesitan datos externos.

Lleva tu [bitácora analítica](../../01-guias/guia-bitacora-analitica.qmd) y completa la [ficha de reconstrucción](../../01-guias/ficha-entrega-reproducible.qmd). Comprueba el documento desde una sesión nueva y conserva la versión utilizada. Una semilla no reemplaza el registro de código, parámetros y entorno.

[Volver a actividades](../README.md).


## Del archivo de trabajo al minirreporte

Trabaja sobre una copia del `.qmd` y conserva código, datos o generador, configuración y notas. El minirreporte selecciona seis apartados: pregunta, predicción, diseño y unidades, resultado, interpretación y límites. Conserva las fuentes ejecutables junto al informe; resumir la lectura no significa borrar lo necesario para reconstruir.

Elige un resultado principal —tabla, estimación o figura acompañada de valores numéricos comprobables— y explica qué afirma. Otros resultados pueden apoyar la interpretación. Inicia la [ficha de entrega](../../01-guias/ficha-entrega-reproducible.qmd) cuando selecciones el análisis del anexo final; no hace falta completarla para cada ejercicio.

Antes de modificar un parámetro, guarda la versión y escribe la predicción. Ejecuta el documento completo desde una sesión nueva, comenzando por la semilla. Compara modelos sobre los mismos datos cuando el cambio sea analítico. Si cambias la semilla o el mecanismo, identifica el nuevo escenario. Las predicciones se conservan aunque no se cumplan.

Los ejemplos resueltos son apoyo posterior al intento. No se evalúa copiar la sintaxis, sino justificar la decisión y comprobar el resultado. Las duraciones son orientativas; el equipo docente seleccionará las actividades que correspondan al curso.
