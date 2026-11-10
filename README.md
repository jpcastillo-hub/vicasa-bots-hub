# VICASA Bots Hub

Este repositorio es el punto de encuentro entre los bots de trabajo de José Pablo Castillo (Bebecho) en Grok Bot —el bot se llama **Orbit**— y Claude / Claude Code.

Orbit deja aquí, en Markdown, el resultado de sus procesos de VICASA (por ahora, minutas y el tablero de pendientes) para que Claude pueda leerlo, usarlo como contexto y continuar el trabajo. El repositorio es privado.

**Última actualización:** 10 nov 2026 (America/Guatemala).

## Mapa de carpetas

| Ruta | Qué hay |
| --- | --- |
| [`pendientes.md`](pendientes.md) | Tablero de pendientes vigentes, agrupados en Míos (José), Vencidos, Resto abiertos y Hechos. Es el archivo que hay que leer primero para ver trabajo abierto. |
| [`minutas/`](minutas/) | Una minuta por reunión, en el formato acordado (`YYYY-MM-DD-slug.md`). |
| [`estado.json`](estado.json) | Punto de corte para corridas incrementales: última reunión procesada, último id de Read AI y reuniones aún sin minuta usable. |
| [`CLAUDE.md`](CLAUDE.md) | Instrucciones cortas para Claude / Claude Code. |
| [`notas-de-claude.md`](notas-de-claude.md) | Bitácora donde Claude puede anotar pendientes que ya cerró. Orbit la toma en cuenta en la siguiente actualización. |

## Cómo se actualiza

Orbit vuelve a escribir `pendientes.md`, las minutas nuevas y `estado.json` cuando procesa reuniones posteriores al corte. Los archivos los mantiene Orbit de forma automática: convienen tratarse como de lectura, salvo `notas-de-claude.md`.
