# Script `version`

Este script en Bash permite gestionar versiones de archivos de manera sencilla, facilitando la creación, restauración y mantenimiento de versiones, así como la descarga de recursos vinculados a archivos HTML.

---

## Contenido

- [Características](#características)
- [Uso](#uso)
- [Opciones](#opciones)
- [Formato de mensajes de versión](#formato-de-mensajes-de-versión)
- [Requisitos](#requisitos)
- [Licencia](#licencia)

---

## Características

- Crear nuevas versiones de un archivo, numeradas automáticamente.
- Restaurar versiones desde backups o versiones actuales.
- Mantener un historial con mensajes, fechas y autores para cada versión.
- Mover versiones antiguas a un directorio `.backup`.
- Descargar archivos `.js` y `.css` referenciados en archivos HTML.
- Visualizar y editar el historial de versiones.
- Construir y abrir URLs para probar archivos HTML desde un servidor local.
- Interfaz interactiva para selección de versiones usando `fzf`.

---

## Uso

```bash
./version [opción] [archivo]
