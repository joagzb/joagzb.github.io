---
layout: post
title: Melano-Malo
date: 2019-06-02 09:00:00 -0300
description: Desarrollo de un algoritmo inteligente basado en procesamiento digital de señales para el análisis y detección de melanomas malignos. # Add post description (optional)
img: Melano-malo/Melano-malo-main.jpg # Add image post (optional)
fig-caption: detecting an evil melanoma # Add figcaption (optional)
tags: [IA, image processing, python]
---

> Desarrollo de un algoritmo inteligente basado en procesamiento digital de señales para el análisis y detección de melanomas malignos.

---

## Problema y contexto

Un melanoma maligno tiene la contrapartida de que, si es pronosticado como tal de forma tardía, será muy complicado su tratamiento y puede producir efectos negativos en la salud de una persona.

Ante cualquier caso de duda, es importante hacer un seguimiento del estado del melanoma, aún cuando no se presentan caracteristicas malignas. En el caso de detectar el lunar como maligno, también es importante realizar su seguimiento para evitar evoluciones, ya que el especialista de la salud no tiene posibilidad de revisar al paciente, sino hasta la siguiente visita.

Sucede que la mayoría de los pacientes concurren a un dermatólogo en etapas intermedias o avanzadas de un lunar, es decir, cuando los melanomas ya evidencian algunas características malignas como son el tamaño, color (oscuros y rojizos) y sintomas de sangrado.

---

## Objetivo

Este trabajo tuvo el objetivo de desarrollar un método que permita a una persona analizar el estado de un melanoma y acudir a un médico en caso de síntomas sospechosos, o bien, que sirva de apoyo al profesional en la salud para hacer un seguimiento de la lesión.

---

## Técnicas utilizadas

- clasificación por color y variaciones de su histograma
- clasificación por análisis bordes y varianza de Hue (del modelo de color en HSV).

---

## Implementación del algoritmo y resultados técnicos

Con las medidas de desempeño calculadas se determinó que el porcentaje medio de aciertos del primer método fue del 75%, mientras que para el segundo fue del 81%.

En el siguiente link se puede acceder al informe que presenta los detalles técnicos de la implementación

[Informe Paper](https://github.com/guobiloo/Melano-malo/blob/master/Informe_TPfinalPDI_Gonzalez_Kalafatic.pdf)

<embed src="{{site.baseurl}}/assets/docs/melano-malo/informe.pdf#toolbar=0&navpanes=0&scrollbar=0" type="application/pdf" width="100%" height="600px" />

---

## Lenguajes y librerías consideradas

- python 3.7.4
- OpenCV (librería)
- MedPy (librería)

---

## Autores

- [Emiliano Kalafatic](https://www.linkedin.com/in/emiliano-kalafatic/)
- [Joaquin Gonzalez Budiño](https://www.linkedin.com/in/joaquin-gonzalez-budino/)

---

## Ver este proyecto en GitHub

- <https://github.com/joagzb/Melano-malo>
