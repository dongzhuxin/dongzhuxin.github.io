---
layout: single
title: "Research Summary:"
permalink: /research/

---
<p style="text-align:justify">Biomedical engineering, the most rapidly growing of engineering disciplines from a global perspective, is now playing an irreplaceable role in the enhancement of human lifespan and its quality. At the <b>Biomedical Nanotechnology Laboratory</b>, we explore multi-disciplinary research and cutting-edge technology so that we bridge medicine and technology. Specifically, I am dedicated to achieving similar success with polypeptide sequencing to what nanopore sequencing has done to DNA so that there will be a possibility that we understand the causes of protein primary structure related diseases better and consequently come up with a solution. Moreover, solid-state nanopores have huge potential in cell secretion detection and its target molecules are selective thanks to their adjustable geometry. I am also interested in utilizing electron microscopy and atomic force microscopy in various biomedical applications, such as synthetic biology and virology, to aid clinic treatment.</p>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: blue;
  font-weight: bold;
  font-size: 24px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: grey;
  font-size: 14px;
  padding: 8px 12px;
  position: bottom;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/8 etc) */
.numbertext {
  color: blue;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 8</div>
  <img src="/assets/images/Research-Fig1-1.png" alt="drawing" width="1000" />
  <div class="text">Through focus images and simulations of a subnanopore, <em>Nature Communications</em>, 2019</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 8</div>
  <img src="/assets/images/Research-Fig2-2.png" alt="drawing" width="1000" />
  <div class="text">Correlated ionic current noise, <em>Nature Communications</em>, 2019</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 8</div>
  <img src="/assets/images/Research-Fig3-3.png" alt="drawing" width="1000" />
  <div class="text">Biomarker detection from the secretome of a cancer cell, <em>Nano Letters</em>, 2018</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 8</div>
  <img src="/assets/images/Research-Fig4-4.png" alt="drawing" width="1000" />
  <div class="text">Discriminate protein variants at single molecule level, <em>ACS Nano</em>, 2017</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 8</div>
  <img src="/assets/images/Research-Fig5-5.png" alt="drawing" width="1000" />
  <div class="text">Subnanopores for protein sequencing, <em>Nature Nanotechnology</em>, 2016</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 8</div>
  <img src="/assets/images/Research-Fig6-6.png" alt="drawing" width="1000" />
  <div class="text">AFM in synthetic biology, <em>Scientific Reports</em>, 2016</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 8</div>
  <img src="/assets/images/Research-Fig7-7.png" alt="drawing" width="1000" />
  <div class="text">Fabrication of pH sensors for uL solutions, <em>Sensors & Actuators A: Physical</em>, 2013</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">8 / 8</div>
  <img src="/assets/images/Research-Fig8-8.png" alt="drawing" width="1000" />
  <div class="text">Calibration of MEMS inertial sensors, <em>IEEE Sensors Journal</em>, 2010</div>
</div>


<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
  <span class="dot" onclick="currentSlide(7)"></span>
  <span class="dot" onclick="currentSlide(8)"></span>
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

</body>
