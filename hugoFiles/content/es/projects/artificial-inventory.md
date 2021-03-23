---
date: 2021-01-12T12:00:00-04:00
description: "Un sistema que detecta espacios vacías en las gondolas y detecta a las personas dentro de las tiendas"
featured_image: "/images/seg3.png"
tags: []
title: "Artificial Inventory"
---
## Proyecto presentado en la "Feria de Software USM 2020". 
Desarrollamos un sistema que utiliza la salida directa de cámaras de seguridad, para procesar imágenes e identificar espacios vacíos y personas en las gondolas de una tienda de artículos para mascotas, utilizando redes neuronales convolucionales en tiempo real.

## Segmentación de imágenes

Usamos la segmentación de imágenes para detectar espacios vacíos en las gondolas de la tienda, también usamos la posición de los espacios para identificar cada producto.

{{< figure src="/images/seg_close.png">}}
{{< figure src="/images/products.png">}}
{{< figure src="/images/AI_plat_plot.png">}}

### Algunas de mis tareas realizadas incluyeron:
* Product owner y data scientist del equipo.
* Recopilar y discutir los requisitos funcionales por parte del cliente.
* Recolectar y etiquetar más de 5000 ejemplos diferentes de áreas vacías en los estantes.
* Entrenar y afinar un modelo de segmentación de imágenes usando transferencia de aprendizaje y redes neuronales convolucionales.
* Modelo probado y evaluado. Puntuación de Recall: 78,8%.

## Detección de personas

Usamos la clasificación de objetos en imágenes con redes neuronales convolucionales (YOLO) para detectar personas dentro del local comercial.

{{<figure src = "/images/people_hd.png">}}
{{<figure src = "/images/heatmap_hd.png">}}

### Algunas de mis tareas realizadas incluyeron:
* Uso de modelo Yolo para detectar personas en tiempo real, puntuación de Recall: 74,2%.
* Medición de distancia entre personas dentro de la tienda.
* Creación de un mapa de calor con los datos recopilados y presentación de flujo histórico de clientes.

El sistema permite tener un registro histórico y en tiempo real de los productos existentes en las góndolas de las tiendas.
Permite tomar decisiones sobre el posicionamiento de productos según el flujo de personas y la frecuencia de movimiento de los productos.
