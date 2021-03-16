---
layout: post
title: The Spread of Disease, Fresnel and the Modifiable Areal Unit Problem
description: Comparing the spread of disease using Fresnel's circles
img: /img/fresnel_epidemiology.png
---

Comparing the spread of disease across different spatial scales is compounded by the Modifiable Areal Unit Problem (MAUP). The MAUP occurs when data is aggregated to the level of areas that may be unequal in terms of area. For example, the transmission of COVID-19 will differ based on spatial scale and this is reflected in the MAUP.

Drawing on Fresnel's circles, the spread of disease across different scales can be compared. According to Fresnel's circles, each zone has the same area as the central circle. In this illustrative example, the radius of the central circle is 1m and the successive zones have radii of 1.41m, 1.73m, 2m, 2.24m, and 2.45m. Alternatively, the zones can be altered by varying the radius of the central circle.

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/fresnel_circles_spread_of_disease.png" alt="" title=""/>
</div>

<div class="col three caption">
	Fresnel's circles
</div>

<br>

By computing multiple scenarios, a hypothetical person with a virus such as COVID-19 can be placed in the centre and the number of people that get the virus in each equally-sized zone can be counted, surmounting the MAUP. The counts across the zones can then be thematically mapped using the <a href="https://www.liamthomasbolton.com/portfolio/FresnelMap/">Fresnel Map</a>, a novel cartographic technique.

This technique has a number of applications in the domain of epidemiology. It could be utilised to study the spread of airborne diseases and address the MAUP in disease mapping. Using the Fresnel Map, the spread of disease could additionally be mapped around an infrastructural node.
