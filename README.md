# Adaluz – Luxy (tema Horizon de Shopify)

Bloques personalizados en Liquid + CSS + JS puro, sin schema.

| Archivo | Qué es |
|---|---|
| `snippets/luxy-header.liquid` | Encabezado: logo, carrito, buscador y menú lateral |
| `snippets/luxy-bottom-nav.liquid` | Barra inferior flotante (solo móvil): Inicio, Categorías, Favoritos, Carrito |
| `snippets/luxy-hero-carousel.liquid` | Carrusel automático (3 s) con imágenes de Shopify Files |
| `snippets/luxy-featured-products.liquid` | Productos destacados desde la colección `all` |

## Uso
Pegar el contenido de cada archivo en una sección Liquid personalizada del tema Horizon,
o incluirlo con `{% render 'luxy-header' %}` desde `layout/theme.liquid` o una plantilla.
