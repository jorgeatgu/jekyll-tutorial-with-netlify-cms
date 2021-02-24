---
layout: post
title: Cómo construir una pirámide de población con Populate Data y D3
date: 2021-02-24T09:04:45.509Z
intro: "En este tutorial vamos a describir cómo utilizar [Populate
  Data](https://populate.tools/data) para obtener los datos necesarios para
  constuir una pirámide de población con HTML y [D3.js](https://d3js.org/) como
  esta:"
img: /assets/posts/bbva-opem4u-fernando-blat.jpg
---
Populate Data es un servicio ofrecido por [Populate](https://populate.tools) que agrupa multitud de fuentes de datos públicos y privados y que permite consumirlos de forma unificada a través de una API.

## Buscar datos en Populate Data

Para esta visualización en concreto necesitamos los datos del [INE del padrón contínuo](https://ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736177012&menu=resultados&secc=1254736195461&idp=1254734710990) de población municipal por edad y sexo. Utilizaremos el explorador de datos para encontrar un dataset con esta información: