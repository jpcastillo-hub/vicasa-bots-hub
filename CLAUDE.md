# Instrucciones para Claude

Este repositorio lo mantiene **Orbit**, el bot de Grok Bot de José Pablo Castillo, para que puedas trabajar con el mismo contexto de VICASA.

1. Empieza por [`pendientes.md`](pendientes.md). Ahí está el trabajo abierto, con responsable, fecha límite, reunión de origen y estado (Abierto, Vencido o Hecho).
2. Las minutas están en [`minutas/`](minutas/), una por reunión, con el formato: Fecha, Asistentes, Fuente; Resumen; Decisiones; Acuerdos y pendientes; Temas abiertos / riesgos.
3. [`estado.json`](estado.json) indica hasta qué reunión ya se procesó. No lo edites salvo que José te lo pida explícitamente.
4. Estos archivos los escribe Orbit de forma automática. Trátalos como de **solo lectura**. No reescribas el tablero ni las minutas para «ordenarlos».
5. Si cierras o avanzas un pendiente, anótalo en [`notas-de-claude.md`](notas-de-claude.md): qué pendiente, qué hiciste, la fecha (America/Guatemala) y, si puedes, la evidencia (correo, archivo, decisión). Orbit lo reflejará en el tablero en la siguiente actualización.
6. No inventes responsables ni fechas. Si algo no está en la minuta o en el tablero, dilo. No publiques, no envíes correos ni toques Odoo a menos que José te lo pida de forma explícita y lo autorice.

7. En [`investigacion/`](investigacion/) Orbit deja el radar semanal de mercado y competencia: la lista de competidores (`competidores.md`), el reporte de cada lunes (`YYYY-MM-DD-radar-semanal.md`) y los precios crudos observados en `precios/`. Ben —el skill de Claude de José para benchmark de precios y competencia— puede leer estos archivos como fuente de góndola observada. No sustituyen al PTC de VICASA y no hay que inventar precios propios. No reescribas los reportes de Orbit; si comentas o cierras un hallazgo, anótalo en [`notas-de-claude.md`](notas-de-claude.md).
