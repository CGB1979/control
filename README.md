# Control — Mi Jornada

PWA estática para GitHub Pages. No usa Node, npm, Vite ni build: se sirve directamente como archivos estáticos.

## Publicar en GitHub

1. Crear/usar el repositorio `Control`.
2. Subir **estos archivos directamente a la raíz** del repositorio.
3. GitHub → Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Abrir `https://TU-USUARIO.github.io/Control/`.

La aplicación usa rutas relativas (`./`), por lo que funciona tanto en GitHub Pages bajo `/Control/` como en un servidor local.

## Funciones iniciales

- Marcar entrada y salida.
- Cronómetro de jornada.
- Historial y correcciones manuales.
- Calendario mensual.
- Banco de medios francos y francos completos.
- Configuración de reglas laborales.
- Exportación CSV compatible con Excel.
- Almacenamiento local.
- PWA instalable y funcionamiento offline básico.

Las reglas laborales que todavía no fueron confirmadas se mantienen configurables.
