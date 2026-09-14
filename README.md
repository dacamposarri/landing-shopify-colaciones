# Horizon — Colaciones irresistibles

Horizon NO usa plantillas `.liquid` de página. Por eso la landing salía en blanco.

## Orden

1. `sections/colaciones-landing.liquid` — la landing (con `{% schema %}` al final)
2. `templates/page.colaciones.json` — este JSON de 9 líneas
3. Páginas → plantilla **colaciones**

NO uses `page.colaciones.liquid` ni `layout none`.
