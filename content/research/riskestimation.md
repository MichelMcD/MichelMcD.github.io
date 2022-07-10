+++
title = "How well do people judge the risks that they face?"
date = 2017-09-24
+++




People negotiate a variety of risks in their everyday life, from those that pose a threat to survival (e.g., diseases or accidents), to one's quality of life (e.g., victim of crime), or to one's future (e.g., bankruptcy, natural disasters). Information about risks are disseminated via a multitude of sources, including public risk communications (e.g., public health announcements), scientific publications, news media, personal conversations, and more recently via social media. These communications can be of varying quality: the probability of risks can be over- or understated, misrepresented (e.g., false news), uncertain (e.g., climate change predictions), or the statistics themselves may be difficult to understand (e.g., relative risk ratios). 

In this environment, how well do people judge the different risks that they face? 

We asked a representative sample of participants from each of six European countries to estimate, out of every 1,000,000 people in their country, how many experienced each of 13 different risks in the past year. Details of the risks can be found in Table 1.

<figure>
<img class="myImg" src="/estact_plot-1.png" alt="The figure shows how many people experience each risk in a country each year (x-axis) against people's estimates of how many people experience those risks (y-axis). The grey dots represent jittered individual data estimates. Blue dots represent the median estimate for each risk. The grey line denotes where points should fall if people perfectly predicted the actual rates. The blue curved line is a fitted polynomial regression line with shading representing 95% confidence intervals." style="width:100%;max-width:1000px">
</figure>
<figcaption> The figure shows how many people experience each risk in a country each year (x-axis) against people's estimates of how many people experience those risks (y-axis). The grey dots represent jittered individual data estimates. Blue dots represent the median estimate for each risk. The grey line denotes where points should fall if people perfectly predicted the actual rates. The blue curved line is a fitted polynomial regression line with shading representing 95% confidence intervals.</figcaption>

</br>

The relationship between estimated and actual rates shows an underestimation of events that tend to have a higher frequency of occurring (e.g., privacy theft) and an overestimation of events that tend to have a low frequency of occurring (e.g., deaths from drowning). Most risks were overestimated, with the exception of privacy theft, identity theft, frequency of third party insurance claims, and people who report saving money by using LED lights.


Table 1. Description of each risk and the data source/s used to obtain real world data on actual risks for each country
<figure>
<img class="myImg" src="/riskdesc.png" alt="" style="width:100%;max-width:800px">
</figure>



<!-- The Modal -->
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>

  <script>

$(document).ready(function () {
  // Get the modal
  var modal = document.getElementById("myModal");
  
var img = $('.myImg');
var modalImg = $("#img01");
var captionText = document.getElementById("caption");
$('.myImg').click(function(){
    modal.style.display = "block";
    var newSrc = this.src;
    modalImg.attr('src', newSrc);
    captionText.innerHTML = this.alt;
});

  // Get the <span> element that closes the modal
  var span = document.getElementsByClassName("close")[0];
  
  // When the user clicks on <span> (x), close the modal
  span.onclick = function() { 
    modal.style.display = "none";
  }
});

  </script>

