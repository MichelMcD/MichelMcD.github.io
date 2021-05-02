
+++
title = "Developing a Fact Box"
date = 2017-09-24
+++

A Fact Box presents a simple tabular summary of the best available evidence about the benefits and harms of a medical procedure, treatment, or health behaviour. When developing a Fact Box, there are a number of key features to keep in mind: 

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>

<div class="slideshow-container">

<div class="mySlides">
  <div class="numbertext">1 / 7</div>
  <img src="/BuildFB_1.png" style="width:100%">
  <div class="captext">The Fact Box has the following key features..</div>
</div>

<div class="mySlides">
  <div class="numbertext">2 / 7</div>
  <img src="/BuildFB_2.png" style="width:100%">
  <div class="captext">A clear reference class (e.g., to whom does the information refer?)</div>
</div>

<div class="mySlides">
  <div class="numbertext">3 / 7</div>
  <img src="/BuildFB_3.png" style="width:100%">
  <div class="captext">List of benefits and harms, with equal weight given to both. </div>
</div>

<div class="mySlides">
  <div class="numbertext">4 / 7</div>
  <img src="/BuildFB_4.png" style="width:100%">
  <div class="captext">Comparison groups, such as a group who received a new treatment compared to a group who did not. </div>
</div>

<div class="mySlides">
  <div class="numbertext">5 / 7</div>
  <img src="/BuildFB_5.png" style="width:100%">
  <div class="captext">A measure of effect, such as how many people experienced the outcome in each group.</div>
</div>

<div class="mySlides">
  <div class="numbertext">6 / 7</div>
  <img src="/BuildFB_6.png" style="width:100%">
  <div class="captext">Short summary statement, with care not to recommend a specific course of action.</div>
</div>

<div class="mySlides">
  <div class="numbertext">7 / 7</div>
  <img src="/BuildFB_7.png" style="width:100%">
  <div class="captext">State your sources and date of last update.</div>
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

<br>
<p> You can find more detailed guidance on how to develop a Fact Box here: </p>

<P class="pub"> <SPAN class="myauthor">McDowell, M</SPAN>, Rebitschek, F, Gigerenzer, G, & Wegwarth, O (2016). A simple tool for communicating the beneﬁts and harms of health interventions: A guide for creating a fact box. <SPAN class="journal">MDM Policy & Practice </SPAN>(1), 1-10. doi:10.1177/2381468316665365</SPAN> <br> <button class="openaccess" onclick="document.location='https://journals.sagepub.com/doi/pdf/10.1177/2381468316665365'" target="_blank" rel="noopener"> <i class="ai ai-open-access big-icon"> </i>PDF </button> <button class="doi" onclick="document.location='https://journals.sagepub.com/doi/10.1177/2381468316665365'" target="_blank" rel="noopener" >doi</button>  
<button data-target="bibtex-panel-mcdowell2016a" class="accordion">bibtex</button></p>
<div id="bibtex-panel-mcdowell2016a" class="panel" style="display:block">
  <pre> @article{mcdowell2016a,
  title = {A Simple Tool for Communicating the Benefits and Harms of Health Interventions: A Guide for Creating a Fact Box},
  author = {McDowell, Michelle and Rebitschek, Felix G. and Gigerenzer, Gerd and Wegwarth, Odette},
  date = {2016-07-01},
  journaltitle = {MDM Policy \& Practice},
  volume = {1},
  pages = {2381468316665365},
  doi = {10.1177/2381468316665365},
  number = {1}
} </pre>
</div>
