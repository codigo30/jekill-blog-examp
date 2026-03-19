# Huellas de Barrio - Jekyll Blog

Sitio web del Grupo de investigación Medio Ambiente y Sociedad - MASO, convertido a Jekyll para GitHub Pages con funcionalidad de blog completa.

## Características

- Blog dinámico con Jekyll
- Soporte para contenido multimedia (imágenes, videos, YouTube)
- Sistema de categorías y etiquetas
- Diseño responsive con Bootstrap 5
- Optimizado para GitHub Pages
- SEO optimizado

## Estructura del Proyecto

```
.
├── _config.yml          # Configuración principal de Jekyll
├── _layouts/            # Plantillas de página
│   ├── default.html     # Layout base
│   └── post.html        # Layout para posts
├── _includes/           # Componentes reutilizables
│   ├── header.html      # Encabezado
│   └── footer.html      # Pie de página
├── _posts/              # Artículos del blog
│   └── YYYY-MM-DD-titulo.md
├── blog/                # Página índice del blog
├── recursos/            # Recursos estáticos (imágenes, etc)
├── styles.css           # Estilos personalizados
└── index.md             # Página de inicio
```

## Cómo Crear un Nuevo Post

1. Crea un archivo en la carpeta `_posts/` con el formato: `YYYY-MM-DD-titulo-del-post.md`

2. Agrega el front matter al inicio del archivo:

```yaml
---
layout: post
title: "Título del Post"
date: 2024-03-20 10:00:00 -0500
category: "Categoría"
author: "Autor"
image: "url-de-imagen.jpg"
tags: ["tag1", "tag2", "tag3"]
excerpt: "Breve descripción del post"
---
```

3. Escribe el contenido usando Markdown

### Agregar Videos

**Para videos locales:**
```yaml
video: "/ruta/al/video.mp4"
```

**Para videos de YouTube:**
```yaml
youtube: "ID_DEL_VIDEO"
```

## Instalación Local

1. Instala Ruby y Bundler
2. Clona el repositorio
3. Instala las dependencias:
   ```bash
   bundle install
   ```
4. Ejecuta el servidor local:
   ```bash
   bundle exec jekyll serve
   ```
5. Visita `http://localhost:4000`

## Despliegue en GitHub Pages

1. Sube el código a un repositorio de GitHub
2. Ve a Settings > Pages
3. Selecciona "GitHub Actions" como source
4. El sitio se desplegará automáticamente con cada push a main

## Contenido Multimedia

### Imágenes
- Coloca las imágenes en la carpeta `/recursos/img/`
- Referencia en posts: `![Alt text](/recursos/img/imagen.jpg)`

### Videos
- Videos locales: guarda en `/recursos/videos/`
- Videos de YouTube: usa el parámetro `youtube` en el front matter

## Personalización

### Colores
Los colores principales están definidos en `styles.css`:
- Verde principal: `#004200`
- Verde claro: `#33cc66`
- Azul oscuro: `#002c5f`

### Navegación
Edita `_includes/header.html` para modificar el menú de navegación.

### Footer
Edita `_includes/footer.html` para actualizar información de contacto.

## Soporte

Para preguntas o problemas, contacta a: grupomaso@udea.edu.co

## Licencia

Grupo de investigación Medio Ambiente y Sociedad - MASO
Universidad de Antioquia
