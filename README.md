# Piggy Knight — Landing page

Sitio estático de una sola página para el videojuego **Piggy Knight**, de Nowherelado Games (Uruguay).

## Cómo se ve
Abrí `index.html` en el navegador. No necesita build ni dependencias: es HTML + CSS + un poco de JS (lightbox de imágenes). Las fuentes (Cinzel + EB Garamond) se cargan desde Google Fonts y las ilustraciones están en `uploads/`.

## Deploy (GitHub Pages)
1. En el repo → **Settings → Pages**.
2. En **Source** elegí **Deploy from a branch**, branch `main`, carpeta `/ (root)`.
3. El archivo `CNAME` ya apunta a `www.piggyknight.com`. En tu proveedor de dominio, creá un registro **CNAME** para `www` → `elcoletuy.github.io`.

## Estructura
- `index.html` — la página completa.
- `uploads/` — ilustraciones en acuarela, optimizadas a WebP (~2 MB en total).
- `uploads/og.jpg` — imagen de vista previa al compartir el link.
- `CNAME` — dominio personalizado (www.piggyknight.com).
- `.nojekyll` — evita el procesado Jekyll de GitHub Pages.
