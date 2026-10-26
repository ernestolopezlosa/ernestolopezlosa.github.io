# Web personal de Ernesto López Losa

Sitio estático en español e inglés, publicado en [ernestolopezlosa.github.io](https://ernestolopezlosa.github.io/) desde el [repositorio ernestolopezlosa/ernestolopezlosa.github.io](https://github.com/ernestolopezlosa/ernestolopezlosa.github.io). No necesita instalar programas ni contratar alojamiento. Tiene siete páginas independientes en cada idioma:

| Sección | Español | Inglés |
| --- | --- | --- |
| Portada | `index.html` | `en.html` |
| Investigación: selección | `investigacion.html` | `research.html` |
| Publicaciones completas | `publicaciones.html` | `publications.html` |
| Proyectos de investigación | `proyectos.html` | `projects.html` |
| Presentaciones a congresos | `congresos.html` | `conferences.html` |
| Docencia | `docencia.html` | `teaching.html` |
| Currículum | `cv.html` | `cv-en.html` |

`styles.css` controla el diseño: tipografía sans serif DM Sans, fondo gris neutro, tarjetas blancas para las publicaciones, detalles azules y una cabecera oscura en la portada. La página de Investigación presenta una selección visual y enlaza a las páginas independientes de publicaciones, proyectos y congresos; cada una tiene un enlace de regreso. Las imágenes `figure-*.png` son gráficos y mapas relacionados con los trabajos. No muestran pies de figura; las imágenes enlazan con sus fuentes, documentadas más abajo. La fotografía `portrait.jpg` procede del [perfil público de Ernesto López Losa en Academia.edu](https://ehu.academia.edu/ernestolopezlosa); el autor confirmó que desea usarla aquí.

## Cómo se publicó en GitHub Pages

1. Se cambió el usuario de GitHub a `ernestolopezlosa` y el repositorio público a `ernestolopezlosa.github.io`.
2. Se subieron los archivos HTML, `styles.css`, `favicon.svg`, `portrait.jpg` y `.nojekyll` a la raíz del repositorio mediante **Add file → Upload files**.
3. En **Settings → Pages**, GitHub seleccionó automáticamente **Deploy from a branch**, `main` y `/(root)`. La versión actual tiene catorce páginas HTML. La ejecución de **pages-build-deployment** terminó correctamente.
4. Se comprobó que la dirección pública carga las páginas del sitio.

Si en el futuro creas otra web en un repositorio con otro nombre, la dirección tendrá el formato `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Actualizar la web

Para corregir textos o añadir publicaciones, abre el archivo de la sección correspondiente en el repositorio y usa el icono del lápiz; después confirma con **Commit changes**. Para modificar colores o tipografía, edita `styles.css`. Las imágenes de las publicaciones son los archivos `figure-*.png`. Si prefieres reemplazar archivos completos, usa **Add file → Upload files** en el repositorio. Cada cambio confirmado en `main` vuelve a publicar el sitio.

### Fuentes de las figuras

- `figure-respectable-living.png`: figura 3 de [López Losa (2026)](https://doi.org/10.1017/S0212610926101086), CC BY 4.0.
- `figure-daily-annual-wages.png`: figura 5 de [Bartolomé Rodríguez et al. (2026)](https://doi.org/10.1007/978-3-031-91930-5_10), CC BY-NC-ND 4.0.
- `figure-fishing-constraints.png`: figura 1 de [López Losa (2023)](https://revistes.ub.edu/index.php/HistoriaIndustrial/article/download/36781/38653/113832).
- `figure-little-divergence.png`: figura 5 de la [versión de trabajo de López Losa y Piquero Zarauz (2016)](https://media.timtul.com/media/web_aehe/dt-aehe-1607_20240108094523.pdf). Corresponde a una versión previa del artículo de 2021.
- `figure-royal-palace.png`: gráfico original construido con los intervalos salariales de la tabla 1 de [García-Zúñiga y López Losa (2021)](https://doi.org/10.1111/ehr.13048), p. 694; los datos son reales de vellón por día en 1790.
- `figure-hamilton-prices.png`: figura 5 de [López Losa (2013)](https://recyt.fecyt.es/index.php/IHE/article/download/70523/42670/220135).
- `figure-basque-guilds.png` y `figure-fishing-rights.png`: mapas originales elaborados con la costa de [Natural Earth](https://www.naturalearthdata.com/downloads/10m-physical-vectors/) (dominio público) y las posiciones de puertos publicadas por [Euskadiko Kirol Portuak](https://ekp.euskadi.eus/es/). Muestran ubicación geográfica, no resultados cuantitativos de los artículos.

## Si quieres retirar la web

Puedes retirar la publicación y conservar los archivos: entra en el repositorio, abre **Settings → Pages** y usa **Unpublish site**. La página dejará de estar disponible, pero podrás volver a publicarla más adelante. También puedes eliminar el sitio seleccionando `None` como rama de publicación en **Settings → Pages**. Si quieres borrar también los archivos y el repositorio, ve a **Settings → General → Danger Zone → Delete this repository**. [Opciones explicadas por GitHub](https://docs.github.com/en/pages/getting-started-with-github-pages/deleting-a-github-pages-site).

Esta carpeta no incluye los CV originales porque contienen datos personales que no corresponden a la web pública.

## Fuentes de los datos

Contenido basado en los CV facilitados (marzo de 2025 y junio de 2026). La bibliografía completa reproduce los trabajos recogidos en el CV extenso, añade los de 2026 y excluye manuscritos en preparación. La sección de congresos reúne las intervenciones consignadas en ambos CV para los últimos quince años (2011–2026). Se contrastaron el correo y la afiliación con el [perfil institucional de EHU](https://www.ehu.eus/es/web/graduak/grado-economia/profesorado?idPdi=3926&redirect=fichaPDI), y los enlaces de los artículos con sus páginas editoriales. La lista publicada corresponde a las entradas de los CV facilitados y no sustituye a una bibliografía actualizada después de 2026.

## Ayuda oficial

- [Guía inicial de GitHub Pages](https://docs.github.com/en/pages/quickstart)
- [Cómo subir archivos a un repositorio](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [Configurar la rama de publicación](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
