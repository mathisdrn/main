---
layout: project
title: Material Informatics&#58; Grain Growth
categories: projects
permalink: projects/material-informatics-grain-growth
---

<div class="message">
<strong>Note:</strong> This project is still under development during Summer 2016.
</div>

[Material Informatics][mi] is an emerging field that applies data science techniques to material science in order to better understand the discovery and development of advanced materials. This is accomplished by building process-structure-property relationships: data-driven models that can predict new material properties much faster than standard simulations. 

This project for **CSE 8803 Material Informatics** aims to build structure-property linkages for grain boundary pinning during grain growth.

<!--more-->

<figure>
  <img class="full" src="/images/projects/grain-growth/grain-growth.gif" alt="An example grain growth simulation.">
  <figcaption>An example grain growth simulation.</figcaption>
</figure>

Grain boundary pinning is a phenomenon in which insoluble particles are added to a microstructure. These particles affect the final grain size of a microstructure when subjected to a process (e.g. heating). In industry it's common to "pin" a material in order to control its final grain size distribution. 

Grain growth is possible to simulate, but often times the simulations are computationally expensive. My group is developing a data-driven, surrogate model to avoid these long simulations such that given a new set of input pin distribution parameters, we are able to predict the final microstructure after grain growth has occurred.

We do this by running initial simulations to train our model on, perform analyses such as spatial statistic computations and dimensionality reduction, and ultimately build a regression model.

<figure>
  <img class="lhalf" src="/images/projects/grain-growth/pca-in.gif" alt="An example grain growth simulation.">
    <img class="rhalf" src="/images/projects/grain-growth/pca-out.gif" alt="An example grain growth simulation.">
  <figcaption>Low dimensional representation of the inputs and outputs of our model.</figcaption>
</figure>

Results so far looking promising, but we are still putting the final touches on the project report!

This project was started in [CSE 8803 / ME 8883 Material Informatics][mic] class taught in Fall 2015 at Georgia Tech and has since become a standalone research project. [The project blog can be found here.][grain-growth] 

Final results are expected to be reported by the end of the Summer 2016 semester.

***

## Project Members
* [David Montes de Oca Zapiain][davidm]
* [David Brough][davidb]
* [Evdokia Popova][eva]

## Links
* [Grain Growth Project Blog][grain-growth]
* [Georgia Tech Materials Informatics Class Fall 2015][mic]
* [Material Informatics][mi]

[davidm]: http://mined.gatech.edu/members/David-MontesdeOca-Zapiain/ "David Montes de Oca Zapiain."
[eva]: http://mined.gatech.edu/members/Eva/ "Evdokia Popova."
[davidb]: http://davidbrough.net "David Brough."
[grain-growth]: http://materials-informatics-class-fall2015.github.io/MIC-grain-growth/ "Grain Growth Blog."
[mi]: https://en.wikipedia.org/wiki/Materials_informatics "Material Informatics."
[mic]: http://materials-informatics-class-fall2015.github.io "Materials Informatics Class Fall 2015."