# Net Food — landing (opción 2a)

Sitio estático, sin dependencias ni build.

## Publicar en GitHub Pages
1. Subí el contenido de esta carpeta a la raíz del repositorio (o a /docs).
2. Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)` o `/docs`.
3. En unos minutos queda publicado en `https://<usuario>.github.io/<repo>/`.

## Archivos
- `index.html` — la página completa (estilos y scripts incluidos).
- `assets/` — fotos, logo y mapa de cobertura.
- `.nojekyll` — evita que GitHub Pages procese la carpeta con Jekyll.

## Comportamiento
- Las fotos se cargan a medida que entran en pantalla (`loading="lazy"`).
- Cada sección aparece con un fade al llegar al viewport; se desactiva si el visitante tiene activada la reducción de movimiento del sistema.
- La tira de marcas se desplaza sola y se detiene al pasar el mouse.
- Las preguntas frecuentes se abren y cierran con click o teclado.

## Pendiente de reemplazar
- Teléfono de WhatsApp: `(0249) 15 XXX-XXXX`.
- Enlaces del nav y del footer (hoy son texto, sin `href`).
- Datos estimados: cantidad de clientes, días de reparto por localidad y pedido mínimo.
