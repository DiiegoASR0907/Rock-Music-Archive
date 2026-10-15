# Rock Music Archive 🎸

Enciclopedia colaborativa de bandas de rock y sus discografías de estudio.

## Objetivo

Construir un catálogo fiable y ampliable con:
- Bandas, país de origen y años de actividad.
- Álbumes de estudio y sus fechas originales de lanzamiento.
- Listas completas de canciones en el orden de cada edición documentada.
- Portadas o enlaces a imágenes autorizadas.
- Fuentes verificables para cada dato.

## Estructura

- `data/bands.json`: catálogo de bandas.
- `data/albums.json`: álbumes y canciones.
- `docs/DATA_SCHEMA.md`: reglas y formato de los datos.
- `docs/SOURCES.md`: criterios para investigar y citar fuentes.

## Criterios de calidad

1. Distinguir la fecha original de lanzamiento de reediciones y remasterizaciones.
2. Registrar la edición usada cuando el orden o la cantidad de canciones varíe.
3. No inventar datos faltantes: usar `null` o dejar constancia de que están pendientes de verificación.
4. Incluir URLs de fuentes fiables y fecha de consulta cuando corresponda.
5. Preferir fuentes oficiales de las bandas y sellos; complementar con catálogos fiables.
6. Las portadas pueden estar protegidas por derechos de autor. Enlazar fuentes autorizadas y no asumir que una imagen puede redistribuirse libremente.

## Estado del proyecto

- [x] Repositorio creado.
- [x] Estructura inicial y criterios documentados.
- [x] Añadir el primer álbum verificado: *Abbey Road* (1969), con 17 pistas y fuentes oficiales.
- [x] Cargar una primera versión cronológica de los 12 álbumes del catálogo de estudio estándar de The Beatles, incluido *Magical Mystery Tour* según su edición LP estadounidense.
- [x] Registrar *Yellow Submarine* por separado como banda sonora, para no confundirla con los álbumes de estudio estrictos.
- [ ] Verificar álbum por álbum las listas de canciones, fechas, créditos y enlaces oficiales antes de marcar todos los registros como verificados.
- [ ] Continuar con Led Zeppelin, Pink Floyd, Queen y las demás bandas.
- [ ] Añadir una web visual para explorar bandas, álbumes y canciones.

## Idioma

Documentación en español; títulos de álbumes y canciones conservados en su idioma original.
