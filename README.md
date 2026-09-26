# Instrucciones

## Paso 1:

Dale click al link del sitio web que aparece junto al "About" (en la parte superior derecha de este sitio) para que veas en general cuál es objetivo a obtener al finalizar este instructivo.

## Paso 2:

1. Ir al botón de "Use this template" -> "Create a new repository"
2. Llena con el nombre que quieras que tenga tu repositorio

**OJO:** Ahora ya estamos en tu repositorio. Ya no más en la plantilla

## Paso 3:

Ir a Settings -> Pages -> Build and deployment -> Source -> GitHub Actions. Lo único que verás en un cintillo azul que dice que se cambiaron los ajustes.

## Paso 4:

+ Ahora vamos a crear la GitHub Page, i.e. el link donde la gente consumirá tu sitio web

+ Como en sesiones anteriores, el template ya contiene todos los archivos necesarios para que veas el sitio web objetivo

+ Dentro del sitio de tu repositorio. Busca la sección de "Actions" en la parte superior

+ En la barra lateral izquierda encontrarás la sección "Actions". Justo abajito aparece la sección "All workflows" y justo abajito aparece la sección "Publicar sitio Quarto en GitHub Pages". Dale click a este último

+ En la sección principal verás un cintillo azul que dice "This workflow has a workflow_dispatch event trigger" y un botón "Run workflow". En el selector de dicho botón dale click a "Run workflow" y la magia empezará a ocurrir.... 

+ Ir a "Actions" de nuevo. Dar click al único workflow y esperar a que termine

+ 🚨🐢⌛**Importante:**⌛🐢🚨 En esta sesión en particular, este proceso tardará un poco más que antes. Esto se debe a que ahora se agregaron más elementos gráficos que GitHub tiene que renderizar... y esto toma tiempo

+ Una vez que termine el workflow te mostrará el link de tu sitio web

+ Para que lo tengas a la mano todo el tiempo, haz lo siguiente:

  + Ve a la página principal de tu repositorio (aquí en GitHub). Del lado derecho encontrarás la palabra "About" con una tuerquita de lado derecho
  + Marca la casilla de "Use your GitHub Pages website" y "Save changes". Ahora verás la dirección de tu sitio justo debajo de la palabra "About"

+ Si haces cambios en tus archivos para modificar algo. Modifica todo lo que tengas que modificar y después vuelve a hacer: Actions -> All workflows -> Publicar sitio Quarto en GitHub Pages -> Run workflow y espera a que vuelva a renderear tu sitio

+ **Observación:** Si una vez que terminó el workflow tu sitio parece no haber hecho los cambios, dale refresh en tu navegador

## Paso 5:

+ Revisa el contenido de los archivos `reporte-05.qmd`, `reporte-06.qmd` y `reporte-07.qmd` y compáralo con el resultado que vez en tu sitio web.

+ El archivo `reporte-06.qmd` muestra un formato que no habíamos visto hasta el momento: el formato dashboard

+ El archivo `reporte-05.qmd` muestra una líbrería para resaltar algunos resultados gráficamente y muestra cómo se pueden definir sub-pestañas en cada página para mejorar la navegación a través del sitio web.

+ El archivo `reporte-07.qmd` muestra algunos elementos gráficos sencillos que ayudan a que las visualizaciones comuniquen mejor

+ Finalmente revisa el archivo `_quarto.yml` para que veas que efectivamente mostramos los reportes 5, 6 y 7

+ Sólo por curiosidad, nota que en los archivos `requirements.txt` y `DESCRIPTION` aparecen los nombres de librerías de R/Python que no usamos en las sesiones anteriores pero ahora sí

