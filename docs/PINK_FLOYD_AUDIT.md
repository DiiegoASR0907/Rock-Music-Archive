# Pink Floyd — cobertura inicial y pendientes de auditoría

## Alcance

Primera carga de los 15 álbumes considerados en la discografía de estudio de Pink Floyd, desde *The Piper at the Gates of Dawn* (1967) hasta *The Endless River* (2014). Se toma como referencia inicial la secuencia de pistas publicada en la [discografía oficial de Pink Floyd](https://archive.pinkfloyd.com/music/albums).

Esta es una **pasada de cobertura**, no una auditoría discográfica final. Los 15 registros están marcados como `needs_verification`: las pistas están cargadas, pero las duraciones y los créditos de composición no se han completado todavía porque deben verificarse contra una edición identificada y fuentes apropiadas. No interpretar campos vacíos como créditos inexistentes ni duraciones nulas como duración cero.

## Álbumes cargados

1. *The Piper at the Gates of Dawn* (1967)
2. *A Saucerful of Secrets* (1968)
3. *More* (1969)
4. *Ummagumma* (1969)
5. *Atom Heart Mother* (1970)
6. *Meddle* (1971)
7. *Obscured by Clouds* (1972)
8. *The Dark Side of the Moon* (1973)
9. *Wish You Were Here* (1975)
10. *Animals* (1977)
11. *The Wall* (1979)
12. *The Final Cut* (1983)
13. *A Momentary Lapse of Reason* (1987)
14. *The Division Bell* (1994)
15. *The Endless River* (2014)

## Criterios y excepciones que deben conservarse

- **Edición de referencia:** se usa la secuencia original británica como punto de partida. Las fechas exactas, el sello y cualquier diferencia entre territorios deben verificarse antes de marcar registros como `verified`.
- **Créditos:** cargar compositores tal como figuran acreditados en la edición de referencia. No atribuir automáticamente todos los integrantes a cada pista ni sustituir créditos editoriales por inferencias sobre quién escribió o interpretó una parte.
- **Duraciones:** registrar duración por pista y total de álbum solo después de identificar la edición/fuente; las mezclas, reediciones y formatos pueden diferir.
- **Ummagumma:** álbum doble híbrido; el primer disco contiene actuaciones en directo y el segundo material de estudio. No debe describirse como si todas las pistas fueran grabaciones de estudio.
- **More** y **Obscured by Clouds:** son bandas sonoras publicadas como álbumes de Pink Floyd; mantener la nota de contexto y no confundirlas con recopilaciones.
- **The Wall:** verificar orden y títulos pista por pista, así como la representación de las dos caras originales y posibles diferencias de puntuación.
- **The Final Cut:** comprobar la edición original frente a reediciones que añaden “When the Tigers Broke Free”.
- **A Momentary Lapse of Reason:** distinguir la mezcla original de 1987 de la remezcla de 2019 y sus cambios de créditos, instrumentación o duración.
- **The Division Bell:** contrastar la secuencia completa y los créditos, especialmente las canciones con participación de varios autores.
- **The Endless River:** contrastar la división por lados del vinilo original y la secuencia de las ediciones CD/digitales.

## Próxima auditoría

1. Verificar fecha, país/mercado, sello y secuencia de pistas de cada lanzamiento original.
2. Añadir fuente específica por álbum y referencias pista por pista para créditos y duraciones.
3. Documentar discrepancias entre créditos impresos, bases de datos y reediciones, sin resolverlas silenciosamente.
4. Calcular duración total solo cuando las duraciones de la edición elegida estén completas.
5. Cambiar `verification_status` a `verified` únicamente cuando los campos requeridos y sus fuentes hayan sido revisados.
6. Después de completar la cobertura de las demás bandas, realizar la auditoría histórica global y comparar los registros entre bandas.

## Fuentes de partida

- [Pink Floyd — discografía oficial de álbumes](https://archive.pinkfloyd.com/music/albums): fuente primaria para el alcance general y los listados de pistas.
- [Pink Floyd — discografía oficial actual](https://www.pinkfloyd.com/music/): ayuda a distinguir álbumes, reediciones, directos y recopilaciones.
- [Pink Floyd Hyperbase](https://pinkfloydhyperbase.dk/albums/index.php): fuente secundaria de contraste para canciones y grabaciones; no reemplaza los créditos impresos de la edición elegida.
