---
layout: post
title: NiceTV - aplicación web para cobradores e instaladores del servicio
date: 2020-10-13 08:00:00 -0300
description: Plataforma para la gestión de cobranzas e instalaciones de los servicios afines a NiceTV # Add post description (optional)
img: NiceTV/plataforma_cobradores.jpg # Add image post (optional)
tags: [web,html,css,javascript,responsive,frontend,backend, fullstack, laravel, php] # add tag
---

> web app made for NiceTV Digital Television service. It allow Shops to be enable to recieve payments for common NiceTV services, earning money commisions for each done payment.

---

## Languages, tools and frameworks

- HTML
- CSS
- Javascript
- UIkit (framework de CSS)
- Laravel (framework de PHP)
- MySQL
- Redis

---

## Proyect experience

Debido a que la empresa se encuentra en una etapa de crecimiento, han decidido contratarme nuevamente para desarrollar una plataforma web que permita gestionar de manera más organizada tanto las tareas de instalacion del servicio y su personal a cargo, como también para crear nuevas bocas de pagos para los servicios que ofrecen.

Al mismo tiempo, esto les permitiría mejorar sus métricas de negocio para la toma de decisiones tanto comerciales y logísticas.

Antes de diseñar el sistema y empezar a desarrollarlo, he asistido a varias reuniones como etapa inicial de recolección de requisitos, a los fines de conocer más a fondo las espectativas de los usuario(Stakeholders) implicados.

Una vez formado el primer documento de requisitos y haber elaborado un diagrama de casos de uso con el mismo, inicié la etapa de diseño del sistema y elaboré 3 diagramas.
- un diagrama esquemático de la base de datos,
- un diagrama de clases UML para representar el modelo de datos
- un documento con las rutas, peticiones y consumo de APIS del servidor

La arquitectura de software considerada para el presente desarrollo es el patrón MVC (modelo-vista-controlador)

Estos documentos son importantes ya que ayudan en la etapa de testing, mantenimiento o futuro crecimiento de la aplicación. Pueden ser consultados por cualquier desarrollador para la comprensión del proyecto a futuro.

Luego, he iniciado el desarrollo del sistema y haciendo uso del documento de casos de uso, pude organizar las funcionalidades del sistema en incrementos para seguir una metodología incremental. Así podía testear y probar cada parte de la aplicación a medida que iba desarrollado. De esta forma, si se detectaba un error, era fácil detectar la fuente del problema y corregirlo rápido.

Finalmente, he realizado la integración del sistema. Corrí la aplicación con distintos casos de prueba extraídos nuevamente del documento de requisitos y diagrama de casos de uso. Mientras hacía eso, tomé capturas de video para armar videotutoriales a modo de ayuda para los usuarios finales. Por último, presenté el sistema funcionando correctamente y se subió al servidor de la empresa.

Durante todo este proceso, he trabajado junto al administrador de servidores, otro administrador de base de datos de la empresa, un contador y distintos usuarios finales tales como instaladores y cobradores del servicio.

---

## Result

Aquí se muestran algunos videos que he realizado a pedido y a modo de tutorial para los usuarios finales, como he comentado en la sección anterior:

<iframe width="560" height="315" src="https://www.youtube.com/embed/VHR09GWZEdM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/AEkUpsX-q4I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Related proyects

Here there are some other proyects I have done for the same Company:

- [NiceTV website]({{site.baseurl}}/NiceTV-website/)
- [NiceTV Phone TV app]({{site.baseurl}}/NiceTV-streamingTV-app/)
- [NiceTV online payment Interface]({{site.baseurl}}/NiceTV-web-payment-interface/)
