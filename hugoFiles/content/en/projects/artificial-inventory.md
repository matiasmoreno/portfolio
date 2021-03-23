---
date: 2021-01-12T12:00:00-04:00
description: "A system that detects empty areas on shelves and track people inside shops"
featured_image: "/images/seg3.png"
tags: []
title: "Artificial Inventory"
---
## Project presented in "Feria de Software USM 2020". 
We developed a system that uses the direct feed from security cameras, to process the images and identify empty spaces and people in shelves of a pet supply store, using convolutional neural networks in real time.

## Image segmentation

We used image segmentation to detect empty areas in the store, also we used the position to identify the product.

{{< figure src="/images/seg_close.png">}}
{{< figure src="/images/products.png">}}
{{< figure src="/images/AI_plat_plot.png">}}

### Some of my performed tasks included:
* Product owner and data scientist of the team.
* Collect and discuss functional requirements from the client.
* Collect and label more than 5000 different examples of empty areas on shelves.
* Train and tune a image segmentation model using transfer learning and convolutional neural networks.
* Test and evaluate model. Recall score: 78.8%.

## People detection

We used image object classification with convolutional neural networks (YOLO) to detect people store.

{{< figure src="/images/people_hd.png" >}}
{{< figure src="/images/heatmap_hd.png">}}

### Some of my performed tasks included:
* Use of Yolo model to detect people in real time, Recall score: 74.2%.
* Measurement distance between people inside the shop.
* Creation of heatmap with the collected data, and display historic plot of visitors.

The system allows to have a real-time and historical record and of the existing products in the store shelves.
It allows making decisions about the positioning of products according to the flow of people and the frequency of movement of the products.