---
layout: post
title: "Hormigas-urbanas"
date: 2018-11-20 09:00:00 -0300
description: "Desarrollo de un algoritmo inteligente para encontrar el camino mas conveniente entre dos puntos de la ciudad, utilizando colectivos públicos" # Add post description (optional)
img: hormigas/hormigas-main.jpg # Add image post (optional)
fig-caption: "an ant waiting for a bus" # Add figcaption (optional)
tags: [IA, matlab, python]
---

> Desarrollo de un algoritmo inteligente para encontrar el camino mas conveniente entre dos puntos de la ciudad, utilizando colectivos públicos.

---

## Problema y contexto

Las personas que visitan ciudades que no conocen mucho, estudian como utilizar medios de transporte públicos poder ir a un determinado sitio. Para ellas, es deseable que cuenten con un servicio que no sólo muestre los distintos puntos atractivos, sino que también indique cómo llegar al destino deseado utilizando medios de transporte públicos.

Para estos casos, existen soluciones de software tales como google maps, que permite consultar cómo llegar desde un punto a otro, considerando el tiempo y la distancia como el costo asociado para ofrecer los mejores resultados. Estos algoritmos hacen uso de técnicas de búsquedas tradicionales, como costo uniforme, cuyo resultado es el mejor a considerar.

La desventaja surge si se considera el translado de un punto a otro, no solo tomando en cuenta el tiempo de demora estimada en el translado, sino también la opción de utilizar transportes públicos y el coste en dinero que esto supone. Por otro lado, en ciudades grandes, no solo se debe tener un buen sistema de respaldo de datos para almacenar todas las calles y puntos de interes, sino también un buen sistema con la capacidad suficiente para procesar y calcular las rutas óptimas ya que el algoritmo de costo uniforme hace un consumo masivo de recursos de memoria.

---

## Objetivo

El objetivo de este trabajo fué la búsqueda de estrategias alternativas que permitan encontrar alguno de los mejores trayectos entre un punto y otro de una ciudad, que minimice el tiempo de translado y de dinero  con posibilidad de utilizar el colectivo urbano como transporte público, sin requerir muchos recursos de hardware.

---

## Metodología

Se propuso aquí el uso de métodos de Inteligencia Colectiva, desde un enfoque de inteligencia Computacional, inspirados en el comportamiento biológico de las hormigas (que poseen un costo espacial acotado -cantidad de hormigas-).

---

## Idea de solución

A modo de prototipado, se ha decidido encontrar una solución que permita a una persona conocer cuál es un buen camino a seguir, que le permita ahorrar tiempo (~distancia) y dinero, considerando dos medios de traslado: a pie y mediante colectivos públicos urbanos.
Además, nos hemos propuesto el objetivo de comparar las distintas variaciones del algoritmo de colonia de hormigas y así poder seleccionar la alternativa mas adecuada.

---

## Técnicas utilizadas

- Inteligencia Artificial

  - Inteligencia Computacional

    - Método de búsqueda de caminos óptimos
    - Inteligencia Colectiva Metaheuristico

      - Algoritmos de Colonia de hormigas

---

## Implementación del algoritmo y resultados técnicos

Los detalles técnicos acerca de la implementación y los resultados obtenidos quedan expresados en el siguiente informe:

[ver informe paper](https://github.com/guobiloo/hormigas-urbanas/blob/master/hormigas%20urbanas%20-%202018.pdf)

<embed src="{{site.baseurl}}/assets/docs/hormigas-urbanas/informe.pdf#toolbar=0&navpanes=0&scrollbar=0" type="application/pdf" width="100%" height="600px" />

---

## Lenguajes y librerías consideradas

- python 2.7
- Matlab
- OpenStreetMaps

---

## Autores

- Joaquin Gonzalez Budiño
- Nicolas Giuliano

---

## Ver este proyecto en GitHub

- <https://github.com/joagzb/hormigas-urbanas>
