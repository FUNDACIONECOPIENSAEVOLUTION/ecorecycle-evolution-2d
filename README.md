# Proyecto Triple Eco, Ciencia Evolution

Sitio interactivo y animado de **Fundación Ecopiensa Evolution**, basado en el sitio ECORECYCLE Evolution.

## Publicación con GitHub Pages

Los archivos `index.html`, `historia.html`, `.nojekyll` y `logo ecopiensa (1).png` deben estar **directamente en la raíz** de la rama `main` del repositorio. No es suficiente subir un archivo ZIP sin extraerlo.

1. Repositorio existente: `FUNDACIONECOPIENSAEVOLUTION/ecorecycle-evolution-2d`.
2. Subir los archivos extraídos a la raíz de la rama `main`.
3. En el repositorio, ir a **Settings > Pages**. Bajo **Build and deployment**, seleccionar **Deploy from a branch**, rama `main` y carpeta `/(root)`; guardar.
4. Comprobar la URL `https://fundacionecopiensaevolution.github.io/ecorecycle-evolution-2d/`.

## Contenido

El sitio tiene nueve historias animadas accesibles desde la portada:

1. Ecoaldeas y red ECO-CIA.
2. RCD: aprovechamiento de escombros.
3. Ecotiendas y canje.
4. Reciclaje con dos modalidades de recogida.
5. Plásticos y ECOBIONICA.
6. Residuos orgánicos.
7. Otros materiales y aprovechamiento.
8. Inclusión comunitaria.
9. Inteligencia artificial y seguimiento.

La página de cada historia permite recorrer escenas mediante botones. La narración con voz es opcional y depende de la compatibilidad del navegador.

## Pruebas realizadas

Se validó el JavaScript con `node --check`. Se probaron la página principal y las nueve historias en un navegador Chromium automatizado, simulando escritorio (1440 × 900) y móvil (390 × 844); en las nueve funcionaron avanzar y retroceder, se generaron los SVG y no hubo errores JavaScript de página ni desbordamientos horizontales. La navegación se ensayó con contenido inyectado en el navegador porque las rutas locales estaban restringidas en el entorno de pruebas. **Aún no se ha comprobado un despliegue público real de GitHub Pages.**