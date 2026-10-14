# Grupo Teva - Sitio web

Sitio estático. No requiere build ni servidor.

## Publicar en GitHub Pages
1. Subí todo el contenido de esta carpeta a la raíz de un repo.
2. En GitHub: Settings > Pages > Source: "Deploy from a branch" > Branch: `main` / `(root)`.
3. En 1 o 2 minutos queda en `https://TU-USUARIO.github.io/NOMBRE-REPO/`.

## Estructura
- `index.html`: la página completa.
- `support.js` e `image-slot.js`: runtime del diseño. No editar.
- `ds/`: estilos y tipografías del sistema de diseño.
- `assets/`: logos, fotos de plantas y logos de clientes.
- `.nojekyll`: evita que GitHub Pages procese los archivos.

## Notas
- La web carga React y Babel desde unpkg.com al abrirse. Necesita internet.
- El formulario de contacto envía por formsubmit.co a vicobren@gmail.com. La primera vez que alguien lo use, FormSubmit manda un mail de activación a esa casilla. Hay que confirmarlo.
- Para cambiar una foto, reemplazá el archivo en `assets/` con el mismo nombre.
