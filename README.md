# Web personal de Ernesto López Losa

Sitio estático en español e inglés, publicado en [ernestolopezlosa.github.io](https://ernestolopezlosa.github.io/) desde el [repositorio ernestolopezlosa/ernestolopezlosa.github.io](https://github.com/ernestolopezlosa/ernestolopezlosa.github.io). No necesita instalar programas ni contratar alojamiento. Tiene cuatro páginas independientes en cada idioma:

| Sección | Español | Inglés |
| --- | --- | --- |
| Portada | `index.html` | `en.html` |
| Investigación | `investigacion.html` | `research.html` |
| Docencia | `docencia.html` | `teaching.html` |
| Currículum | `cv.html` | `cv-en.html` |

`styles.css` controla el diseño: fondo gris neutro, tarjetas blancas para las publicaciones, detalles azules y una cabecera oscura en la portada. `site.js` controla las tres vistas de Investigación. Las imágenes `figure-*.svg` son esquemas originales de los temas de cada trabajo; **no representan datos ni reproducen figuras publicadas**. La fotografía `portrait.jpg` procede del [perfil público de Ernesto López Losa en Academia.edu](https://ehu.academia.edu/ernestolopezlosa); el autor confirmó que desea usarla aquí.

## Cómo se publicó en GitHub Pages

1. Se cambió el usuario de GitHub a `ernestolopezlosa` y el repositorio público a `ernestolopezlosa.github.io`.
2. Se subieron los ocho archivos HTML, `styles.css`, `site.js`, `favicon.svg`, `portrait.jpg` y `.nojekyll` a la raíz del repositorio mediante **Add file → Upload files**.
3. En **Settings → Pages**, GitHub seleccionó automáticamente **Deploy from a branch**, `main` y `/(root)`. La ejecución de **pages-build-deployment** terminó correctamente.
4. Se comprobó que la dirección pública carga las ocho páginas.

Si en el futuro creas otra web en un repositorio con otro nombre, la dirección tendrá el formato `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Actualizar la web

Para corregir textos o añadir publicaciones, abre el archivo de la sección correspondiente en el repositorio y usa el icono del lápiz; después confirma con **Commit changes**. Para modificar colores o tipografía, edita `styles.css`. Las imágenes de las publicaciones son los archivos `figure-*.svg`. Si prefieres reemplazar archivos completos, usa **Add file → Upload files** en el repositorio. Cada cambio confirmado en `main` vuelve a publicar el sitio.

## Si quieres retirar la web

Puedes retirar la publicación y conservar los archivos: entra en el repositorio, abre **Settings → Pages** y usa **Unpublish site**. La página dejará de estar disponible, pero podrás volver a publicarla más adelante. También puedes eliminar el sitio seleccionando `None` como rama de publicación en **Settings → Pages**. Si quieres borrar también los archivos y el repositorio, ve a **Settings → General → Danger Zone → Delete this repository**. [Opciones explicadas por GitHub](https://docs.github.com/en/pages/getting-started-with-github-pages/deleting-a-github-pages-site).

Esta carpeta no incluye los CV originales porque contienen datos personales que no corresponden a la web pública.

## Fuentes de los datos

Contenido basado en los CV facilitados (marzo de 2025 y junio de 2026). Se contrastaron el correo y la afiliación con el [perfil institucional de EHU](https://www.ehu.eus/es/web/graduak/grado-economia/profesorado?idPdi=3926&redirect=fichaPDI), y los enlaces de los artículos con sus páginas editoriales. La selección bibliográfica no pretende ser una lista completa.

## Ayuda oficial

- [Guía inicial de GitHub Pages](https://docs.github.com/en/pages/quickstart)
- [Cómo subir archivos a un repositorio](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [Configurar la rama de publicación](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
