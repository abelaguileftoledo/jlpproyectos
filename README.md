# jlpproyectos.cl

Sitio web estático de JLP Proyectos. HTML + CSS + JS puro, sin build.

## Estructura

```
index.html            Página principal
robots.txt            Indexación
sitemap.xml           Mapa del sitio
assets/img/           Imágenes (hero, about, b1-b6, partner-logo)
assets/fonts/         Fuentes Montserrat (self-hosted)
```

## Despliegue (Cloudflare Pages)

Es un sitio estático: **no requiere build**.

Configuración en Cloudflare Pages:
- **Framework preset:** None
- **Build command:** (vacío)
- **Build output directory:** `/`

Cada `git push` a la rama `main` redespliega automáticamente.

## Pendientes de contenido (reemplazar antes de dar por final)

- [ ] Teléfono real (hoy `+56 9 0000 0000` en `index.html`)
- [ ] Formulario operativo (hoy es demo, no envía)
- [ ] Fotos reales en `assets/img/` (mantener los mismos nombres de archivo)
- [ ] Proyectos reales en el portafolio (hoy son de ejemplo)
