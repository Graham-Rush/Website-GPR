---
title: ""
echo: false
section-divs: false
keep-md: true
---

```{=html} 
<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">5 / 3</div> -->
  <img src="../img/paper.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">6 / 3</div> -->
  <img src="../img/survey.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">7 / 3</div> -->
  <img src="../img/lecture1.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">8 / 3</div> -->
  <img src="../img/sun.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">9 / 3</div> -->
  <img src="../img/os1.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">1 / 3</div> -->
  <img src="../img/ythan-marsh1.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">2 / 3</div> -->
  <img src="../img/lecture2.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">3 / 3</div> -->
  <img src="../img/8map.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <div class="mySlides fade">
  <!-- <div class="numbertext">4 / 3</div> -->
  <img src="../img/plane.jpg" style="width:100%">
  <div class="text"></div>
  </div>
  
  <!-- Next and previous buttons -->
  <!-- <a class="prev" onclick="plusSlides(-1)">&#10094;</a> -->
  <!-- <a class="next" onclick="plusSlides(1)">&#10095;</a> -->
  </div>
  
  <!-- ... Rest of your header content ... -->
  
  <style>
    /* Your CSS styles for the slideshow go here */
    /* Slideshow container */
    .slideshow-container {
      width: 100%; /* Set the desired width for the container. I need this to match the image ratio, as it does now for image 2 */
      <!-- height: 100px; /* Set the desired height for the container */ -->
      overflow: hidden; /* Hide any overflowing content */
      position: relative;
      margin: auto;
      border: 2px solid #068194; /* Add a border around the container */
    }
  
    .image-container img {
    width: 100%; /* Take up the full width of the container */
      height: 100%; /* Take up the full height of the container */
      object-fit: cover; /* Maintain aspect ratio and cover entire container */
      display: block; /* Remove any extra spacing caused by inline display */
  }
  
    /* Hide the images by default */
    .mySlides {
      display: none;
    }
  
    /* Next & previous buttons */
    .prev, .next {
      cursor: pointer;
      position: absolute;
      top: 50%;
      width: auto;
      margin-top: -22px;
      padding: 16px;
      color: white;
      font-weight: bold;
      font-size: 18px;    
      transition: 0.6s ease;
      border-radius: 0 3px 3px 0;
      user-select: none;
    }
  
    /* Caption text */
    .text {
      color: #f2f2f2;
        font-size: 48px;
      padding: 8px 12px;
      position: absolute;
      bottom: 8px;
      width: 100%;
      text-align: center;
    }
  
    /* Text overlay */
    .text-overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      color: red; /* Text color */
        z-index: 1; /* Place the text above the image */
    }
  
    /* Number text (1/3 etc) */
    .numbertext {
      color: #f2f2f2;
        font-size: 12px;
      padding: 8px 12px;
      position: absolute;
      top: 0;
    }
  
    /* Fading animation */
    .fade {
      animation-name: fade;
      animation-duration: 30s;
    }
    
    @keyframes fade {
      from {opacity: .8}
      to {opacity: 1}
    }
  </style>
  
  <script>
    // Your JavaScript code for the slideshow goes here
    let slideIndex = 0;
    showSlides();
    
    function showSlides() {
      let i;
      let slides = document.getElementsByClassName("mySlides");
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) {slideIndex = 1}
      slides[slideIndex-1].style.display = "block";
      setTimeout(showSlides, 5000); // Change image every 2 seconds
    }
  </script>
```



<!-- Start of the code to read and write publication list -->

::: {.cell}

:::


# Publications

## Published articles


###  2021 
<li class='list-group-item'><strong>G. Rush</strong>, P. McDarby, R. Edwards, Y. Milker, E. Garrett  and  W. R. Gehrels (2021) <i>"Development of an intertidal foraminifera training set for the North Sea and an assessment of its application for Holocene sea-level reconstructions".</i> Marine Micropaleontology<br><a class='btn btn-outline-dark btn-sm' href='https://www.sciencedirect.com/science/article/abs/pii/S0377839821000967' target='_blank' rel='noopener noreferrer'><i class='ai ai-archive' role='img' aria-label='Access the orignal article'></i>Access the orignal article</a></li>
<li class='list-group-item'>T. Frederikse, S. Adhikari, T. J. Daley, S. Dangendorf, R. Gehrels, F. Landerer, M. Marcos, T. L. Newton, <strong>G. Rush</strong>, A. B. Slangen  and  others (2021) <i>"Constraining 20th-century sea-level rise in the South Atlantic Ocean".</i> Journal of Geophysical Research and Oceans<br><a class='btn btn-outline-dark btn-sm' href='https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020JC016970' target='_blank' rel='noopener noreferrer'><i class='ai ai-archive' role='img' aria-label='Access the orignal article'></i>Access the orignal article</a></li>###  2020 
<li class='list-group-item'>D. Mauquoy, R. J. Payne, K. V. Babeshko, R. Bartlett, I. Boomer, H. Bowey, C. D. Evans, F. Ring-Hrubesh, D. Muirhead, M. O’Callaghan  and  <strong>G. Rush</strong> (2020) <i>"Falkland Island peatland development processes and the pervasive presence of fire".</i> Quaternary Science Reviews<br><a class='btn btn-outline-dark btn-sm' href='https://www.sciencedirect.com/science/article/abs/pii/S027737912030353X' target='_blank' rel='noopener noreferrer'><i class='ai ai-archive' role='img' aria-label='Access the orignal article'></i>Access the orignal article</a></li>###  2019 
<li class='list-group-item'>R. J. Payne, F. Ring-Hrubesh, <strong>G. Rush</strong>, T. J. Sloan, C. D. Evans  and  D. Mauquoy (2019) <i>"Peatland initiation and carbon accumulation in the Falkland Islands".</i> Quaternary Science Reviews<br><a class='btn btn-outline-dark btn-sm' href='https://www.sciencedirect.com/science/article/abs/pii/S027737911930068X' target='_blank' rel='noopener noreferrer'><i class='ai ai-archive' role='img' aria-label='Access the orignal article'></i>Access the orignal article</a></li>###  2018 
<li class='list-group-item'><strong>G. Rush</strong>, L. E. Clarke, M. Stone  and  M. J. Wood (2018) <i>"Can drones count gulls? Minimal disturbance and semiautomated image processing with an unmanned aerial vehicle for colony-nesting seabirds".</i> Ecology and evolution<br><a class='btn btn-outline-dark btn-sm' href='https://onlinelibrary.wiley.com/doi/full/10.1002/ece3.4495' target='_blank' rel='noopener noreferrer'><i class='ai ai-archive' role='img' aria-label='Access the orignal article'></i>Access the orignal article</a></li>


<!-- This si some text -->

<!-- ```{r} -->
<!-- cat(paste("this is some more text")) -->
<!-- ``` -->

## Working Papers / Non-archival


<ul class='list-group list-group-flush'>
</ul>
