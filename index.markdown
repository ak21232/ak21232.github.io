---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://kit.fontawesome.com/a2b003a1d5.js" crossorigin="anonymous"></script>
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif;}
body, html {
  height: 100%;
  color: #777;
  line-height: 1.8;
}

/* Create a Parallax Effect */
.bgimg-1, .bgimg-2, .bgimg-3 {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/* First image (Logo. Full height) */
.bgimg-1 {
  background-image: url('images/parallax1.jpg');
  min-height: 400px;
}

/* Second image (Portfolio) */
.bgimg-2 {
  background-image: url("images/parallax2.jpg");
  min-height: 400px;
}

/* Third image (Contact) */
.bgimg-3 {
  background-image: url("images/parallax3.jpg");
  min-height: 400px;
}

.w3-wide {letter-spacing: 10px;}
.w3-hover-opacity {cursor: pointer;}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1600px) {
  .bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: scroll;
    min-height: 400px;
  }
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar" id="myNavbar">
    <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
      <i class="fa fa-bars"></i>
    </a>
    <a href="#home" class="w3-bar-item w3-button">HOME</a>
    <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> ABOUT</a>
    <a href="#myskills" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-user"></i> MY SKILLS</a>
    <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-project-diagram"></i> PROJECTS</a>
    <a href="#fundraising" class="w3-bar-item w3-button w3-hide-small"><i class="fas fa-hand-holding-heart"></i> FUNDRAISING</a>
    <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-right w3-hover-red">
      <i class="fa fa-search"></i>
    </a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
    <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT</a>
    <a href="#myskills" class="w3-bar-item w3-button" onclick="toggleFunction()">MY SKILLS</a>
    <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">PROJECTS</a>
    <a href="#fundraising" class="w3-bar-item w3-button" onclick="toggleFunction()">FUNDRAISING</a>
    <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
    <a href="#" class="w3-bar-item w3-button">SEARCH</a>
  </div>
</div>

<!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity">KHANCODE</span>
  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center">ABOUT ME</h3>
  <p class="w3-center"><em>Infinite Improvement Loop</em></p>
  <p>As I've gone through the challenges of life I have come to notice one thing: there are tons of things I suck at. In highschool I sucked at math and chemistry.
	In undergrad I sucked at statistics and computer science. What I do not suck at is identifying these issues and bridging the gap to improve at what I lack. Currently I am a Software
	Reliability Engineer who's attending grad school for a Master's in Computer Science with a B.S. in Chemical Engineering and a certification in Data Science. I constantly re-evaluate
	myself and develop weaknesses into passions.</p>
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <img src="images/myphoto.png" class="w3-round w3-image w3-hover-opacity" alt="Photo of Me" width="500" height="333">
      <p><b><i class="fa fa-user w3-margin-right"></i>Abraar Khan</b></p><br>
    </div>
    <div class="w3-col m6 w3-padding-large">
      <p>I've chosen to create this website to give you a better idea of who I am and what I like to do. You may notice a variety of programming projects with varying degrees of complexity. As a programmer without the traditional programming background I think its important that I can display my progress. Each step was important in forming the engineer I am today. Please feel free to browse through my work and contact me for inquiries. All the information is laid out below. </p>
    </div>
  </div>
  <br>
  <br>

  <!-- Container (My Skills Section) -->
  <div class="w3-content w3-container w3-padding-64" id="myskills">
    <h3 class="w3-center">MY SKILLS</h3>
    <br>
    <p class="w3-wide"><i class="fa fa-code fa-lg"></i>   C++   |   Python   |   Visual Basic</p>
    <hr>
    <p class="w3-wide"><i class="fa fa-vial fa-lg"></i>   QA Testing</p>
    <hr>
    <p class="w3-wide"><i class="fa fa-chart-line fa-lg"></i>   Business Intelligence</p>
    <hr>
    <p class="w3-wide"><i class="fa fa-life-ring"></i>   Application Reliability</p>
    <hr>
    <p class="w3-wide"><i class="fa fa-database"></i>   Database Management</p>
    <hr>
    <p class="w3-wide"><i class="fab fa-aws"></i>   Amazon Web Services</p>
    <hr>
    <p class="w3-wide"><i class="fa fa-users fa-lg"></i>   Agile Collaboration</p>
    <hr>
    <br>
  </div>


<!-- Second Parallax Image with Portfolio Text -->
<div class="bgimg-2 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
    <span class="w3-xxlarge w3-text-white w3-wide">PROJECTS</span>
  </div>
</div>

<!-- Container (Portfolio Section) -->
<div class="w3-content w3-container w3-padding-64" id="portfolio">
  <h3 class="w3-center">What I've Been Working On</h3>
  <p class="w3-center"><em> Click the caption to take a look at the project </em></p><br>

  <!-- Responsive Grid. Four columns on tablets, laptops and desktops. Will stack on mobile devices/small screens (100% width) -->
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="images/NaturalGasRecovery.png"  onclick="onClick(this)" class="w3-hover-opacity" alt="Natural Gas Recovery Project">
      <a href="https://drive.google.com/file/d/0B4guoFwFU9reZ1lQQVJfTVhjQVU/view?usp=sharing">Natural Gas Recovery</a>
    </div>
    <div class="w3-col m3">
      <img src="images/COVID-19.png"  onclick="onClick(this)" class="w3-hover-opacity" alt="Covid-19 Model">
      <a href="https://github.com/ak21232/california-coronavirus-data">COVID-19 Model</a>
    </div>
    <div class="w3-col m3">
      <img src="images/ScheduleOptimizer.png" onclick="onClick(this)" class="w3-hover-opacity" alt="Schedule Optimizer">
      <a href="https://github.com/ak21232/Schedule_Optimizer.git">Schedule Optimizer</a>
    </div>
  </div>
  <div class="w3-row-padding w3-center">
    <div class="w3-col m3">
      <img src="images/ProcessControl.png" onclick="onClick(this)" class="w3-hover-opacity" alt="Process Control">
      <a href="https://github.com/ak21232/ProcessControl.git">Process Control</a>
    </div>
    <div class="w3-col m3">
      <img src="images/ResourceMonitor.png" onclick="onClick(this)" class="w3-hover-opacity" alt="Resource Monitor">
      <a href="https://github.com/ak21232/Resource_Monitor.git">Resource Monitor</a>
    </div>
  </div>
</div>
<br>
<hr>
<br>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Container (FundRaising) -->
<div class="w3-content w3-container w3-padding-64" id="fundraising">
  <h3 class="w3-center">FUNDRAISING</h3>
  <p class="w3-center"><em>An opportunity to make a difference</em></p>
  <p>On June 20, 2020 my mother, Nadira Begum, passed away from complications due to stroke triggered by Moyamoya disease.
  Moyamoya is a disease that occurs when the arteries leading to the brain narrow and other vessels try to compensate.
  Extremely rare and limited in treatment options, patients must seek specialty care.
  </p>
  <div class="w3-row">
    <div class="w3-col m6 w3-right w3-padding-large">
      <img src="images/marathonsformoyamoya.jpg" class="w3-round w3-image w3-hover-opacity" alt="Mom and I" width="500" height="333">
      <p><b><i class="fa fa-heart w3-margin-right"></i>Marathons For Moyamoya </b></p><br>
    </div>
    <div class="w3-col m6 w3-padding-large">
      <p> Enter Anthony Wang and the UCLA Neurosurgery team. While under his watch my mother received the best treatment available.
      With constant communication and follow-ups even during the COVID-19 crisis her quality of life was maintained until the end.
      In her memory and her spirit of service to others, I have partnered with UCLA health to create Marathons for Moyamoya, a dedication
      of my marathon runs to raise funds to benefit UCLA neurosurgery.
      Please help me by raising awareness and funds so that people in similar situations receive the best care available. Click the
      UCLA banner below to be redirect to the fundraiser webpage.
      </p>
    </div>
  </div>
  <br>
  <div class="w3-center m3">
    <a href="https://spark.ucla.edu/project/23472">
    <img src="images/UCLA_Health.png" class="w3-hover-opacity" alt="Fundraiser">
    </a>
  </div>
  <br>
  <hr>
  <br>

<!-- Third Parallax Image with Portfolio Text -->
<div class="bgimg-3 w3-display-container w3-opacity-min">
  <div class="w3-display-middle">
     <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
  </div>
</div>


<!-- Container (Contact Section) -->
<div class="w3-content w3-container w3-padding-64" id="contact">
  <h3 class="w3-center">How to Reach Out</h3>
  <p class="w3-center"><em>Let's keep in touch</em></p>

  <div class="w3-row w3-padding-32 w3-section">
    <div class="w3-col m4 w3-container">
      <!-- <img src="/w3images/map.jpg" class="w3-image w3-round" style="width:100%"> -->
    </div>
    <div class="w3-col m8 w3-panel">
      <div class="w3-large w3-margin-bottom">
        <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Los Angeles, CA<br>
        <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: (818) 254-8592‬<br>
        <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: akhan022@ucr.edu<br>
      </div>
      <p><i class="fa fa-comments w3-hover-text-black w3-xlarge w3-margin-right"></i> Start a conversation </p>
      <form action="mailto:ak21232@gmail.com" method="post" enctype="text/plain">
        <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
          </div>
          <div class="w3-half">
            <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
          </div>
        </div>
        <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
        <button class="w3-button w3-black w3-right w3-section" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </form>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <a href="https://github.com/ak21232"><i class="fa fa-github w3-hover-opacity"></i></a>&emsp;
    <a href="https://www.linkedin.com/in/abraarkhan/"><i class="fa fa-linkedin w3-hover-opacity"></i></a>
  </div>
</footer>

<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}

// Change style of navbar on scroll
window.onscroll = function() {myFunction()};
function myFunction() {
    var navbar = document.getElementById("myNavbar");
    if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
        navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
    } else {
        navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
    }
}

// Used to toggle the menu on small screens when clicking on the menu button
function toggleFunction() {
    var x = document.getElementById("navDemo");
    if (x.className.indexOf("w3-show") == -1) {
        x.className += " w3-show";
    } else {
        x.className = x.className.replace(" w3-show", "");
    }
}
</script>
