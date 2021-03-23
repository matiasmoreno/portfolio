---
date: 2020-12-17T12:00:00-04:00
description: "A platform that detects empty areas on shelves and track people inside shops"
featured_image: "/images/seg3.png"
tags: []
title: "Artificial Inventory"
---

Project presented in "Feria de Software USM 2020". We developed a system that uses deep neural networks to identify empty spaces in shelves of a pet supply store. Also we detect the people in the store in real time.

* Collected and labeled more than 5000 different examples of empty areas on shelves.
* Trained and tuned a image segmentation model using transfer learning and convolutional neural networks.
* Tested and evaluate model. Recall score: 78.8%.
* Creation of heatmap and historic plot of empty areas in shelves.
* Used Yolo model to detect people, Recall score: 74.2%.
* Creation of heatmaps to identify most visited aisles.
* Use of direct feed from security cameras.

{{< figure src="/images/segmentation_hd.png">}}

{{< figure src="/images/people_hd.png" >}}

{{< figure src="/images/heatmap_hd.png">}}

{{< figure src="/images/AI_plat_plot.png">}}

{{< figure src="/images/plat2.png" >}}
