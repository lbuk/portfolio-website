---
layout: post
title: 3D Data on Building Subdivision
description: A technique for recording 3D data on building subdivision
img: /img/numbers.png
---

Data on the subdivision of buildings is scarce and lacking in detail. Building subdivision - including the horizontal stratification of property by floor - is highly volumetric, making the creation and mapping of this data a challenge for planners and designers.

A solution to this problem is to record three-dimensional (3D) subdivision by floor using a simple and intuitive set of numbers. Each number from left to right represents the ordering of the floors. The encoding of the numbers illustrates whether subdivision has occurred on a floor or alternatively the number of homes added or removed as a result of subdivision. The set of numbers can be added to urban datasets as part of variables.

Binary vectors illustrate whether subdivision has occurred on a floor (Figure 1). Non-binary vectors can be used to show how many homes have been added or subtracted on a floor as a result of subdivision (Figure 2). 

This new technique could be utilised by planners and designers to provide a better picture of building subdivision and housing density in cities. It is inspired by the work of Steadman, Martin and March.

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/numbers_subdivision.png" alt="" title=""/>
</div>

<div class="col three caption">
	Figure 1. Each digit is encoded with a zero or a one. A zero encoding means that no subdivision has taken place on that floor (I). A one indicates that the floor has been subdivided (II). Here, subdivision has occurred on the third and sixth floors and would be recorded as '001001' in a dataset.
</div>

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/numbers_homes_subdivision.png" alt="" title=""/>
</div>

<div class="col three caption">
	Figure 2. Each digit is encoded with the number of homes added or removed by floor due to subdivision. This diagram illustrates that zero homes have been added on the first floor (I) and eight homes have been added on the top floor (II) through airspace development, for instance.
</div>
