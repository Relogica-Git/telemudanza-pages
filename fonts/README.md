# Fuentes locales de Telemudanza

Aprobadas el 6 de septiembre de 2026: **Inter Variable** para lectura y controles; **Work Sans Variable** para titulares.

Los dos WOFF2 se conservan en esta carpeta y se sirven desde el dominio propio. No hay peticiones a Google Fonts ni a un CDN.

- inter-latin-variable.woff2: Fontsource @fontsource-variable/inter 5.3.0.
- work-sans-latin-variable.woff2: Fontsource @fontsource-variable/work-sans 5.3.0.
- Subconjunto latino, incluidos los caracteres castellanos. Si se amplían alfabetos, añadir el subconjunto necesario sin sustituir silenciosamente estos archivos.
- Licencias OFL conservadas en Inter-LICENSE.txt y WorkSans-LICENSE.txt.
- font-display: swap; pesos variables 100–900.
- npm run check:font verifica ambos binarios.
- Al reemplazar binarios, usar nombres versionados para evitar cachés obsoletas.

Söhne no es un requisito ni una dependencia pendiente de esta entrega.
