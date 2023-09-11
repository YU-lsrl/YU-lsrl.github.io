---
layout: page
permalink: /gallery/
title: gallery
description: 
nav: true
nav_order: 3
---
<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    {% include figure.html path="assets/img/ab.jpg" title="example image" width="200" height="200" class="img-fluid rounded z-depth-1" %}
    <div class="text">Caption Text</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    {% include figure.html path="assets/img/mah.jpg" title="example image" width="200" height="200" class="img-fluid rounded z-depth-1" %}
    <div class="text">Caption Two</div>
  </div>
 <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    {% include figure.html path="assets/img/mg.jpg" title="example image" width="200" height="200" class="img-fluid rounded z-depth-1" %}
    <div class="text">Caption Three</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
</div>
