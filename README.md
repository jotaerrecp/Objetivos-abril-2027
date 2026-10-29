# Mapa de objetivos · Abril 2027

Aplicación estática PWA en español, con objetivos, progreso y balance en ARS. Tema negro, iconos alineados y casillas a la derecha.

## Publicación

Archivos listos para GitHub Pages desde la raíz del repositorio (`/`). No requiere compilación, instalación de dependencias, servidor propio ni secretos. Compatible con sitios de usuario y rutas de repositorio: los recursos, el manifest y el service worker usan rutas relativas.

## Archivos

- `index.html`: aplicación con estilos y lógica integrados.
- `manifest.webmanifest`, `sw.js` y los dos iconos PNG: instalación y uso sin conexión después de la primera carga correcta.
- `Objetivos-independiente.html`: versión portable para abrir como archivo local.
- `mapa-objetivos.zip`: descarga de la aplicación disponible desde la interfaz.
- `.nojekyll`: publicación directa de los archivos estáticos.

## Datos

El guardado es local a cada navegador y origen. Para trasladar los avances desde la página anterior a GitHub Pages, usar **Exportar respaldo** en la página anterior e **Importar** en la nueva. Este repositorio contiene los objetivos y presupuestos iniciales; no incluye los avances guardados en el navegador.

Los objetivos y presupuestos iniciales incluidos en el código serán visibles para quien pueda acceder al repositorio o a la página publicada. La aplicación no requiere iniciar sesión ni envía los cambios a un servidor.

## Mantenimiento

Después de modificar la aplicación, actualizar también el HTML independiente y el ZIP de descarga. Cambiar el nombre de `CACHE` en `sw.js` para renovar los recursos sin conexión. Conservar la clave de localStorage `mapa-objetivos-2027-v1` y los IDs de los objetivos existentes para mantener los avances del mismo origen.
