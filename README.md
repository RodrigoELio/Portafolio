# Portafolio — Desarrollador de Software

Página de portafolio personal en un solo archivo HTML, construida con **Bootstrap 5**. Incluye secciones de presentación, sobre mí, habilidades, proyectos y contacto.

## Estructura

```
index.html
```

Todo el proyecto vive en un único archivo: HTML, estilos personalizados y la carga de Bootstrap vía CDN. No requiere build ni dependencias instaladas.

## Tecnologías

- Bootstrap 5 (grid y componentes base, vía CDN)
- CSS personalizado (tipografía, colores, layout)
- Google Fonts: Fraunces, IBM Plex Sans, IBM Plex Mono
- SVG en línea para el diagrama del hero

## Cómo verlo localmente

Solo abre `index.html` en el navegador — no necesita servidor.

## Personalización pendiente

Antes de publicar, reemplaza estos datos de ejemplo dentro de `index.html`:

- `nombre.apellido` en la barra de navegación y `Nombre Apellido` en el pie de página
- `tu.correo@ejemplo.com` (enlace de contacto)
- Enlaces de GitHub y LinkedIn (actualmente `tu-usuario`)
- Sección de **Proyectos**: el proyecto destacado ya describe el Sistema de Gestión de Restaurante; edita o reemplaza los dos proyectos secundarios de ejemplo
- Sección de **Habilidades**: ajusta según tu stack real

## Publicar gratis

**Opción recomendada — GitHub Pages:**

1. Crea un repositorio público en GitHub.
2. Sube `index.html` (arrastrándolo desde la web o con `git push`).
3. Ve a *Settings → Pages* y selecciona la rama `main` y la carpeta raíz (`/`).
4. Tu página quedará publicada en `tu-usuario.github.io/nombre-repo`.

**Alternativas:**

- [Netlify Drop](https://app.netlify.com/drop) — arrastra la carpeta y obtén una URL al instante.
- [Vercel](https://vercel.com) — similar a Netlify, útil si luego agregas funcionalidad dinámica.
- Cloudflare Pages — buena opción si más adelante quieres conectar un dominio propio.

## Licencia

Uso personal — libre de modificar como quieras.
