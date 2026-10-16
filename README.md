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
- [x] Contrastar las fechas originales de los 12 álbumes estándar con la discografía oficial.
- [x] Iniciar auditoría formal y checklist en `docs/BEATLES_AUDIT.md`.
- [x] Añadir créditos de composición a *Please Please Me* y *With The Beatles*.
- [ ] Verificar el resto de listas y créditos pista por pista; completar duraciones solo con fuentes confirmadas.
- [ ] Continuar con Led Zeppelin, Pink Floyd, Queen y las demás bandas.
- [ ] Añadir una web visual para explorar bandas, álbumes y canciones.

## Idioma

Documentación en español; títulos de álbumes y canciones conservados en su idioma original.


## Estado de avance (15 de octubre de 2026)

- **The Beatles:** auditoría cerrada para 12 álbumes del catálogo estándar y la banda sonora *Yellow Submarine*. Hay 193 pistas registradas con créditos, duraciones y referencias por pista.
- **Led Zeppelin:** iniciado con el álbum homónimo de 1969 (edición estadounidense), 9 pistas y fuentes oficiales/secundarias para contrastar tracklist, créditos y duraciones.
- **Siguiente paso:** incorporar los ocho álbumes de estudio restantes de Led Zeppelin en orden cronológico y validar sus ediciones antes de pasar a Pink Floyd.
- **Criterio:** las duraciones se documentan para una edición de referencia; mezclas, remasterizaciones y mercados pueden presentar diferencias de segundos.
