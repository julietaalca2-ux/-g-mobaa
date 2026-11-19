# Eternal Kingdoms — Web Edition

Interfaz de videojuego MOBA de fantasía, optimizada para Safari en iPhone y publicación directa en GitHub Pages.

## Archivos
- `index.html` — HUD principal, pantalla de carga y secciones independientes.
- `styles.css` — interfaz cinematográfica, animaciones, efectos y adaptación horizontal/vertical.
- `app.js` — navegación, selección de héroes, sala 5v5 de demostración, tienda, inventario, perfil, eventos y guardado local.
- `assets/` — carpeta preparada para recursos gráficos propios.

## Publicación
Sube el contenido de esta carpeta a la raíz de un repositorio GitHub. En **Settings → Pages**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`.

No requiere Unity, Unreal, instalación ni compilación. Google Fonts es opcional; hay fuentes alternativas si no hay conexión.

## Alcance
Es una edición web visual e interactiva. La cola de partida, amigos, historial y estadísticas son demostrativos; no existe todavía un servidor de partidas, cuentas online, combate 3D ni multijugador real. Los ajustes, el nombre, el inventario y las recompensas se guardan en `localStorage`.


## Versión 3 — corrección de interfaz
Se reorganizó el HUD, el escenario principal y las páginas internas con áreas reservadas para la barra superior e inferior. Los paneles laterales de promociones y amigos solo aparecen en Inicio; las demás secciones usan el ancho disponible y mantienen cuadrículas simétricas y desplazamiento independiente. Incluye ajustes específicos para iPhone vertical y horizontal.
