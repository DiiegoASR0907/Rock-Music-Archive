# Esquema de datos

## Bandas — `data/bands.json`

Cada banda debe incluir:
- `id`: identificador estable en minúsculas y con guiones.
- `name`: nombre oficial.
- `country_of_origin`, `formed_year`, `disbanded_year`.
- `genres`: géneros principales, sin pretender que sean exhaustivos.
- `official_website` y `sources`.
- `status`: indicar si el registro es inicial o está verificado.

## Álbumes — `data/albums.json`

Cada álbum debe incluir:
- `id`, `band_id`, `title`, `album_type`.
- `original_release_date`: fecha ISO `YYYY-MM-DD` si está confirmada; si solo se conoce año/mes, documentarlo en una nota y no inventar el día.
- `edition_note`: edición o mercado utilizado para definir el tracklist.
- `label`, `genres`, `duration_minutes`.
- `cover`: enlace de imagen, fuente y nota de derechos.
- `tracks`: pistas ordenadas por `position`; incluir duración y compositores solo cuando se verifiquen.
- `sources`: fuentes que respalden fechas, canciones y otros datos.
- `verification_status`: `template_only`, `needs_verification` o `verified`.

## Reglas importantes

- No mezclar álbumes de estudio con directos, recopilatorios, EP o bandas sonoras.
- Separar el lanzamiento original de las reediciones.
- Si hay ediciones con listas distintas, crear registros separados o explicar claramente la variante.
- Mantener títulos, signos y diacríticos tal como aparecen en fuentes fiables.
- Un enlace a una portada no equivale a permiso para redistribuirla.
