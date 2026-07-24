# Mercado Norte — Maquetación de Tienda Online

**Nombre:** Armando Cecilio Morales Sagastume
**Carné:** 1890-23-16029

## Descripción del proyecto

Maquetación visual (solo diseño, sin funcionalidad) de la página principal de
una tienda online ficticia llamada **Mercado Norte**, construida con
**HTML5** y **Bootstrap 5.3** (última versión vía CDN).

El objetivo del proyecto es practicar el uso de componentes visuales de
Bootstrap y el sistema de grid responsivo, sin implementar lógica real de
carrito de compras ni backend.

## Componentes de Bootstrap utilizados

- **Carousel**: carrusel de imágenes en la parte superior de la página, con
  indicadores, controles de navegación y leyendas (`carousel-caption`).
- **Grid system (container, row, col-sm-*)**: distribución del cuerpo en dos
  columnas — `col-sm-3` para el menú de categorías y `col-sm-9` para el
  listado de productos.
- **Grid responsivo anidado (row-cols-1 row-cols-md-3)**: los productos se
  muestran 1 por fila en pantallas pequeñas y 3 por fila en pantallas
  medianas/grandes.
- **Cards**: cada producto se muestra como una `card` con imagen, categoría,
  nombre, precio y botón.
- **List group**: menú lateral de categorías de ejemplo (no funcional).
- **Buttons**: botón "Agregar al carrito" (deshabilitado, solo visual) y el
  ícono flotante del carrito de compras.
- **Bootstrap Icons**: ícono de carrito (`bi-cart3`) y de brújula
  (`bi-compass`) usado como elemento distintivo de marca.
- **Utilidades de espaciado y responsivo** (`container`, `my-5`, `g-4`,
  `img-fluid`, `mb-4`, etc.) para mantener márgenes y paddings adecuados.

## Estructura del repositorio

```
tienda-online/
├── index.html          # Página principal
├── css/
│   └── styles.css       # Estilos personalizados (paleta, tipografía, tarjetas)
└── README.md            # Este archivo
```

## Identidad visual

- **Paleta de colores**: verde bosque (`#16302B`) como color de marca,
  naranja quemado (`#E4572E`) como color de acción/CTA y amarillo cálido
  (`#FCC419`) como acento.
- **Tipografía**: `Fraunces` (serif) para títulos y `Work Sans` para el
  cuerpo del texto, cargadas desde Google Fonts.
- **Elemento distintivo**: el ícono de brújula junto al nombre "Mercado
  Norte", presente en la barra de marca y en el footer.

## Cómo verlo localmente

1. Clonar o descargar este repositorio.
2. Abrir `index.html` directamente en el navegador (no requiere servidor).

## Publicación

- **Repositorio GitHub:** _agregar aquí la URL una vez subido_
- **Sitio publicado (GitHub Pages / Netlify):** _agregar aquí la URL una vez publicado_
