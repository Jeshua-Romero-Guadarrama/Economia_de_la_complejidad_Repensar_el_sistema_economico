# Economia de la complejidad: Repensar el sistema económico

<br/>
<br/>

<p align="center"><img align="center" src="https://github.com/Jeshua-Romero-Guadarrama/Economia_de_la_complejidad_repensar_el_sistema_economico/blob/main/images/Economia_de_la_complejidad_repensar_el_sistema_economico.png" width="30%" height="30%"></p>

<br/>
<br/>

## 📖 Sobre el curso

<p><img src="https://github.com/Jeshua-Romero-Guadarrama/Econoalgoritmia/raw/main/images/logo.png" alt="logo" align="right" width="20%" height="20%"> 
El presente texto nace al calor de las exigencias pedagógicas de todos los ciudadanos mexicanos interesados en la ciencia política. A partir de los años que he pasado detrás de innumerables libros (con el objetivo de gestar, buscar y probar nuevos conocimientos), ve la luz pública este trabajo, que fué creciendo y cambiando lentamente, empezando como apuntes de la universidad. Creo que ha alcanzado la madurez suficiente para ser compartido con el mundo. Con independencia de su valor intrínseco, tengo entendido que hace mucho tiempo que no se hacía una obra de este tipo (lo que ciertamente le corresponde al lector juzgar). En la bibliografía especializada disponible en castellano, el antecedente más inmediato que conozco es **Teorías políticas contemporáneas: Una introducción**, de Klaus von Beyme. La primera edición alemana es de 1972, cuya edición en castellano (difícil de hallar), es de 1977. Esa obra fué mi primera orientación; en consecuencia, mantengo en lo fundamental su esquema y algo de su terminología (tengo una deuda intelectual con el formidable profesor de Heildelberg).</p>

El curso se puede consultar aquí: [Economia de la complejidad: Repensar el sistema económico](http://economiadelacomplejidadrepensarelsistemaeconomico.jeshuanomics.com/)

<br/>
<br/>

## ✍🏻 Referencia bibliográfica

Romero, G. J. (2021). *Economía de la complejidad: Repensar el sistema económico*. JeshuaNomics.

<br/>
<br/>

## 📦 Paquetería necesaria

Para ejecutar los ejemplos mostrados en el libro será necesario tener instalados los siguientes paquetes:

[`lattice`](https://cran.r-project.org/web/packages/lattice/index.html), 
[`ggplot2`](https://cran.r-project.org/web/packages/ggplot2/index.html), 
[`foreign`](https://cran.r-project.org/web/packages/foreign/index.html), 
[`car`](https://cran.r-project.org/web/packages/car/index.html), 
[`leaps`](https://cran.r-project.org/web/packages/leaps/index.html), 
[`MASS`](https://cran.r-project.org/web/packages/MASS/index.html), 
[`RcmdrMisc`](https://cran.r-project.org/web/packages/RcmdrMisc/index.html), 
[`lmtest`](https://cran.r-project.org/web/packages/lmtest/index.html), 
[`glmnet`](https://cran.r-project.org/web/packages/glmnet/index.html), 
[`mgcv`](https://cran.r-project.org/web/packages/mgcv/index.html), 
[`rmarkdown`](https://cran.r-project.org/web/packages/rmarkdown/index.html), 
[`knitr`](https://cran.r-project.org/web/packages/knitr/index.html) y 
[`dplyr`](https://cran.r-project.org/web/packages/dplyr/index.html).

Por ejemplo, ejecutando el siguiente comando:

```{r eval=FALSE}
pkgs <- c("lattice", "ggplot2", "foreign", "car", "leaps", "MASS", "RcmdrMisc", 
          "lmtest", "glmnet", "mgcv", "rmarkdown", "knitr", "dplyr",
          "caret", "rattle", "car", "AppliedPredictiveModeling", "ISLR")

install.packages(setdiff(pkgs, installed.packages()[,"Package"]), dependencies = TRUE)
```

___

<p align="center"><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-sa.eu.svg"/></a></p>Esta obra está autorizada bajo la <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.