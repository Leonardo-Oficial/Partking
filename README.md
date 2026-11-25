# Catastro de estacionamientos de superficie — Valdivia

Plano tridimensional del centro de Valdivia con los 50 tramos de estacionamiento
de la Propuesta Pública N° 171-2025 (ID 2282-185-LP25), pensado para el
seguimiento técnico de la concesión.

**Ver en línea:** https://leonardo-oficial.github.io/Partking/

## Qué hace

- Dibuja la ciudad en tres dimensiones sobre el recuadro del centro, de 2,26 × 1,58 km.
- Muestra los 50 tramos del Anexo N° 3 con sus cupos existentes, de discapacidad
  y afectos a cobro, y permite cuadrarlos contra la meta de 675 de la Ordenanza.
- Deja agregar tramos nuevos tomando una cuadra entera con un clic, ajustar el
  trazo punto por punto y repartir los cupos a mano dentro del tramo.
- Tres tonos de interfaz: claro, medio y oscuro.

## De dónde salen los datos

- **Calles y avenidas:** trazado copiado de las teselas vectoriales del mapa base
  mundial de Esri (`World_Basemap_v2`, capa `Road`), nivel 17. 339 ejes, 51,7 km,
  vértice a vértice.
- **Rótulos de calle, río y áreas verdes:** © colaboradores de OpenStreetMap.
- **Cupos por tramo:** Anexo N° 3 de las bases de la Propuesta Pública N° 171-2025,
  documento público de la licitación.
- **Edificios:** huellas de OpenStreetMap, con alturas estimadas.

Esta copia pública no incluye las anotaciones de terreno de la inspección.

## Cómo funciona

Es una sola página HTML sin dependencias: no necesita servidor, compilación ni
instalación. Se abre con doble clic o se sube tal cual a cualquier hospedaje
estático. Lo único que carga de fuera son las tipografías de Google Fonts.

Los cambios que se hagan en la página (tramos nuevos, cupos, estados) quedan
guardados en el navegador de quien la usa, mediante `localStorage`.

## Licencia y atribución

El código es de autoría propia. Los datos cartográficos pertenecen a sus
fuentes: Esri y los colaboradores de OpenStreetMap, bajo las condiciones de cada
una. El Anexo N° 3 es parte de las bases públicas de la licitación.
