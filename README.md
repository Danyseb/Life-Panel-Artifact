# Panel de vida

Panel personal en un solo archivo HTML: rutina diaria con marcas, plan de pendientes con ruta optimizada, vista mensual, estadísticas y una pestaña «Mi día» con agenda, correos, tareas y alertas.

## Cómo usarlo

- **En cualquier navegador:** abre `index.html`. Los datos se guardan en el `localStorage` de ese navegador.
- **Como artefacto de Claude:** publícalo con los permisos `db`, `sample` y `mcp` (Google Calendar `list_events`, Gmail `search_threads`). Así los datos se guardan en la nube y «Mi día» lee tu calendario y tu correo.

Sin esos permisos, la pestaña «Mi día» muestra que no hay conexión y el resto funciona igual.

## Qué incluye

- **Mi día:** resumen en una línea, agenda de hoy o de 7 días (conflictos, huecos cortos y bloques libres), correos clasificados, tareas en lenguaje natural, alertas cruzadas y estado de conexiones.
- **Hoy:** tareas fijas y del día con marcas ✓ / ✕, más una lista editable de medicinas y suplementos.
- **Planear:** pendientes con lugar y horario; ordena la ruta y genera el enlace de Google Maps.
- **Mes y Estadísticas:** cumplimiento por día y por tarea.
- **Modo claro y oscuro** con un switch arriba.

## Privacidad

El archivo no trae datos personales. La rutina fija y la lista de medicinas son ejemplos que se editan desde la página. Calendar y Gmail se usan solo en modo lectura: la app nunca envía, borra ni modifica correos ni eventos.
