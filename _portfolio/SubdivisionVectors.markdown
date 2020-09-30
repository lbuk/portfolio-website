---
layout: post
title: Subdivision Vectors
description: A data structure for recording building subdivision by floor
img: /img/numbers.png
---

Planning data is mostly unstructured, messy and two-dimensional. The creation of structured, machine-readable data on building subdivision is a challenge for urban practitioners.

A solution to this problem is to record subdivision using a simple and machine-readable data structure that consists of a list of numbers. Each number represents the floor of a building. The encoding of the numbers illustrates whether subdivision has occurred on a floor or alternatively the number of homes added or subtracted.

This new technique, entitled Subdivision Vectors, could be utilised by planners and designers to provide structured data on building subdivision. The data can be added to spreadsheets, for instance, as a new variable to describe subdivision by floor. Inspired by the work of Steadman, Martin and March in field of architectural design, the Subdivision Vectors could be deployed to provide a better picture of housing density.

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/subdivision_vectors.png" alt="" title=""/>
</div>

<div class="col three caption">
	Figure 1. Each digit is encoded with a zero or a one. A zero means that no subdivision has taken place on that floor. A one indicates that the floor has been subdivided. Here, subdivision has occurred on the third and sixth floors.
</div>

<br>

<div class="col">
	<img class="col" src="{{ site.baseurl }}/img/subdivision_vectors_homes.png" alt="" title=""/>
</div>

<div class="col three caption">
	Figure 2. Each number is encoded with the number of homes added or removed by floor due to subdivision. This diagram illustrates that zero homes have been added on the first floor and eight homes have been added on the top floor. It may be best to use spaces between the floor numbers for blocks.
</div>
