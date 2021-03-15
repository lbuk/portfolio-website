---
layout: post
title: Social Distancing, Fresnel and the Modifiable Areal Unit Problem
description: A method of comparing social distancing rules using Fresnel's circles
img: /img/social_distancing_fresnel.png
---

Coronavirus is having an unprecedented effect on population health and society. A variety of measures have been implementented to tackle COVID-19. Although social distancing is by no means a substitute for wearing a face mask or getting vaccinated, it is an important way of reducing the spread of the virus. In summary, the further away you are from other people, the less likely you are to get COVID-19. 

Social distancing measures <a href="https://www.bbc.co.uk/news/science-environment-52522460">differ from place to place</a>. While the UK recommends people maintain a distance of at least 2 metres, several countries - including France, China, Hong Kong, Denmark, Singapore and Lithuania - recommend a minimum distance of only 1 metre. In addition, other countries suggest a minimum distance of 1.4m (South Korea), 1.5m (Belgium, Australia, Italy, Spain, Greece, Netherlands, Germany, Portugal) or 1.8m (US). 

Comparing different social distancing rules and the spread of disease across different spatial scales are compounded by the Modifiable Areal Unit Problem (MAUP). The MAUP occurs when data is aggregated to the level of spaces or districts that may be unequal in terms of area.

Drawing on Fresnel's circles and the <a href="https://www.liamthomasbolton.com/portfolio/FresnelMap/">Fresnel Map</a>, the effectiveness of the various social distancing rules can be compared. According to Fresnel's circles, each 'doughnut' has the same area as the central circle. In this particular example, the radius of the central circle is 1m and the successive zones have radii of 1.41m, 1.73m, 2m, 2.24m, and 2.45m. Alternatively, the zones can be altered by varying the radius of the central circle.

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/pandemic_social_distancing_fresnel_circles_figure_1.png" alt="" title=""/>
</div>

<div class="col three caption">
	Fresnel's circles. The radius of the central circle (i.e. Zone 1) is 1m.
</div>

<br>

By computing multiple scenarios, a hypothetical person with COVID-19 can be placed in the centre and the number of people that get the virus in each equally-sized zone can be counted. The zones can then be thematically mapped using the <a href="https://www.liamthomasbolton.com/portfolio/FresnelMap/">Fresnel Map</a>, a novel cartographic technique.

This technique has a number of applications in the domain of epidemiology. It could be utilised to study the spread of airborne diseases and address the MAUP in epidemiology. Using the Fresnel Map, the spread of disease could additionally be mapped around an infrastructural node. The technique has applications beyond coronavirus and social distancing and could be utilised to optimise future measures.
