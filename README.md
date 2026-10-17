# Spotify Clone

Réplica estática de la interfaz de Spotify, hecha con HTML y Sass. La página muestra el sencillo "Terminal 2F" de GIMS como práctica de maquetación frontend. No usa la API de Spotify ni reproduce audio.

## Requisitos

- Node.js y npm

## Uso

Instala las dependencias de desarrollo y compila los estilos:

```bash
npm install
npm run sass:build
```

Después, abre `index.html` en el navegador o sírvelo con cualquier servidor estático. Para recompilar Sass automáticamente mientras trabajas:

```bash
npm run sass:watch
```

El CSS compilado se incluye para que el sitio se pueda publicar directamente en GitHub Pages; el mapa de fuentes y `node_modules` no se incluyen en Git.

## Estructura

- `index.html`: estructura y contenido de la página.
- `sass/`: estilos fuente organizados en componentes, layout y recursos compartidos.
- `styles/main.css`: estilos compilados que consume la página.
- `assets/img/`: imágenes locales.

## Publicación en GitHub Pages

En la configuración del repositorio, selecciona la rama que contiene el proyecto y la carpeta raíz (`/`) como origen de GitHub Pages.

Ver sitio publicado: [jonnschenk.github.io/Spotify/](https://jonnschenk.github.io/Spotify/)

## Créditos y alcance

Proyecto de práctica no oficial, sin afiliación con Spotify, GIMS ni los demás artistas mencionados. Las imágenes y marcas pertenecen a sus respectivos titulares. Verifica que tienes derecho a publicar los recursos incluidos antes de hacer público el repositorio.
# Spotify
