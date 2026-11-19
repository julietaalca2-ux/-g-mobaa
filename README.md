# Eternal Kingdoms — Web Edition

Interfaz web de demostración de un MOBA de fantasía, construida con HTML, CSS y JavaScript puro.

## Contenido
- `index.html`: estructura de las pantallas.
- `styles.css`: identidad visual, animaciones y adaptación móvil.
- `app.js`: navegación, héroes, sala 5v5, tienda, colección, perfil, eventos y ajustes.
- `assets/`: carpeta preparada para recursos gráficos adicionales.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub y sube el contenido de esta carpeta (no la carpeta ZIP).
2. En **Settings → Pages**, elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda y abre la URL que GitHub Pages te indique.

No requiere instalación, compilación, Unity ni servicios externos. Abre `index.html` en un navegador para probarlo. Google Fonts se usa como mejora tipográfica opcional; si no hay conexión, se aplican fuentes alternativas.

## Estado de esta edición
Esta entrega es una interfaz jugable de demostración. La búsqueda de partida, los rivales, las estadísticas y el historial son demostrativos. No incluye combate 3D, servidores, cuentas online ni multijugador real. Las preferencias, el perfil, el inventario y las recompensas se guardan localmente mediante `localStorage`.
