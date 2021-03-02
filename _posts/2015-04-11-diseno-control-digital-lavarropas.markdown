---
layout: post
title: Diseño de control digital para lavarropas automático
date: 2015-04-11 09:00:00 -0300
description: Implementación de sistema de control digital para un lavarropas automático # Add post description (optional)
img: lavarropas/lavarropas-main.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [VHD, FPGA, sistemas embebidos, electrónica, digital]
---

> Implementación de sistema de control digital para un lavarropas automático

---

## Video de la simulación

<iframe width="400" height="275" src="https://www.youtube.com/embed/94JvlFr-tns" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Breve descripción

Se ha realizado el diseño esquemático digital de un micro-controlador para el funcionamiento un lavarropas automático que ejecuta los distintos procesos en un lavado (lavado,enjuague y centrifugado) en base lo seleccionado por un usuario. Posteriormente, a modo de testing, se ha cargado dicho controlador a una plaqueta FPGA Basys2 para simular las instrucciones de lavado.

El diseño se realizó describiendo la lógica del comportamiento a través de:

- lenguaje de descripción de hardware (VHD)
- mediante diagramas esquemáticos.

El primer paso consistió en entender el problema y subdividirlo en sub-módulos lógicos siguiendo la perspectiva Top-Down, que pueda adaptarse a cualquier hardware que se emplee a futuro. Cada sub-módulo describe una necesidad en particular e implementa un programa lógico de comportamiento para satisfacerlo, utilizando el lenguaje VHD. Este enfoque de divide y vencerás -Divide & conquer- favorece la productividad del desarrollo, reutilización de diseños y detectar los errores con mayor rapidez. Sin embargo, posee como desventaja la dificultad en comprender la arquitectura de componentes lógicos, el flujo de datos y sus relaciones.

Para solventar esto, se ha elaborado el diagrama esquemático que permite entender la arquitectura de componentes escenciales y el flujo de comunicacion entre ellos, que permite comprender desde un panorama global, las ecuaciones combinacionales y secuenciales.

Los resultados obtenidos en la simulación se muestran en el video, evidenciando el buen comportamiento del sistema de control diseñado obtenido a partir del diagrama esquemático.

---

## Informe de Implementación

A continuación, se adjunta el informe que detalla la resolución del diseño en PDF

- [ver informe de Implementación PDF](https://github.com/guobiloo/Control-Digital-Lavarropas/blob/master/informe%20-%20control%20digital%20de%20lavarropas.pdf)

<embed src="{{site.baseurl}}/assets/docs/lavarropas/informe.pdf#toolbar=0&navpanes=0&scrollbar=0" type="application/pdf" width="100%" height="600px" />

---

## Autores

- Joaquin Gonzalez Budiño
- Nicolas Giuliano

---

## Ver este proyecto de GitHub

<https://github.com/joagzb/Control-Digital-Lavarropas>
