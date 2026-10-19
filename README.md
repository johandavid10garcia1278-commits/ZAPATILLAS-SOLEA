# SOLEA — tienda de zapatillas

Tienda demostrativa de zapatillas, creada con HTML, CSS y JavaScript puro. Es adaptable a móviles y escritorio, y está lista para publicarse en GitHub Pages.

## Incluye

- Diseño responsive con identidad de marca y logo SVG propio.
- Catálogo de zapatillas y fichas rápidas de producto.
- Filtros por marca, talla europea y precio.
- Búsqueda y ordenamiento por precio o nombre.
- Favoritos, carrito con cantidades, subtotal y aviso de envío gratis.
- Formulario de novedades con confirmación visual.
- Guía de tallas y navegación móvil.

## Abrir en tu computador

1. Descarga y descomprime `solea-github.zip`.
2. Abre `index.html` en tu navegador. No necesitas instalar dependencias.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `solea-store`.
2. Sube todos los archivos y carpetas de este proyecto (no solo `index.html`).
3. En el repositorio, entra a **Settings → Pages**.
4. En **Build and deployment**, escoge **Deploy from a branch**, selecciona `main` y la carpeta `/ (root)` y guarda.
5. Espera a que GitHub Pages publique el sitio y abre la URL que muestra en esa sección.

## Personalizar productos

Edita el arreglo `PRODUCTS` al inicio de `script.js`. Cada producto incluye marca, nombre, precio en pesos colombianos, tallas, colores, imagen y descripción.

## Importante

Este proyecto es una **demo front-end**. El carrito funciona en la sesión actual del navegador, pero no procesa pagos ni crea pedidos reales; tampoco envía ni almacena correos. Las fotos se cargan desde Unsplash y las fuentes desde Google Fonts, por lo que esas partes requieren conexión a internet. Para vender de verdad necesitarás integrar un backend, inventario y una pasarela de pago segura.
