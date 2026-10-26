# Carta de aniversario

Sitio estático en español, listo para publicarse gratis con GitHub Pages. No necesita instalar dependencias ni compilar.

## Publicarlo en GitHub

1. Crea un repositorio en GitHub y sube todos los archivos de esta carpeta, incluida la carpeta oculta `.github`.
2. En GitHub, abre **Settings → Pages** y selecciona **GitHub Actions** como fuente de publicación.
3. La acción `Publicar en GitHub Pages` se ejecutará al subir cambios a la rama `main` (también puedes ejecutarla desde **Actions → Run workflow**).
4. Cuando termine correctamente, encontrarás el enlace del sitio en **Settings → Pages**.

Si tu rama principal se llama `master`, cambia `main` por `master` en `.github/workflows/pages.yml`.

## Personalizar la carta

Abre `index.html` y modifica los textos dentro de `const CONFIG` (título, fecha, saludo, párrafos y firma). Guarda y sube el cambio a GitHub para que se publique la nueva versión.

La fuente decorativa se carga desde Google Fonts. Si no está disponible, el navegador usa fuentes locales de respaldo.
