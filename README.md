# Esquí de montaña desde el Balneario de Panticosa

Mapa 3D invernal de las 28 rutas de esquí de montaña que salen y vuelven al Balneario de Panticosa (Valle de Tena, Pirineo aragonés). Las rutas son las de las crónicas del blog [La Meteo que viene](https://lameteoqueviene.blogspot.com/), de Jorge García-Dihinx.

**Web:** https://rforcano.github.io/esqui-balneario-panticosa/

- Cada ruta aparece una sola vez. Si se ha hecho varias veces, la ficha enlaza a sus otras crónicas.
- Al pulsar el nombre de una ruta se abre su ficha: cota, desnivel, horario, orientación, perfil y variantes.
- Al pulsar la ficha se abre la crónica original en el blog.

Los trazados son **aproximados**. Están reconstruidos a partir de lo que cuentan las crónicas y de los itinerarios de esquí de OpenStreetMap. Antes de salir, consulta el track original de cada crónica y el boletín de aludes.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `index.html` | La aplicación (HTML, CSS y JavaScript; usa [three.js](https://threejs.org/) 0.170 desde jsDelivr) |
| `data.json` | Rutas, fichas, perfiles y toponimia |
| `terrain_h.png` | Modelo de elevación (altura × 10 en los canales rojo y verde) |
| `winter.jpg` | Textura invernal del relieve (sombreado, bosque, roca, ibones helados) |
| `preview.jpg` | Imagen para compartir en redes |

## Fuentes y créditos

- Relieve: MDT del © Instituto Geográfico Nacional de España e IGN France, vía [Mapterhorn](https://mapterhorn.com/).
- Cobertura del suelo: ESA WorldCover 2021 (CC BY 4.0).
- Itinerarios y toponimia: © colaboradores de [OpenStreetMap](https://www.openstreetmap.org/copyright) (ODbL).
- Rutas, datos de las fichas y crónicas: Jorge García-Dihinx, *La Meteo que viene*. Las descripciones de las fichas son resúmenes propios. Cada ficha enlaza a la crónica original.

Proyecto creado por [Ricardo Forcano](https://ricardoforcano.es/) con Claude.
