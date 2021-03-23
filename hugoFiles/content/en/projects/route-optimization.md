---
date: 2020-12-17T12:00:00-04:00
description: "A two-stage metaheuristic algorithm for finding efficient routes for a fleet of vehicles"
featured_image: "/images/SA_plot.png"
tags: []
title: "Vehicle routing and collection optimization"
---
## Computer Science Engineering thesis.

Design and development of metaheuristic technique that allows finding solutions to the Milk Collection Problem with Selection and Blending.

## Vehicle Routing Problem

The Vehicle Routing Problem is a combinational optimization and integer programming problem wich asks "What is the optimal set of routes for a fleet of vehicles to traverse in order to deliver to a given set of customers?".

{{< figure src="/images/SA_plot.png">}}

In my Computer Science engineering thesis I designed and tested a two-stage metaheuristic technique, that finds efficient routes for large routing instances.
I worked with a real world problem called Milk Collection Problem with Selection and Blending (MCPSB), which is a problem related to the well-known Vehicle Routing Problem. In the MCPSB it is required to find a set of routes for a fleet of trucks, in order to collect and blend different qualities of milk, from farms located in a wide geographical area.

The goal is to minimize the cost of transportation and maximize the profit obtained from the milk collection process.

I designed and tested a metaheuristic technique wich uses Simulated Annealing and Hill Climbing algorithms to find efficient routes in less than 50 seconds of computing time for the largests instances available.

{{< figure src="/images/SAHC.png">}}

The largest instance tested is made up of 500 possible farms to visit, 35 trucks and 3 different milk qualities. 

{{< figure src="/images/500.png">}}

{{< figure src="/images/SA2.png" >}}

{{< figure src="/images/time.png" >}}

## Real world applications

The technique can be used to carry out many types of route planning in real time, in different real world problems such as: 
* Collection of goods of different quality.
* Collection of hazardous materials
* Delivery of different types of goods.
* Planning visits for a group of workers.