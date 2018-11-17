--- 
title: "Variable Compleja"
subtitle: "Ciencia de los Datos Financieros"
author: "Synergy Vision"
date: "2018-11-17"
knit: "bookdown::render_book"
documentclass: krantz
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
colorlinks: yes
lot: yes
lof: yes
fontsize: 12pt
monofontoptions: "Scale=0.8"
keep_md: yes
site: bookdown::bookdown_site
description: ""
url: 'http\://synergy.vision/Variable-Compleja/'
github-repo: synergyvision/Variable-Compleja/
cover-image: images/cover.png
---

# Prefacio {-}

Placeholder


## ¿Por qué  leer este libro? {-}
## Estructura del libro {-}
## Información sobre los programas y convenciones {-}
## Agradecimientos {-}

<!--chapter:end:index.Rmd-->


# Acerca del Autor {-}

Este material es un esfuerzo de equipo en Synergy Vision, (<http://synergy.vision/nosotros/>).		 

El propósito de este material es ofrecer una experiencia de aprendizaje distinta y enfocada en el estudiante. El propósito es que realmente aprenda y practique con mucha intensidad. La idea es cambiar el modelo de clases magistrales y ofrecer una experiencia más centrada en el estudiante y menos centrado en el profesor. Para los temas más técnicos y avanzados es necesario trabajar de la mano con el estudiante y asistirlo en el proceso de aprendizaje con prácticas guiadas, material en línea e interactivo, videos, evaluación contínua de brechas y entendimiento, entre otros, para procurar el dominio de la materia.
  		  
Nuestro foco es la Ciencia de los Datos Financieros y para ello se desarrollará material sobre: **Probabilidad y Estadística Matemática en R**, **Programación Científica en R**, **Mercados**, **Inversiones y Trading**, **Datos y Modelos Financieros en R**, **Renta Fija**, **Inmunización de Carteras de Renta Fija**, **Teoría de Riesgo en R**, **Finanzas Cuantitativas**, **Ingeniería Financiera**, **Procesos Estocásticos en R**, **Series de Tiempo en R**, **Ciencia de los Datos**, **Ciencia de los Datos Financieros**, **Simulación en R**, **Desarrollo de Aplicaciones Interactivas en R**, **Minería de Datos**, **Aprendizaje Estadístico**, **Estadística Multivariante**, **Riesgo de Crédito**, **Riesgo de Liquidez**, **Riesgo de Mercado**, **Riesgo Operacional**, **Riesgo de Cambio**, **Análisis Técnico**, **Inversión Visual**, **Finanzas**, **Finanzas Corporativas**, **Valoración**, **Teoría de Portafolio**, entre otros.

Nuestra cuenta de Twitter es (https://twitter.com/bysynergyvision) y nuestros repositorios están en GitHub (https://github.com/synergyvision).
  		  
 **Somos Científicos de Datos Financieros**

<!--chapter:end:000-author.Rmd-->

\mainmatter

# Introducción 

## Plano Complejo

\BeginKnitrBlock{definition}<div class="definition"><span class="definition" id="def:unnamed-chunk-1"><strong>(\#def:unnamed-chunk-1) </strong></span>El plano complejo o cuerpo de un número complejo es el conjunto siguiente

\begin{equation}
\mathbb{C} =\{ (x,y) : x,y \in \mathbb R\}
\end{equation}

Con las operaciones

- Suma: $(x_1,y_1) + (x_2,y_2) = (x_1+x_2,y_1 +y_2)$.

- Producto escalar $\lambda (x,y) \ne (\lambda x,\lambda y)$

- Producto $(x_1,y_1) (x_2,y_2) = (x_1x_2 - y_1y_2,y_1 +y_2)$
  </div>\EndKnitrBlock{definition}





\BeginKnitrBlock{definition}<div class="definition"><span class="definition" id="def:defi-par-transformadas-fourier"><strong>(\#def:defi-par-transformadas-fourier) </strong></span>Para una función  general $\{a_t;t=0,\pm1,\pm2,\ldots\}$ que satisface la condición de sumabilidad absoluta

\begin{equation}
  \sum_{t=-\infty}^{\infty}|a_t|<\infty,
(\#eq:eq-cond-sumabilidad-absoluta)
\end{equation}

definimos el **par de transformadas de Fourier** de la forma

\begin{equation}\label{}
  A(\omega)=\sum_{t=-\infty}^{\infty}a_te^{-2\pi i\omega t}
(\#eq:eq-transformada-fourier-A)
\end{equation}

y

\begin{equation}\label{}
  a_t=\int_{-1/2}^{1/2}A(\omega)e^{2\pi i\omega t}d\omega
(\#eq:eq-transformada-fourier-a)
\end{equation}</div>\EndKnitrBlock{definition}

<!--chapter:end:010-introduction.Rmd-->

# Referencias {-}




<!--chapter:end:500-references.Rmd-->

