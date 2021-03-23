---
date: 2020-12-17T12:00:00-04:00
description: "In algoritmo metaheurístico de dos etapas para encontrar rutas eficientes para una flota de vehículos"
featured_image: "/images/SA_plot.png"
tags: []
title: "Optimización de recolección y ruteo de vehículos"
---
## Memoria de Ingeniería en Ciencias de la Computación.

Diseño y desarrollo de técnica metaheurística que permite encontrar soluciones al Problema de Recolección de Leche con Selección y Mezcla.

## Problema de generación de rutas para vehículos

El problema de generación de rutas para vehículos un problema de optimización combinatoria y programación enetera que busca resolver la siguiente pregunta "¿Cuál es el conjunto óptimo de rutas que debe atravesar una flota de vehículos para entregar bienes a un conjunto dado de clientes?".

{{< figure src="/images/SA_plot.png">}}

En mi memoria de Ingeniería Civil Informática diseñé y probé una técnica metaheurística de dos etapas, que permite encontrar rutas eficientes para grandes instancias de enrutamiento.
Trabajé con un problema del mundo real llamado Problema de recolección de leche con selección y mezcla (MCPSB), el cual es un problema relacionado con el conocido Problema de enrutamiento de vehículos. En el MCPSB se requiere encontrar un conjunto de rutas para una flota de camiones, con el fin de recolectar y meclar distintas calidades de leche, desde granjas ubicadas en una amplia zona geográfica.

El objetivo de la técnica es minimizar el costo de transporte y maximizar la ganancia obtenida en el proceso de recolección de leche.

Diseñé y probé una técnica metaheurística que utiliza algoritmos como Simutaled Annealing y Hill Climbing para encontrar rutas eficientes en menos de 50 segundos de tiempo de cómputo para las instancias más grandes disponibles.

{{< figure src="/images/SAHC.png">}}

La instancia más grande probada está compuesta por 500 granjas posibles para visitar, 35 camiones y 3 calidades de leche diferentes.

{{< figure src="/images/500.png">}}

{{< figure src="/images/SA2.png" >}}

{{< figure src="/images/time.png" >}}

## Aplicaciones del mundo real

La técnica se puede utilizar para realizar muchos tipos de planificación de rutas en tiempo real, en diferentes problemas de enrutamiento como:
* Recolección de mercancías de diferentes tipos o calidades.
* Recolección de materiales peligrosos.
* Entrega de diferentes tipos de bienes.
* Planificación de visitas para grupos de trabajadores.