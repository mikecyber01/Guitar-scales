# Guitar Scales

App web (PWA) para estudiar escalas y posiciones en el mástil de guitarra y bajo, con modo juego.

## Subir a GitHub Pages
1. Crea un repositorio nuevo en GitHub (p. ej. `guitar-scales`), público.
2. Sube **todos** los archivos de esta carpeta a la raíz del repositorio
   (`index.html`, `manifest.webmanifest`, `sw.js` y los PNG).
3. En el repositorio: **Settings → Pages → Build and deployment**:
   Source = *Deploy from a branch*, Branch = `main`, carpeta `/ (root)` → Save.
4. Espera 1-2 minutos. La app estará en `https://TU-USUARIO.github.io/guitar-scales/`.

## Instalar en el móvil
- **Android (Chrome):** menú ⋮ → *Instalar aplicación*.
- **iPhone (Safari):** Compartir → *Añadir a pantalla de inicio*.

Tras la primera carga funciona sin conexión. Si cambias archivos, sube la versión
cambiando `CACHE` en `sw.js` (p. ej. `guitar-scales-v2`) para que el móvil se actualice.
