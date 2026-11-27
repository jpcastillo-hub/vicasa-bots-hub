# VICASA – Revisión (Singular)

## Fecha
Jueves 26 nov 2026, 14:51–15:08 según la grabación de Read AI; convocada para las 15:00 (America/Guatemala)

## Asistentes
José Pablo Castillo, Andrés Rebuly Pineda y Andrés Pinto (Singular). No se conectó: jc@singularagency.co.

## Fuente
18 min · Read AI id `01M8CT0EEQM14QGHR3NTADBNH9` (convocada por Andrés Rebuly) e informe de Read AI en Gmail (correo 1a219b2c32103920)

## Resumen
Revisión con Singular de los scrapers de inventario y del bot de ventas diarias de GTA. El scraper de Unisuper da inventarios incorrectos e intermitentes, así que se lleva a mano para no afectar bonificaciones y variables por score; Walmart sigue manual. El bot de GTA ya corrió solo por primera vez y guarda datos normalizados en una tabla aparte, consultable por MCP, pero todavía no aparece en el dashboard ni en el agente de Capsule.

## Decisiones
- Unisuper se sigue gestionando a mano mientras se revisa el scraper; Walmart queda manual porque no se encontró una solución viable.
- El trabajo adicional (llevar los datos de GTA al dashboard y al agente de Capsule) se mapea y se registra como historias en Singular para aprobarlo antes de hacerlo.

## Acuerdos y pendientes
- Andrés Pinto · Revisar el scraper de Unisuper para identificar por qué reporta inventarios incorrectos e intermitentes. Sin fecha.
- Andrés Rebuly Pineda · Mapear el trabajo adicional en Singular y dejar las historias listas para revisión y aprobación. Sin fecha.
- José Pablo Castillo · Revisar con su equipo el alcance de la visualización de los datos de GTA en el dashboard y su disponibilidad para el agente de Capsule, y confirmar los requisitos. Sin fecha.

## Temas abiertos / riesgos
- Los inventarios incorrectos de Unisuper pueden distorsionar los cálculos de bonificaciones y variables basados en el score.
- Diferencia de alcance: José Pablo esperaba que los datos de GTA reemplazaran la información problemática en el dashboard y en el agente de Capsule; Singular dice que el acuerdo cubría solo dejarlos en la base y que lo demás es desarrollo adicional.
- Con esta sesión se da por hecho el pendiente del 10 nov «Implementar la descarga de ventas diarias de GTA» (el bot ya corrió automáticamente).
