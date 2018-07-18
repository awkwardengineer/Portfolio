---
title: NextBus Sign
template: article.jade
image: splash.jpg
tags: Personal Skill Builder
date: 2016
---
The NextBus sign was a personal project and a skill builder. It connects to the NextBus API which publishes a data feed for the bus arrival times on the MBTA and other transit systems.  

I developed this project for personal use, but was constantly thinking about what a commercialization effort would entail. The key obstacle was fitting a business model to the cost of maintaining an API, even though the hardware lends itself to a one time sale.

On the technical / design end, I developed the graphics and industrial design, mechanical housing, and custom circuit boards.

The sign uses a cloud connected Particle as the main microcontroller. To shorten development time, the NextBus API is processed off the microcontroller in Python and a short string is sent to the device itself through Particle's cloud back end. The Python script runs on an AWS instance in Amazon's cloud.

![](splash.jpg)  
![](01.jpg)  
![](02.jpg)  
![](03.jpg)  
![](04.jpg)  
![](05.jpg)  
![](06.jpg)  
![](07.jpg)  
