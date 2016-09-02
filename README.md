# Kalifakone.github.io
My website
<!DOCTYPE html>
<html>
<title>The Story Of My World</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="http://www.w3schools.com/lib/w3.css">
<link rel="icon" href="/favicon.ico" type="image/x-icon">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "African", sans-serif;}
body, html {
    height: 100%;
    color: #777;
    line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
    opacity: 0.7;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-color: black;
}

/* First image (Logo. Full height) */
.bgimg-1 {
    background-image: url("");
    min-height: 100%;
}

/* Second image (Portfolio) */
.bgimg-2 {
    background-image: url("");
    min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
    background-image: url("");
    min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}



/* Turn off parallax scrolling for tablets and mobiles */
@media only screen and (max-width: 1024px) {
    .bgimg-1, .bgimg-2, .bgimg-3 {
        background-attachment: scroll;
    }
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <ul class="w3-navbar" id="myNavbar">
    <li><a href="#" class="w3-padding-large">HOME</a></li>
    <li class="w3-hide-small w3-right"><li><a href="http://The Story Of My World.strikingly.com/" class="w3-padding-large">Website</a></li>
    <li class="w3-hide-small w3-right">

      <a href="" class="w3-padding-large w3-hover-red"><i class="fa fa-search"></i></a>
    </li>
  </ul>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-opacity w3-display-container">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-xlarge w3-black w3-xlarge w3-wide w3-animate-opacity">KALIFA<span class="w3-hide-small"> WEBSITE</span> </span>
  </div>

</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT ME</h3>
  <p class="w3-center"><em>I love programming</em></p>
  <p>"We always say" Allah remove the bad people from our lives"...But what makes you think that you're the "good one"? Maybe you were the "Bad one" in someone's life and Allah remove you from theirs."</p>
  <div class="w3-row">
    <div class="w3-content w3-container w3-padding-64">
      <p><b>Kalifa Konneh</b></p><br>
      <img src="Makerfaire.JPG" class="w3-center" alt="Photo of Me">
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-section">
      <p>Welcome to my website.</p>
    </div>
  </div>
</div>

<!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-light-grey w3-wide">PORTFOLIO</span>
  </div>
</div>

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64">
  <h3 class="w3-center">MY WORK</h3>
  <p class="w3-center"><em>Here are some of my latest lorem work ipsum tipsum.<br> Click on the images to make them bigger</em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="Google.JPG" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

    <div class="w3-col m3">
      <img src="Yahoo!.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

    <div class="w3-col m3">
      <img src="PIC.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

    <div class="w3-col m3">
      <img src="image.jpg" style="width:80%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>
  </div>

  <div class="w3-row-padding w3-center w3-section">
    <div class="w3-col m3">
      <img src="Tinko.jpg" style="width:80%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>



    <div class="w3-col m3">
      <img src="RED.jpg" style="width:80%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>

    <div class="w3-col m3">
      <img src="https://lh3.googleusercontent.com/-yYDSxwx6Dq4/V6y098o-qLI/AAAAAAAAG8w/aHrMsdqYyNcz2pvPx2t-KYNf3sC5b-fsACEw/w139-h140-p/IMG_1506.JPG" style="width:80%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-closebtn w3-hover-red w3-text-white w3-xxxlarge w3-container w3-display-topright">Gallery</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" style="max-width:100%">
  </div>
</div>

<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-light-grey w3-wide">CONTACT</span>
  </div>
</div>

<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64">
  <h3 class="w3-center">WHERE I WORK</h3>
  <p class="w3-center"><em>I'd love your feedback!</em></p>

  <div class="w3-row w3-padding-32 w3-section">
    <div class="w3-col m4 w3-container">
      <!-- Add Google Maps -->
      <div id="" class="w3-round-large"></div>
    </div>
    <div class="w3-col m8 w3-container w3-section">
      <div class="w3-large w3-margin-bottom">
        <i class="fa fa-map-marker w3-hover-text-black" style="width:30px"></i> Bronx,NY<br>
        <i class="fa fa-phone w3-hover-text-black" style="width:30px"></i> Phone:6467248653<br>
        <i class="fa fa-envelope w3-hover-text-black" style="width:30px"> </i> Email:konnehkalifala@gmail.com<br>
      </div>
      <p>leave me a note:</p>
      <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
        <div class="w3-half">
          <input class="w3-input w3-border w3-hover-light-grey" type="text" placeholder="Name">
        </div>
        <div class="w3-half">
          <input class="w3-input w3-border w3-hover-light-grey" type="text" placeholder="Email">
        </div>
      </div>
      <input class="w3-input w3-border w3-hover-light-grey" type="text" placeholder="Comment">
      <button class="w3-btn w3-section w3-right">SEND</button>
    </div>
  </div>
</div>
 <ul>
    

        <li><a target="_blank" href="https://www.instagram.com/Wizkali_K52/"><img id="ig" 
        <li><a target="_blank" href="https://github.com/kalifakone.github.io"><img id="gh" 
 
      </ul>

<!-- Footer -->
<footer class="w3-center w3-dark-grey w3-padding-48 w3-hover-black">
  <p>Powered by <a href="https://github.com/" title="kalifa" target="_blank" class="w3-hover-opacity">kalifakone.github.io</a></p>
</footer>
 <!-- Add Google Maps --><script src=""></script>
<script>

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-navbar" + " w3-card-2" + " w3-animate-top" + " w3-black";
    } else {
        navbar.className = navbar.className.replace(" w3-card-2 w3-animate-top w3-black", "");
    }
}
</script>

</body>
</html>
