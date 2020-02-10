---
layout: post
title: Subdivision Data
description: Data on the subdivision of buildings
img: /img/numbers.png
---

Data on the subdivision of buildings is scarce. Building subdivision - including the horizontal stratification of property by floor - is highly volumetric, making the creation of data a challenge for urban planners and designers.

A solution to this problem is to record subdivision by floor using a simple and intuitive set of numbers. Each number from left to right represents the ordering of the floors. The encoding of the numbers can illustrate whether subdivision has occurred on a floor or the number of homes added or subtracted as a result of subdivision. 

Binary vectors illustrate whether subdivision has occurred on a floor (Figure 1). Non-binary vectors can be used to show how many homes have been added or subtracted by floor as a result of building subdivision (Figure 2). 

This technique could be used by planners and designers to provide a better picture of building subdivision and housing density in cities.

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/numbers_subdivision.png" alt="" title=""/>
</div>

<div class="col three caption">
	Figure 1. Each digit is encoded with a zero or a one. A zero encoding means that no subdivision has taken place on that floor (I). A one indicates that the floor has been subdivided (II). Here, subdivision has occurred on the third and sixth floors.
</div>

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/numbers_homes_subdivision.png" alt="" title=""/>
</div>

<div class="col three caption">
	Figure 2. Each digit is encoded with the number of homes added or subtracted by floor due to subdivision. This diagram illustrates that zero homes have been added on the first floor (I) and eight homes have been added on the top floor through airspace development, for instance (II).
</div>