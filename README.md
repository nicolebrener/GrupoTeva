# Grupo Teva - Sitio web

Sitio estático. No requiere build ni servidor, ni depende de CDNs externos.

## Publicar en GitHub Pages
1. Subí todo el contenido de esta carpeta a la raíz del repo.
2. Settings > Pages > Source: "Deploy from a branch" > Branch: `main` / `(root)`.
3. En 1 o 2 minutos queda en `https://TU-USUARIO.github.io/NOMBRE-REPO/`.

## Estructura
- `index.html`: la página completa (textos, estilos y lógica).
- `support.js` e `image-slot.js`: runtime del diseño. No editar.
- `vendor/`: React y el bundle del sistema de diseño, incluidos localmente.
- `fonts/`: tipografía Inter, incluida localmente.
- `assets/`: logos, fotos de plantas y logos de clientes.
- `.nojekyll`: evita que GitHub Pages procese los archivos.

## Notas
- El formulario de contacto envía por formsubmit.co a vicobren@gmail.com. El primer envío dispara un mail de activación a esa casilla. Hay que confirmarlo.
- Para cambiar una foto, reemplazá el archivo en `assets/` con el mismo nombre.
