# Resumen

Este repositorio incluye un conjunto de ficheros .Rmd con introducción a distintos paquetes [htmlwidgets](http://www.htmlwidgets.org/index.html).

Los ficheros son los siguientes:

- **htmlwidgets_leaflet.Rmd**: cómo generar mapas interactivos mediante el paquete *leaflet*.
- **htmlwidgets_dygraphs.Rmd**: cómo generar series temporales interactivas mediante el paquete *dygraphs*.
- **htmlwidgets_visnetwork.Rmd**: cómo generar grafos interactivos mediante el paquete *visnetwork*.


# Uso

Cada fichero .Rmd es un tutorial autocontenido, en que se combinan explicaciones y ejercicios en R. Se trata de ficheros RMarkdown, con salida learnr::tutorial. Para ejecutarlos, hacer click en el botón *Run Document* de RStudio, o bien desde consola ejecutar la función *rmarkdown::run()*
Se trata de aplicaciones Shiny (con interfaz RMarkdown), de manera que existe una sesión de R ejecutándose en tanto el usuario interactúa con el tutorial.