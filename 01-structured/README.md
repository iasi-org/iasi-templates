# IASI template · book / structured

Plantilla canónica mínima para un libro IASI con `publication.strategy: structured`.

También funciona como proyecto de integración para probar `iasi.quarto` sin tener que renderizar un volumen real completo.

## Estructura intencional

- 2 partes reales.
- 2 capítulos por parte.
- Secciones y subsecciones.
- Figura y tabla con referencias cruzadas.
- Referencia entre partes.
- Perfiles HTML y PDF.

## Regla IASI que debe validar

En `structured`, la numeración editorial de capítulos comienza en 1 dentro de cada `part`.

Resultado esperado:

```text
Primera parte
  1 Primer capítulo
  2 Segundo capítulo

Segunda parte
  1 Primer capítulo de la segunda parte
  2 Segundo capítulo de la segunda parte
```

El archivo `_book-structure.yml` se incluye en esta plantilla para que el proyecto pueda renderizarse inmediatamente y para dejar explícita la estructura que `iasi.quarto` debe generar.
