---
title       : 'Estadística descriptiva'
subtitle    : 'Diseño de Experimentos'
author      : 'Carlos Neftaly Lozano A.'
job         : 'Microbiólogo Industrial y Ambiental, Msc'
logo     : EM.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap]            # {, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
license: by-nc-sa
---

## Definición

<q>
La estadística es el estudio de la colección, análisis, interpretación, presentación y organizacón de los datos.
</q>

--- 

## Estadística 

<img src="./figure/Data.jpg" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

---

## Fuente de datos en Microbiología..

<img src="./figure/Escala.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

---

## Datos 
<span style="display:block; height: 2cm;"></span>

En estadística, 'los datos' se conceptualizan como un conjunto de  <span style="color:#FF4000">objetos</span> sobre los cuales medimos u observamos una o más <span style="color:#DF0101">características </span>. 


<img src="./figure/data2.jpg" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" style="display: block; margin: auto;" />

--- 

## Variable

<span style="display:block; height: 2cm;"></span>

<q> Una característica o atributo que puede  <span style="color:#FF4000">variar</span>  de un individuo a otro. </q>

---

## Variable
<span style="display:block; height: 2cm;"></span>
<style>
  <slide class="{{ slide.class }}" id="{{ slide.id }}">
    <hgroup>
    {{{ slide.header }}}
  </hgroup>
    <article>
    <hr noshade size=4 color='red'>  
    {{{ slide.content }}}  
    <div class='left' style='float:left;width:48%'>
    {{{ slide.left.html }}}
    </div>    
      <div class='right' style='float:right;width:48%'>
      {{{ slide.right.html }}}
      </div>
        </article>
        </slide>
</style>
        
        
*** {name: left}

- <span style="color:orange">Inviduo </span>
- Observación
- sujeto
- objeto
- caso
- **Unidad experimental**

*** {name: right}
- <span style="color:orange">Variables </span>
- Característica
- Atributo
- Rasgo

--- 

## Variables 

<q>  Las <span style="color:red"> variables</span> juegan un papel protagónico en la estadística y diseño de experimentos </q>

--- 

## Variables 

<img src="./figure/flujo.jpg" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" style="display: block; margin: auto;" />

--- 

## Variables 

<img src="./figure/Var.jpg" title="plot of chunk unnamed-chunk-5" alt="plot of chunk unnamed-chunk-5" style="display: block; margin: auto;" />

---

## Variables

<q> Nuestro turno: ejemplo de variables típicas en microbiología.....</q>

--- 

## Variables 

<q>¿Cómo convertiríamos una variable _cuantitativa_ en una _cualitativa_ o viceversa? </q>

---


## Caso 1: Unas cuantas manzanas.... 

<span style="display:block; height: 2cm;"></span>

<img src="./figure/1.png" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" style="display: block; margin: auto;" />

--- 

## Caso 1: Unas cuantas manzanas.... 



<img src="./figure/2.png" title="plot of chunk unnamed-chunk-7" alt="plot of chunk unnamed-chunk-7" style="display: block; margin: auto;" />

--- 


## Caso 2: Más manzanas.... 



<img src="./figure/3.png" title="plot of chunk unnamed-chunk-8" alt="plot of chunk unnamed-chunk-8" style="display: block; margin: auto;" />

--- 


## Caso 2: Más manzanas.... 



<img src="./figure/4.png" title="plot of chunk unnamed-chunk-9" alt="plot of chunk unnamed-chunk-9" style="display: block; margin: auto;" />

--- 

## Caso 3: Muchas más manzanas.... 



<img src="./figure/5.png" title="plot of chunk unnamed-chunk-10" alt="plot of chunk unnamed-chunk-10" style="display: block; margin: auto;" />

--- 

## Caso 3: Muchas más manzanas.... 


<img src="./figure/6.png" title="plot of chunk unnamed-chunk-11" alt="plot of chunk unnamed-chunk-11" style="display: block; margin: auto;" />

--- 


## Resumiendo variables...

<span style="display:block; height: 2cm;"></span>

>1. Tablas de frecuencia

>2. Gráficos

>3. Resumenes numéricos 

--- 

## Resumiendo variables: Tablas de frecuencia

<img src="./figure/fre.png" title="plot of chunk unnamed-chunk-12" alt="plot of chunk unnamed-chunk-12" style="display: block; margin: auto;" />

---

## Resumiendo variables: Tablas de frecuencia

| Acidity | Conteo |
|:-------:|:------:|
|Low      |        |
|Medium     |        |
|High         |        |

---


## Resumiendo variables

<span style="display:block; height: 2cm;"></span>

<img src="./figure/flujoMed.jpg" title="plot of chunk unnamed-chunk-13" alt="plot of chunk unnamed-chunk-13" style="display: block; margin: auto;" />

---

## Medidas de tendencia central 

<span style="display:block; height: 2cm;"></span>

- Media: Promedio

- Mediana: Punto medio o central 

- Moda: Más común o frecuente

--- 

## Media 

$$\bar x = \frac{1}{n}\sum_{i = 1}^{n} x_i$$



<img src="./figure/media.png" title="plot of chunk unnamed-chunk-14" alt="plot of chunk unnamed-chunk-14" style="display: block; margin: auto;" />

---

## Mediana

Es el punto medio o central de una distribución ordenada de valores. 


<img src="./figure/mediana.png" title="plot of chunk unnamed-chunk-15" alt="plot of chunk unnamed-chunk-15" style="display: block; margin: auto;" />

<img src="./figure/mediana2.png" title="plot of chunk unnamed-chunk-16" alt="plot of chunk unnamed-chunk-16" style="display: block; margin: auto;" />

---


## Variables categóricas: Representación gráfica
### Gráfico de tortas
![plot of chunk unnamed-chunk-17](figure/unnamed-chunk-17-1.png)

---

## Variables categóricas: Representación gráfica
### Gráfico de barras
![plot of chunk unnamed-chunk-18](figure/unnamed-chunk-18-1.png)

---
