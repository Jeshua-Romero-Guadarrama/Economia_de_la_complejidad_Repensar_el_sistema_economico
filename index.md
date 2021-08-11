---
title: "Economia de la complejidad: Repensar el sistema económico"
cover-image: "images/cover.png"
author: "Jeshua Romero Guadarrama"
date: "2021-08-10"
site: bookdown::bookdown_site
output: 
  bookdown::word_document2: default
  bookdown::pdf_book:
    pandoc_args: ["+RTS", "-K64m", "-RTS", "--csl", "apa-old-doi-prefix.csl"]
    includes:
      in_header: preamble.tex
    citation_package: natbib
    keep_tex: yes
  bookdown::gitbook:
    config:
      toc:
        collapse: subsection
        scroll_highlight: yes
      fontsettings:
        theme: white
        family: serif
        size: 2
    split_by: section+number
    highlight: tango
    includes:
      in_header: [header_include.html]
always_allow_html: yes
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
biblatexoptions:
  - sortcites
link-citations: yes
github-repo: "https://github.com/Jeshua-Romero-Guadarrama/Economia_de_la_complejidad_repensar_el_sistema_economico"
description: "El presente texto nace al calor de las exigencias pedagógicas de todos los ciudadanos mexicanos interesados en la ciencia política. A partir de los años que he pasado detrás de innumerables libros (con el objetivo de gestar, buscar y probar nuevos conocimientos), ve la luz pública este trabajo, que fué creciendo y cambiando lentamente, empezando como apuntes de la universidad. Creo que ha alcanzado la madurez suficiente para ser compartido con el mundo. Con independencia de su valor intrínseco, tengo entendido que hace mucho tiempo que no se hacía una obra de este tipo (lo que ciertamente le corresponde al lector juzgar). En la bibliografía especializada disponible en castellano, el antecedente más inmediato que conozco es **Teorías políticas contemporáneas: Una introducción**, de Klaus von Beyme. La primera edición alemana es de 1972, cuya edición en castellano (difícil de hallar), es de 1977. Esa obra fué mi primera orientación; en consecuencia, mantengo en lo fundamental su esquema y algo de su terminología (tengo una deuda intelectual con el formidable profesor de Heildelberg)."
url: 'https://jeshua-romero-guadarrama.github.io/Economia_de_la_complejidad_repensar_el_sistema_economico/'
tags: [Academia, Teoría política, Ciencia política, Teoría política, Práctica política]
favicon: "images/logo.png"
---

# Prefacio {-}














<center><img style = 'width:60%;' src='images/Economia_de_la_complejidad_repensar_el_sistema_economico.png'></center>



<center><img style = 'width:30%;' src='images/cover.png'></center>
<br><center><img style='float: center; width:50%' src='images/logo_claim_en_rgb.png'/></center>
<br><center><a href="https://www.jeshuanomics.com/" target="blank">Publicado por Jeshua Romero Guadarrama en colaboración con JeshuaNomics:</a></center>
<br><center><a href="https://github.com/JeshuaNomics" class="fa fa-github"><span class="label">  Git Hub</span></a>
<a href="https://www.facebook.com/JeshuaNomics/" class="fa fa-facebook"><span class="label">  Facebook</span></a>
<a href="https://twitter.com/JeshuaNomics" class="fa fa-twitter"><span class="label">  Twitter</span></a>
<a href="https://www.linkedin.com/in/jeshua-romero-guadarrama/" class="fa fa-linkedin"><span class="label">  Linkedin</span></a>
<a href="https://vk.com/jeshuanomics" class="fa fa-vk"><span class="label">  Vkontakte</span></a>
<a href="https://jeshuanomics.tumblr.com/" class="fa fa-tumblr"><span class="label">  Tumblr</span></a>
<a href="https://www.youtube.com/channel/UCY7f84mJGvMN7TF7XI4-Jgg?view_as=subscriber/" class="fa fa-youtube-play"><span class="label">  YouTube</span></a>
<a href="https://www.instagram.com/JeshuaNomics/" class="fa fa-instagram"><span class="label">  Instagram</span></a></center>

<br> Jeshua Romero Guadarrama es economista y actuario por la <a href="http://www.economia.unam.mx/">Universidad Nacional Autónoma de México</a>, quien ha construido el presente proyecto en colaboración con <a href="https://www.jeshuanomics.com">JeshuaNomics</a>, ubicado en la Ciudad de México, se puede contactar mediante el siguiente correo electrónico: jeshuanomics@gmail.com.
<br>
<br> Última actualización el martes 10 del 08 de 2021
<br>



Proporciona una exploración de las consecuencias de las diferencias ontológicas entre objetos naturales y sociales.

Examina las teorías históricamente ofrecidas con respecto a la causalidad social y la agencia y propone y defiende algunas alternativas

Estipula las diferencias fundamentales de causalidad en la naturaleza en comparación con la vida social, con especial atención a la economía.

Examina la naturaleza de la causalidad y la agencia en la vida social.


Examina el problema de la adecuación descriptiva en la teoría económica, incluidos los límites de simplificación de la realidad requeridos por el modelado

Plantea preguntas sobre cómo las teorías de la economía deben proporcionar espacio para consideraciones morales

Hace las preguntas importantes sobre el papel de la teoría económica


Los estudiantes con poca experiencia en el análisis avanzado de políticas a menudo tienen dificultades para entender los beneficios de desarrollar habilidades de programación estadística en **R** al momento de aplicar diversos métodos descriptivos e inferenciales. <i>Análisis político con R</i> por Jeshua Romero Guadarrama (2021), ofrece una introducción interactiva a los aspectos esenciales de la programación por medio del lenguaje y software estadístico **R**, así como una guía para la aplicación de la teoría política y análisis detallado de políticas públicas en entornos específicos. En otras palabras, el objetivo es que los estudiantes se adentren al mundo de la política aplicada mediante ejemplos empíricos presentados en la vida diaria y haciendo uso de las habilidades de programación recién adquiridas. Dicho objetivo se encuentra respaldado por ejercicios de programación interactivos y la incorporación de visualizaciones dinámicas de conceptos fundamentales mediante la flexibilidad de JavaScript, a través de la biblioteca D3.js.

En los últimos años, el lenguaje de programación estadística **R** se ha convertido en una parte integral del plan de estudios de las clases de análisis político y estadística que se imparten en las universidades. Regularmente una gran parte de los estudiantes no han estado expuestos a ningún lenguaje de programación antes y, por lo tanto, tienen dificultades para participar en el aprendizaje de **R** por sí mismos. Con poca experiencia en el análisis avanzado de estadísticas, es natural que los novicios tengan dificultades para comprender los beneficios de desarrollar habilidades en **R** para aprender y aplicar la estadística. Estos incluyen particularmente la capacidad de realizar, documentar y comunicar estudios empíricos y tener las facilidades para programar estudios de simulación, lo cual es útil para, por ejemplo, comprender y validar teoremas que generalmente no se asimilan o entienden fácilmente con el estudio de las fórmulas. Al ser un economista aplicado y analista político, me gustaría que mis colegas desarrollen capacidades de gran valor; en consecuencia, deseo compartir con las nuevas generaciones de politólogos y economistas mis conocimientos.

En lugar de confrontar a los estudiantes con ejercicios de codificación puros y literatura clásica complementaria, he pensado que sería mejor proporcionar material de aprendizaje interactivo que combine el código en **R** con el contenido del curso de texto *Introducción a la Econometría* de @stock2015 que sirve de base para el presente material. El presente trabajo es un complemento empírico interactivo al estilo de un informe de investigación reproducible que permite a los estudiantes no solo aprender cómo los resultados de los estudios de casos se pueden replicar con **R**, sino que también fortalece su capacidad para utilizar las habilidades recién adquiridas en otras aplicaciones empíricas.

#### Las convenciones usadas en el presente curso {-}

+ El texto *en cursiva* indica nuevos términos, nombres, botones y similares.

+ El texto **en negrita** se usa generalmente en párrafos para referirse al código **R**. Esto incluye comandos, variables, funciones, tipos de datos, bases de datos y nombres de archivos.

+ <code>Texto de ancho constante sobre fondo gris</code> indica un código **R** que usted puede escribir literalmente. Puede aparecer en párrafos para una mejor distinción entre declaraciones de código ejecutables y no ejecutables, pero se encontrará principalmente en forma de grandes bloques de código **R**. Estos bloques se denominan fragmentos de código.

#### Reconocimiento {-}

A mi alma máter: Universidad Nacional Autónoma de México (Facultad de Economía y Facultad de Ciencias). Por brindarme valiosas oportunidades que coadyuvaron a mi formación.



