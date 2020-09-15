--- 
title: "Técnicas de Remuestreo"
author: "Ricardo Cao Abad (rcao@udc.es) y Rubén Fernández Casal (rfcasal@udc.es)"
institute: 
   - "Departamento de Matemáticas"
   - "Grupo de investigación de Modelización, Optimización e Inferencia Estadística (MODES)"
   - "Centro de Investigación en Tecnologías de la Información y las Comunicaciones (CITIC)"
date: "2020-03-31"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: rubenfcasal/book_remuestreo
description: "Apuntes de la asignatura de Técnicas de Remuestreo del Máster en Técnicas Estadísticas."
---


# Prólogo {-}

Este libro contiene los apuntes de la asignatura de [Técnicas de Remuestreo](http://eamo.usc.es/pub/mte/index.php/es/?option=com_content&view=article&id=2202&idm=22&a%C3%B1o=2019) del [Máster en Técnicas Estadísticas](http://eio.usc.es/pub/mte). 

Este libro ha sido escrito en [R-Markdown](http://rmarkdown.rstudio.com) empleando el paquete [`bookdown`](https://bookdown.org/yihui/bookdown/)  y está disponible en el repositorio Github: [rubenfcasal/book_remuestreo](https://github.com/rubenfcasal/book_remuestreo). 
Se puede acceder a la versión en línea a través del siguiente enlace:

<https://rubenfcasal.github.io/book_remuestreo>.

<!-- 
<a class="btn pull-left js-toolbar-action" aria-label="PDF" title="PDF" href="#"><i class="fa fa-file-pdf-o"></i></a> 
-->

donde puede descargarse en formato [pdf](https://rubenfcasal.github.io/book_remuestreo/book_remuestreo.pdf).

Para ejecutar los ejemplos mostrados en el libro será necesario tener instalados los siguientes paquetes:
[`boot`](https://cran.r-project.org/web/packages/boot/index.html), [`bootstrap`](https://cran.r-project.org/web/packages/bootstrap/index.html), [`survival`](https://cran.r-project.org/web/packages/survival/index.html), [`forecast`](https://cran.r-project.org/web/packages/forecast/index.html), [`MASS`](https://cran.r-project.org/web/packages/MASS/index.html).
Por ejemplo mediante el comando:

```r
install.packages(c("boot", "bootstrap", "survival", "forecast", "MASS"))
```

Para generar el libro (compilar) serán necesarios paquetes adicionales, 
para lo que se recomendaría consultar el libro de ["Escritura de libros con bookdown" ](https://rubenfcasal.github.io/bookdown_intro) en castellano.


Este obra está bajo una licencia de [Creative Commons Reconocimiento-NoComercial-SinObraDerivada 4.0 Internacional ](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.es_ES) 
(esperamos poder liberarlo bajo una licencia menos restrictiva más adelante...).


\includegraphics[width=1.22in]{by-nc-nd-88x31} 



