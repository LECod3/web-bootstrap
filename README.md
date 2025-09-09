# # Mi Proyecto — Bootstrap Cheat Sheet

Descripción: Guía rápida y anotada de Bootstrap para empezar: instalación, estructura básica, utilidades, componentes comunes, inicialización de JavaScript y personalización con Sass. Pensado como cheat-sheet / README.md para proyectos.

1 — Introducción
Bootstrap es un framework CSS/JS que ofrece estilos y componentes listos para usar. Ideal para prototipos rápidos y para mantener consistencia visual.

2 — Instalación rapida por CDN
<!-- CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- JS (bundle incluye Popper) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5/dist/js/bootstrap.bundle.min.js"></script>

3 - Estructura básica
<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Mi Proyecto</title>
<!-- link bootstrap -->
</head>
<body>
<div class="container">
<h1 class="mt-4">Hola Bootstrap</h1>
</div>
</body>
</html>

5 — Grid (columnas)

Sistema basado en row y col-{breakpoint}-{n}.
<div class="container">
<div class="row">
<div class="col-12 col-md-6">Columna 1</div>
<div class="col-12 col-md-6">Columna 2</div>
</div>
</div>

Breakpoints comunes: sm, md, lg, xl, xxl.

6 — Utilidades rápidas

Espaciado: m-? margen, p-? padding. Ej: mt-3, px-2.

Display: d-none, d-block, d-flex.

Text: text-center, text-muted, text-uppercase.

Colores de fondo y texto: bg-primary, text-white, bg-light.