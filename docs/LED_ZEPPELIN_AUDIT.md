# Auditoría de Led Zeppelin

**Fecha de cierre inicial:** 15 de octubre de 2026  
**Alcance:** nueve álbumes de estudio originales, en orden cronológico; sin álbumes en directo, recopilatorios ni pistas adicionales de reediciones deluxe.

## Cobertura del catálogo

| Álbum | Fecha de lanzamiento registrada | Pistas originales |
|---|---:|---:|
| [Led Zeppelin](https://discography.ledzeppelin.com/lz1) | 1969-01-12 | 9 |
| [Led Zeppelin II](https://discography.ledzeppelin.com/lz2) | 1969-10-22 | 9 |
| [Led Zeppelin III](https://discography.ledzeppelin.com/lz3) | 1970-10-05 | 10 |
| [Led Zeppelin IV](https://discography.ledzeppelin.com/lz4) | 1971-11-08 | 8 |
| [Houses of the Holy](https://discography.ledzeppelin.com/hoth) | 1973-03-28 | 8 |
| [Physical Graffiti](https://discography.ledzeppelin.com/pg) | 1975-02-24 | 15 |
| [Presence](https://discography.ledzeppelin.com/pres) | 1976-03-31 | 7 |
| [In Through the Out Door](https://discography.ledzeppelin.com/ittod) | 1979-08-15 | 7 |
| [Coda](https://discography.ledzeppelin.com/coda) | 1982-11-19 | 8 |

**Total:** 9 álbumes y 81 pistas de las ediciones originales de referencia. El archivo de datos contiene una fecha ISO por álbum, posición, título, duración, compositores y enlaces de fuente para la lista, la duración y los créditos.

## Criterio de edición

Se registra una edición original de referencia por álbum, con el mercado indicado en `country_or_market` y una nota explícita en `edition_note`. La fecha se refiere al lanzamiento original documentado, no a la fecha de una remasterización. Las fechas y el orden se contrastan con la discografía oficial; las duraciones y los compositores se contrastan con páginas de AllMusic que muestran el listado de pistas.

## Material que queda fuera

Las pistas adicionales de los discos complementarios de las ediciones deluxe de 2014–2015 no se mezclan con el orden original. Tampoco se incorporan álbumes en directo ni recopilatorios. En particular, `Coda` se conserva como álbum de estudio de archivo de ocho pistas, tal como fue publicado en 1982.

## Resultados de la primera revisión de discrepancias

### Duraciones: *Physical Graffiti*

Se sustituyeron las 15 duraciones por las publicadas en la discografía de Jimmy Page, fuente primaria especialmente útil para este álbum. La fuente muestra, por ejemplo, “Kashmir” en 8:37 y “Ten Years Gone” en 6:34; algunas listas de prensajes antiguos presentan tiempos distintos, incluso errores impresos en la carátula. Cada pista del álbum apunta ahora a esa fuente de duración. [Discografía de Jimmy Page — Physical Graffiti](https://jimmypage.com/discography/led-zeppelin/physical-graffiti/).

### Créditos y obras de origen revisados

- **“The Lemon Song”**: se reemplazó Willie Dixon por Chester Arthur Burnett (Howlin’ Wolf) en la lista de compositores y se añadió una nota sobre su relación con “Killing Floor”.
- **“You Shook Me”**: se eliminó J. B. Lenoir del crédito de composición y se dejó Willie Dixon.
- **“Hats Off to (Roy) Harper”**: se normalizó Charles Obscure como seudónimo de Jimmy Page, manteniendo la referencia al material tradicional.
- **“When the Levee Breaks”** y **“In My Time of Dying”**: se añadieron notas que distinguen los créditos de la versión de Led Zeppelin de las obras de blues/gospel de origen.
- **“Boogie with Stu”**: se retiró Ritchie Valens del arreglo `writers` porque la atribución no está confirmada como crédito legal de la edición de referencia. Se mantiene en `credit_note` como discrepancia pendiente de comprobar contra los créditos editoriales de la edición física.
- **“Whole Lotta Love”** y **“Bring It On Home”**: se documentó la relación con las obras de blues de origen y se evita tratar todas las partes de un arreglo como si tuvieran necesariamente la misma atribución.

La fuente oficial de Led Zeppelin diferencia las listas originales de los discos y las pistas extra de los discos complementarios de las ediciones deluxe; por ejemplo, *Physical Graffiti* mantiene 15 pistas en el álbum original y lista aparte siete mezclas/versiones adicionales. [Discografía oficial de Physical Graffiti](https://discography.ledzeppelin.com/pg).

## Segunda fase: contraste sistemático pendiente/en curso

La revisión inicial no equivale todavía a una comparación pista por pista con un ejemplar físico identificado para los ocho álbumes distintos de *Physical Graffiti*. La discografía oficial sirve para fijar la secuencia original y separar el disco principal del material extra, pero no publica de forma consistente duración y créditos editoriales completos para cada pista. AllMusic se usa como fuente secundaria de contraste, no como prueba primaria de lo impreso en una edición específica.

Para cerrar la segunda fase, cada pista debe contrastarse con (1) créditos del LP/CD de referencia o una reproducción legible del sello/contraportada/etiqueta; (2) duración de esa misma edición o un catálogo editorial fiable ligado a ella; y (3) una fuente independiente cuando haya diferencias. Las diferencias de segundos se registrarán como variantes de edición, no se corregirán automáticamente. En canciones adaptadas de blues, folk o espirituales, `writers` debe reflejar los créditos atribuibles a la grabación/edición elegida y `credit_note` explicar por separado la obra de origen, arreglos, seudónimos y disputas.

### Estado de trabajo

- *Physical Graffiti*: duraciones cotejadas con la discografía oficial de Jimmy Page; créditos de canciones basadas en obras anteriores aún requieren comprobación contra créditos editoriales de la edición física.
- *Led Zeppelin*, *Led Zeppelin II*, *Led Zeppelin III*, *Led Zeppelin IV*, *Houses of the Holy*, *Presence*, *In Through the Out Door* y *Coda*: secuencia y fecha cotejadas con la discografía oficial; las duraciones/créditos del archivo proceden principalmente de páginas de álbum de AllMusic y no se deben describir como verificados contra un LP/CD concreto.
- Casos prioritarios de crédito: “Babe I’m Gonna Leave You”, “Dazed and Confused”, “Gallows Pole”, “Hats Off to (Roy) Harper”, “When the Levee Breaks”, “Nobody’s Fault but Mine”, “We’re Gonna Groove” y “I Can’t Quit You Baby”.

## Limitaciones y próximos controles

- Las duraciones publicadas pueden diferir entre prensajes, CD, remasterizaciones y fuentes de catálogo. En *Physical Graffiti* se priorizó la página de Jimmy Page para las duraciones; en los demás álbumes queda pendiente una comparación sistemática pista por pista con fuentes primarias o créditos de la edición física. El total calculado a partir de las duraciones individuales no debe tomarse como duración maestra universal.
- Los créditos de composición de canciones adaptadas o basadas en material tradicional pueden aparecer de forma distinta según la fuente y la edición; deben revisarse con los créditos de la edición física si se requiere una auditoría editorial exhaustiva.
- `verification_status: "verified"` indica que los campos requeridos tienen datos y referencias identificables; no implica que todas las ediciones históricas tengan idénticos tiempos o créditos.

## Fuentes principales

- [Discografía oficial de Led Zeppelin](https://discography.ledzeppelin.com/)
- [Led Zeppelin II — AllMusic](https://www.allmusic.com/album/r11460)
- [Led Zeppelin III — AllMusic](https://www.allmusic.com/album/led-zeppelin-iii-mw0000650405)
- [Led Zeppelin IV — AllMusic](https://www.allmusic.com/album/led-zeppelin-iv-mw0000190736)
- [Houses of the Holy — AllMusic](https://www.allmusic.com/album/houses-of-the-holy-mw0000190648)
- [Physical Graffiti — AllMusic, listado del álbum original](https://www.allmusic.com/album/release/physical-graffiti-mr0001677623)
- [Presence — AllMusic](https://www.allmusic.com/album/presence-mw0000194594)
- [In Through the Out Door — AllMusic](https://www.allmusic.com/album/in-through-the-out-door-mw0000650404)
- [Coda — AllMusic](https://www.allmusic.com/album/coda-mw0000194592)
