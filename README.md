# SUINTEC — Sitio web

Sitio de una página (landing) para SUINTEC – Suministros Industriales Tecnológicos.

## Estructura
- `index.html` — marcado de la página
- `css/styles.css` — todos los estilos
- `assets/` — fotos y logos (cada uno como archivo separado)

## Ver en local
Abre `index.html` en el navegador, o levanta un servidor simple:
    python3 -m http.server 8000
y entra a http://localhost:8000

## Pendientes
- Sección **Accesorios** (tuberías, cables, sensores, instrumentación, etc.)
- Reemplazar la **imagen de muestra del tablero** (`assets/imagen-de-muestra...` no existe: el tablero usa un placeholder SVG dentro de index.html) por una foto real.
- Actualizar el menú superior (aún muestra Bombas/Motores/Tableros/Accesorios apuntando a #categorias).
- Opcional: dividir secciones en componentes / publicar en un dominio.

## Secciones ya construidas
Hero · Quiénes somos (Misión/Visión) · Aplicaciones (Agricultura, Construcción, Industria, Saneamiento) ·
Soluciones para sistemas industriales: Bombas (6 tipos + 7 marcas), Motores y sopladores (3 tipos + 4 marcas),
Tableros eléctricos (descripción + viñetas + 5 marcas de componentes) · Por qué elegirnos · Contacto · Footer.
