# Equilibrio

Juego para teléfono: inclina el dispositivo para mantener la pelota en el plato.

## Subir a GitHub Pages
1. Crea un repositorio en GitHub. Para usarlo con PWABuilder/Google Play, ponle de nombre
   `TU-USUARIO.github.io` (así la web queda en la raíz: https://TU-USUARIO.github.io/).
2. Sube TODO el contenido de esta carpeta (incluido `.nojekyll` e `icons/`) a la rama `main`.
3. En Settings > Pages elige "Deploy from a branch", rama `main`, carpeta `/ (root)`.
4. Espera 1-2 minutos y abre la URL desde el teléfono con Chrome.

## Instalar en el teléfono (sin APK)
Abre la URL en Chrome (Android) > menú ⋮ > "Instalar aplicación" / "Añadir a pantalla de inicio".

## Generar el APK/AAB
1. Entra a https://www.pwabuilder.com, pega la URL y pulsa Start.
2. Package for stores > Android. Opciones sugeridas: orientación portrait, modo fullscreen.
3. Descarga el zip. Incluye el APK/AAB, la clave de firma y `assetlinks.json`.
4. Sube `assetlinks.json` a tu sitio en la ruta `/.well-known/assetlinks.json`
   (carpeta `.well-known` en la raíz del repositorio) para quitar la barra de URL.
