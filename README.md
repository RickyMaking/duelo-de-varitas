# Duelo de Varitas

Juego web de duelos de magos. Se publica con GitHub Pages y se instala en el móvil como app.

## Archivos
- `index.html`: el juego
- `manifest.webmanifest`: datos de la app (nombre, iconos, pantalla completa)
- `sw.js`: permite abrirlo rápido y sin conexión
- `icons/`: iconos de la app

## Publicar en GitHub Pages
1. En github.com: **New repository** → nombre `duelo-de-varitas` → Public → Create.
2. **uploading an existing file** → arrastra `index.html`, `manifest.webmanifest`, `sw.js` y la carpeta `icons` (el contenido, no el zip) → **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. En 1-2 minutos tu dirección será `https://TU-USUARIO.github.io/duelo-de-varitas/`.

## Instalar en el móvil
- **Android (Chrome):** abre la dirección → menú ⋮ → *Instalar aplicación* / *Añadir a pantalla de inicio*.
- **iPhone (Safari):** abre la dirección → Compartir → *Añadir a pantalla de inicio*.

## Actualizar
Sustituye `index.html` en el repositorio y sube el número de `VERSION` en `sw.js` (`v1` → `v2`). Al abrir la app dos veces se actualiza.
