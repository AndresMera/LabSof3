# Proyecto 4: Categorización inteligente y vista de detalle

Laboratorio de Ingeniería de Software 3 — Universidad del Cauca

## Descripción

Tienda web que reemplaza el filtro de categorías escrito a mano por uno construido dinámicamente a partir del inventario, y agrega una vista de detalle por producto mediante un modal.

## Funcionalidades implementadas

- **Menú de navegación**: permite ir y volver libremente entre la tienda (`index.html`) y la hoja de vida (`hoja-de-vida.html`).
- **Categorías dinámicas**: las opciones del `<select>` de filtro se generan recorriendo el inventario en la inicialización, sin categorías repetidas.
- **Botón "Ver detalles"**: independiente del botón de agregar al carrito, en cada tarjeta de producto.
- **Modal de detalle**: un único contenedor oculto por defecto (clase `.oculto`) que se reutiliza para todos los productos, mostrando nombre, categoría, precio y stock.

## Estructura del repositorio

```
├── index.html          # Tienda: catálogo, filtro y carrito
├── style.css            # Estilos de la tienda
├── script.js             # Lógica de la tienda (inventario, filtro, carrito, modal)
├── hoja-de-vida.html     # Hoja de vida
├── hoja-de-vida.css      # Estilos de la hoja de vida
├── hoja-de-vida.js       # Lógica de la hoja de vida (menú lateral)
└── images/                # Imágenes de productos y de la hoja de vida
```

## Cómo verlo

- Página desplegada: [enlace de GitHub Pages]
- Repositorio: [enlace del repositorio]

## Autor

Jorge Andrés Mera Vásquez — Ingeniería de Sistemas, Universidad del Cauca
