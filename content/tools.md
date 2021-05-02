+++
title = "Tools and Guides"
date = 2017-09-24
+++

<a href="#tools">Tools</a> to help you design risk and uncertainty communications and <a href="#guides">guides</a> on best practices for designing communications.

<h3 class="res" id="tools"> Tools for developing risk communications </h3>

<a href="/factbox"> <b> Guide to design a Fact Box: </b> </a>
A Fact Box presents a simple tabular summary of the best available evidence about the benefits and harms of a medical procedure, treatment, or health behaviour. Here you can find a brief overview of the key features of a Fact Box to help you get started. 

{{ resize_image(path="../static/fb_mam.png", height=100, width=600, op="fit_width") }}


<a href="https://riskyr.org/"> <b> riskyr </b> </a>
is an open source software developed in R with an accompanying interactive R Shiny app for developing interactive representations of risk-related information. The app was developed by:

<p class="pub"> Neth, H., Gaisbauer, F., Gradwohl, N., & Gaissmaier, W. (2021). riskyr: A toolbox for rendering risk literacy more transparent. Social Psychology and Decision Sciences, University of Konstanz, Germany. Computer software (R package version 0.3.0, Mar. 23, 2021). Retrieved from <a href="https://CRAN.R-project.org/package=riskyr">https://CRAN.R-project.org/package=riskyr</a></p>


<h3 class="res" id="guides"> Guidelines on designing risk communications </h3>

Guidelines for how to design Fact Boxes or Icon Arrays, and principles to improve public understanding and management of risk.

#### CAPUR expert committee principles for risk management

<P class="pub"> Ball, D., Humpherson, E., Johnson, B., <SPAN class="myauthor">McDowell, M</SPAN>, Ng, R., Radaelli, C., Renn, O., Seedhouse, D., Spiegelhalter, D., Uhl, Al. \& Watt, J. (2019, December). Improving Society's Management of Risks: A Statement of Principles. <SPAN class="journal">Collaboration to explore new avenues to improve public understanding and management of risk (CAPUR)</SPAN>. Atomium -- European Institute for Science, Media and Democracy. <br> <button class="pdf" onclick="document.location='https://tinyurl.com/capurstatement'" target="_blank" rel="noopener">PDF</button>

#### Best practice guideline for developing fact boxes

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

#### Best practices for presenting information in decision aids

<P class="pub">Recently, Medical Decision Making published a series of papers updating the patient decision aids standards (IPDAS) including on <a href="https://journals.sagepub.com/doi/full/10.1177/0272989X21996622">basing information comprehensive syntheses of evidence</a>, <a href="https://journals.sagepub.com/doi/pdf/10.1177/0272989X21996328">presenting probabilities</a>, and <a href="https://journals.sagepub.com/doi/full/10.1177/0272989X21996342">challenges to presenting numbers</a> in patient decision aids. </P>


<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");

    var target = this.getAttribute("data-target");
    var panel = document.getElementById(target);

    if (panel.style.maxHeight) {
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
</script>