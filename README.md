# Enitsaloc Perfumería – sitio web

Sitio estático (HTML + CSS + JS en un solo `index.html`). Funciona tal cual en **GitHub Pages**.

## Cómo publicarlo en GitHub Pages
1. Subí **todo el contenido** de esta carpeta a la raíz de tu repositorio (incluida la carpeta `img/` y el archivo `.nojekyll`).
2. En GitHub: *Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`*.
3. Marcá **Enforce HTTPS**.
4. Dominio propio: en *Settings → Pages → Custom domain* escribí tu dominio.

## Antes de publicar, reemplazá
- `TU-DOMINIO.com` por tu dominio real en `index.html`, `robots.txt` y `sitemap.xml`.
- `G-XXXXXXXXXX` (Google Analytics 4) en `CFG.ga`, dentro del `<script>` de `index.html`.
- Datos legales marcados en amarillo (nombre/razón social, CUIT, domicilio, email) en el Aviso legal y la Política de privacidad.

## Fotos
Cada foto vive en `img/` y se llama como el perfume: minúsculas, sin tildes, espacios y símbolos como guiones (`khamrah-qahwa.webp`).
Para sumar una: copiala a `img/` y agregá su nombre (sin `.webp`) a la lista `photos` dentro de `CFG` en `index.html`.

## Opiniones
Se cargan en `CFG.reviews`. La sección y su enlace del menú aparecen solos cuando hay al menos una opinión real.
