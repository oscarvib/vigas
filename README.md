# Vigas · Cortantes y Flectores

Aplicación web (instalable en Chrome) para practicar diagramas de **esfuerzos cortantes** y **momentos flectores**.

- Eliges nº y tipo de apoyos (empotramiento, apoyo fijo, apoyo móvil), nº de cargas puntuales, momentos y cargas distribuidas (uniforme, triangular, trapezoidal).
- Genera posiciones y valores aleatorios; los datos se pueden editar después.
- Resuelve vigas isostáticas e hiperestáticas (método de rigidez): reacciones, ecuaciones de equilibrio, diagramas V y M, máximos y leyes por tramos.
- Funciona sin conexión una vez instalada.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo (p. ej. `vigas`) y sube todos estos ficheros respetando la carpeta `icons/`.
2. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)` → **Save**.
3. Al cabo de un minuto estará en `https://TU_USUARIO.github.io/vigas/`.
4. Ábrelo en Chrome y pulsa **⬇ Instalar app** (o el icono de instalar en la barra de direcciones).

Si cambias `index.html`, sube el número de versión de `CACHE` en `sw.js` para forzar la actualización.
