# allstrangerthings.github.io
<html lang="en">
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: "Lato", sans-serif}
.mySlides {display: none}
</style>
</head>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-black w3-card">
    <a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">HOME</a>
    <a href="#band" class="w3-bar-item w3-button w3-padding-large w3-hide-small">BAND</a>
    <a href="#tour" class="w3-bar-item w3-button w3-padding-large w3-hide-small">TOUR</a>
    <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hide-small">CONTACT</a>
    <div class="w3-dropdown-hover w3-hide-small">
      <button class="w3-padding-large w3-button" title="More">MORE <i class="fa fa-caret-down"></i></button>     
      <div class="w3-dropdown-content w3-bar-block w3-card-4">
        <a href="#" class="w3-bar-item w3-button">Merchandise</a>
        <a href="#" class="w3-bar-item w3-button">Extras</a>
        <a href="#" class="w3-bar-item w3-button">Media</a>
      </div>
    </div>
    <a href="javascript:void(0)" class="w3-padding-large w3-hover-red w3-hide-small w3-right"><i class="fa fa-search"></i></a>
  </div>
</div>

<!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
<div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
  <a href="#band" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">BAND</a>
  <a href="#tour" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">TOUR</a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">CONTACT</a>
  <a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">MERCH</a>
</div>

<!-- Page content -->
<div class="w3-content" style="max-width:2000px;margin-top:46px">

  <!-- Automatic Slideshow Images -->
 <img src="https://pbs.twimg.com/media/EIs-iykU8AASn2x.jpg:large">

  <!-- The Band Section -->
  <div class="w3-container w3-content w3-center w3-padding-64" style="max-width:800px" id="band">
    <h2 class="w3-wide">THE BAND</h2>
    <p class="w3-opacity"><i>We love music</i></p>
    <p class="w3-justify">We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
      ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur
      adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    <div class="w3-row w3-padding-32">
      <div class="w3-third">
        <p>Name</p>
        <img src="/w3images/bandmember.jpg" class="w3-round w3-margin-bottom" alt="Random Name" style="width:60%">
      </div>
      <div class="w3-third">
        <p>Name</p>
        <img src="/w3images/bandmember.jpg" class="w3-round w3-margin-bottom" alt="Random Name" style="width:60%">
      </div>
      <div class="w3-third">
        <p>Name</p>
        <img src="/w3images/bandmember.jpg" class="w3-round" alt="Random Name" style="width:60%">
      </div>
    </div>
  </div>

  <!-- The Tour Section -->
  <div class="w3-black" id="tour">
    <div class="w3-container w3-content w3-padding-64" style="max-width:800px">
      <h2 class="w3-wide w3-center">TOUR DATES</h2>
      <p class="w3-opacity w3-center"><i>Remember to book your tickets!</i></p><br>

      <ul class="w3-ul w3-border w3-white w3-text-grey">
        <li class="w3-padding">September <span class="w3-tag w3-red w3-margin-left">Sold out</span></li>
        <li class="w3-padding">October <span class="w3-tag w3-red w3-margin-left">Sold out</span></li>
        <li class="w3-padding">November <span class="w3-badge w3-right w3-margin-right">3</span></li>
      </ul>

      <div class="w3-row-padding w3-padding-32" style="margin:0 -16px">
        <div class="w3-third w3-margin-bottom">
          <img src="https://m.media-amazon.com/images/I/71OB1IywjLL._AC_SY679_.jpg" alt="New York" style="width:100%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>Season 1</b></p>
            <p class="w3-opacity">Fri 27 Nov 2016</p>
            <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Read More</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIZZgbOE3oHOrgLt4YlI45ywrd_n53cVY7AQrMeF_nD4MH5e5JDMaYQX2tHOzrqoo7vNI&usqp=CAU" alt="Paris" style="width:100%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>Season 2</b></p>
            <p class="w3-opacity">Sat 28 Nov 2016</p>
            <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Read More</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <img src="https://m.media-amazon.com/images/I/71nBDp-RjyL._AC_SY741_.jpg" alt="San Francisco" style="width:100%" class="w3-hover-opacity">
          <div class="w3-container w3-white">
            <p><b>Season 3</b></p>
            <p class="w3-opacity">Released 2019</p>
            <p>Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Read more</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Ticket Modal -->
  <div id="ticketModal" class="w3-modal">
    <div class="w3-modal-content w3-animate-top w3-card-4">
      <header class="w3-container w3-teal w3-center w3-padding-32"> 
        <span onclick="document.getElementById('ticketModal').style.display='none'" 
       class="w3-button w3-teal w3-xlarge w3-display-topright">×</span>
        <h2 class="w3-wide"><i class="fa fa-suitcase w3-margin-right"></i>Tickets</h2>
      </header>
      <div class="w3-container">
        <p><label><i class="fa fa-shopping-cart"></i> Tickets, $15 per person</label></p>
        <input class="w3-input w3-border" type="text" placeholder="How many?">
        <p><label><i class="fa fa-user"></i> Send To</label></p>
        <input class="w3-input w3-border" type="text" placeholder="Enter email">
        <button class="w3-button w3-block w3-teal w3-padding-16 w3-section w3-right">PAY <i class="fa fa-check"></i></button>
        <button class="w3-button w3-red w3-section" onclick="document.getElementById('ticketModal').style.display='none'">Close <i class="fa fa-remove"></i></button>
        <p class="w3-right">Need <a href="#" class="w3-text-blue">help?</a></p>
      </div>
    </div>
  </div>
<h2 id="gtktc" class="w3-wide w3-center">Get to know the characters</h2>
  <!-- Charecter info section -->
<html>
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
  color: white;
  font-weight: bold;
  font-size: 18px;
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
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
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
  animation-name: fade;
  animation-duration: 1.5s;
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
  <div class="numbertext">1 / 34</div>
  <img src="https://i.pinimg.com/236x/27/52/b4/2752b4321101558661f818e4a415d3d2.jpg" style="width:100%">
  <div class="text">Will Byers</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 34</div>
  <img src="https://i.pinimg.com/236x/a5/16/37/a51637a46b854ba0b17b3d45217feddc.jpg" style="width:100%">
  <div class="text">Dustin</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 34</div>
  <img src="https://i.pinimg.com/236x/63/be/03/63be033ba2d85eacd30c6b9bdf9e96ac.jpg" style="width:100%">
  <div class="text">Caption Three</div>
</div>
<div class="mySlides fade">
  <div class="numbertext">4 / 34</div>
  <img src="https://i.pinimg.com/236x/67/7c/66/677c661c95bfb99f005bdce2d4001005.jpg" style="width:100%">
  <div class="text">Max</div>
</div>
<div class="mySlides fade">
  <div class="numbertext">5 / 34</div>
  <img src="https://i.pinimg.com/236x/8b/79/2e/8b792eb0c155bcfd6f8ddc1529e1bce9.jpg" style="width:100%">
  <div class="text">Billy</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 34</div>
  <img src="https://i.pinimg.com/236x/e7/14/ca/e714ca688db0b79c3bde6c2465241826.jpg" style="width:100%">
  <div class="text">Joyce Byers</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 34</div>
  <img src="https://i.pinimg.com/236x/56/88/b2/5688b23b695ff634a3fa3e26b9397ebf.jpg" style="width:100%">
  <div class="text">Eleven</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">8 / 34</div>
  <img src="data:image/jpeg;base64,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" style="width:100%">
  <div class="text">Steve Harrington</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">9 / 34</div>
  <img src="data:image/jpeg;base64,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" style="width:100%">
  <div class="text">Mike Wheeler</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">10 / 34</div>
  <img src="data:image/jpeg;base64,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" style="width:100%">
  <div class="text">Nancy Wheeler</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">11 / 34</div>
  <img src="data:image/jpeg;base64,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" style="width:100%">
  <div class="text">Robin Buckly</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">12 / 34</div>
  <img src="data:image/jpeg;base64,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" style="width:100%">
  <div class="text">Jim Hopper</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">13 / 34</div>
  <img src="data:image/jpeg;base64,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" style="width:100%">
  <div class="text">Barbra Holland</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">14 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">15 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">16 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">17 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">18 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">19 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">20 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">21 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">22 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">23 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">24 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">25 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">26 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">27 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">28 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">29 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">30 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">31 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">32 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">33 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">34 / 34</div>
  <img src="img_nature_wide.jpg" style="width:100%">
  <div class="text">Caption Tex</div>
</div>


<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

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
            <span class="dot" onclick="currentSlide(9)"></span> 
              <span class="dot" onclick="currentSlide(10)"></span> 
                <span class="dot" onclick="currentSlide(11)"></span> 
                  <span class="dot" onclick="currentSlide(12)"></span> 
                    <span class="dot" onclick="currentSlide(13)"></span> 
                      <span class="dot" onclick="currentSlide(14)"></span> 
            <span class="dot" onclick="currentSlide(3)"></span>   <span class="dot" onclick="currentSlide(3)"></span>   <span class="dot" onclick="currentSlide(15)"></span>   <span class="dot" onclick="currentSlide(16)"></span>   <span class="dot" onclick="currentSlide(17)"></span>   <span class="dot" onclick="currentSlide(18)"></span>   <span class="dot" onclick="currentSlide(19)"></span>   <span class="dot" onclick="currentSlide(20)"></span>   <span class="dot" onclick="currentSlide(21)"></span>   <span class="dot" onclick="currentSlide(22)"></span>   <span class="dot" onclick="currentSlide(23)"></span>   <span class="dot" onclick="currentSlide(24)"></span>   <span class="dot" onclick="currentSlide(25)"></span>   <span class="dot" onclick="currentSlide(26)"></span>   <span class="dot" onclick="currentSlide(27)"></span>   <span class="dot" onclick="currentSlide(28)"></span>   <span class="dot" onclick="currentSlide(29)"></span>   <span class="dot" onclick="currentSlide(30)"></span>   <span class="dot" onclick="currentSlide(31)"></span>   <span class="dot" onclick="currentSlide(32)"></span>   <span class="dot" onclick="currentSlide(33)"></span>   <span class="dot" onclick="currentSlide(34)"></span> 
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
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
</html> 
  
<!-- End Page Content -->
</div>

  <style>
  // Automatic Slideshow - change image every 4 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 4000);    
}

// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}

// When the user clicks anywhere outside of the modal, close it
var modal = document.getElementById('ticketModal');
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
  </style>
  <!-- The Contact Section -->
  <div class="w3-container w3-content w3-padding-64" style="max-width:800px" id="contact">
    <h2 class="w3-wide w3-center">CONTACT</h2>
    <p class="w3-opacity w3-center"><i>Fan? Drop a note!</i></p>
    <div class="w3-row w3-padding-32">
      <div class="w3-col m6 w3-large w3-margin-bottom">
        <i class="fa fa-map-marker" style="width:30px"></i> Chicago, US<br>
        <i class="fa fa-phone" style="width:30px"></i> Phone: +00 151515<br>
        <i class="fa fa-envelope" style="width:30px"> </i> Email: mail@mail.com<br>
      </div>
      <div class="w3-col m6">
        <form action="/action_page.php" target="_blank">
          <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
            </div>
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
            </div>
          </div>
          <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
          <button class="w3-button w3-black w3-section w3-right" type="submit">SEND</button>
        </form>
      </div>
    </div>
  </div>
  
  
<!-- Image of location/map -->
<img src="/w3images/map.jpg" class="w3-image w3-greyscale-min" style="width:100%">

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-opacity w3-light-grey w3-xlarge">
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
  <i class="fa fa-twitter w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
  <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
</footer>

<script>

</script>

</body>
</html>
