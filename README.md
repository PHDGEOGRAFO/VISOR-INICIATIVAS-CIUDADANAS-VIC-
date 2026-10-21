# Visor Ciudadano · Santiago — sitio de revisión

Publicación estática para GitHub Pages. Instrucción: crear repositorio público `VISOR-INICIATIVAS-CIUDADANAS-VIC-` en PHDGEOGRAFO y cargar los archivos de esta carpeta en la raíz. Settings > Pages > Deploy from a branch > main > /(root).

## Advertencias

- Este sitio **NO** recibe iniciativas reales ni guarda nombre, correo, teléfono o dirección.
- El módulo administrador y la clave incluida en el cliente son **demostrativos**, no protegen datos. No publicar información de participantes ni GeoPackage en GitHub Pages.
- Para visor histórico multiusuario, GPKG por categoría y tipo, y respaldo en Google Drive hace falta backend privado con autenticación real y persistencia (PostGIS), más integración de Drive con credenciales protegidas en servidor.
- El MATCH V0.3 sigue siendo preliminar y no constituye correspondencia oficialmente validada.
- La capa de 27 barrios es de referencia del Visor de Arriendos; verificar vigencia institucional.
- Fondo cartográfico Esri World Topographic Map, requiere conectividad.

## Estructura
`index.html` visor de revisión estático; `barrios_referencia.geojson` y `match_v03.json` para inspección técnica. Los datos de prueba se almacenan solo en el navegador.