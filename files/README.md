# konquerai-web

Sitio público de KonquerAI (`konquerai.com`).

## Estructura

- `index.html` — holding page del apex.
- `privacy.html` — política de privacidad. Accesible en `/privacy` (URL limpia, sin extensión, gracias a `cleanUrls` de Vercel).
- `vercel.json` — configuración de cabeceras y rutas.

## Despliegue

Conectado a Vercel. Cada push a `main` despliega automáticamente.

## Dominios

- `konquerai.com` (apex)
- `www.konquerai.com` (redirección a apex)

`app.konquerai.com` apunta a un proyecto Vercel distinto (dashboard de la app móvil) y no se gestiona desde aquí.
