# PRADIPTA_GHOSH
<!DOCTYPE html> 

<html lang="en"> 

  

<head> 

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" crossorigin="anonymous">
    <link rel="stylesheet" href="styles.css">


    <title> 

        How to Integrate Webcam using 

        JavaScript on HTML5 ? 

    </title> 

    <h1>This Website is Made By :- PRADIPTA GHOSH</h1>


<!--CLOCK HTML-->
<!DOCTYPE html>
<html lang="en">

<head>
 <meta charset="UTF-8" />
 <meta name="viewport" content=
  "width=device-width,
  initial-scale=1.0" />

 <title>Digital Clock</title>

 <style>
  #clock {
   font-size: 130px;
   width: 860px;
   margin: 35px;
   text-align: center;
   background:yellow;
   color:blue;
   border: 15px solid red;
   border-radius: 20px;
  }


h2{
            color: white;
            background: black;
            text-align: center;
            font-size: 80px;
            transition: 1s;
            font-style:all;
        }
        h2:hover{
      letter-spacing: 8px;
      background-color: green;
      }


 </style>
</head>

<body>
<h2 style="text-align:center; color:white; font-size: 40px;">DIGITAL CLOCK</h2>

<div id="clock"></div>

 <script>
  setInterval(showTime, 1000);
  function showTime() {
   let time = new Date();
   let hour = time.getHours();
   let min = time.getMinutes();
   let sec = time.getSeconds();
   am_pm = "AM";

   if (hour > 12) {
    hour -= 12;
    am_pm = "PM";
   }
   if (hour == 0) {
    hr = 12;
    am_pm = "AM";
   }

   hour = hour < 10 ? "0" + hour : hour;
   min = min < 10 ? "0" + min : min;
   sec = sec < 10 ? "0" + sec : sec;

   let currentTime = hour + ":"
    + min + ":" + sec + am_pm;

   document.getElementById("clock")
    .innerHTML = currentTime;
  }

  showTime();
 </script>
</body>

</html>

<!--END CLOCK-->

    <style>

        h1{
            color: black;
            background: yellow;
            text-align: center;
            font-size: 30px;
            transition: 1s;
            font-style:all;
        }
        h1:hover{
      letter-spacing: 8px;
      background-color: red;
      }

         h3{
            color: white;
            background: blueviolet;
            text-align: center;
            font-size: 40px;
            transition: 1s;
            font-style:all;
        }
        h3:hover{
      letter-spacing: 8px;
      background-color: red;
      }

 h5{
            color: black;
            background: yellow;
            text-align: center;
            font-size: 50px;
                  
        }

        h5:hover{
      letter-spacing: 0px;
      background-color: red;
      color:yellow;
      }
     



    </style>

    <link rel="stylesheet" href="css/style.css"> 

    <link href= 
"https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"

            rel="stylesheet"> 

  

    <script src= 

"http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js" 

    type="text/javascript"> 

  

    </script> 

  

    <script src= 

"https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.bundle.min.js"> 

    </script> 

</head> 

  

<body> 

    <div class="container"> 

        <div class="row"> 

            <div class="col-sm-12"> 

                <div class="card"> 

                    <h5 class="card-header h5 text-center"> 

                        WEBCAM

                    </h5> 

                    <div class="card-body"> 

                        <div class="booth"> 

                            <video id="video" width="100%" 

                                height="100%" autoplay> 

                            </video> 

                        </div> 

  

                        <div class="text-right"> 

                            <a href="#!" class="btn btn-danger" 

                                onClick="stop()"> 

                                Stop Cam 

                            </a> 

                            <a href="#!" class="btn btn-success"

                                onClick="start()"> 

                                Start Cam 

                            </a> 

                        </div> 

                    </div> 

                </div> 

            </div> 

        </div> 

    </div> 

  

    <script> 

        var stop = function () { 

            var stream = video.srcObject; 

            var tracks = stream.getTracks(); 

            for (var i = 0; i < tracks.length; i++) { 

                var track = tracks[i]; 

                track.stop(); 

            } 

            video.srcObject = null; 

        } 

        var start = function () { 

            var video = document.getElementById('video'), 

                vendorUrl = window.URL || window.webkitURL; 

            if (navigator.mediaDevices.getUserMedia) { 

                navigator.mediaDevices.getUserMedia({ video: true }) 

                    .then(function (stream) { 

                        video.srcObject = stream; 

                    }).catch(function (error) { 

                        console.log("Something went wrong!"); 

                    }); 

            } 

        } 

        $(function () { 

            start(); 

        });   

    </script> 


  <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.slim.min.js" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" crossorigin="anonymous"></script>
    <script src="script.js"></script>



</body> 

  
</html> 



<!DOCTYPE html>
<html>
  <head>
    <title>Hello World!</title>

  </head>
  <body>
      <h1></h1>
  </body>
</html>



<!--YOUTUBE VIDEO TAG-->

<!DOCTYPE html>
<html>
<body>

<h3 style="font-size: 40px;">YOUTUBE VIDEO</h3>  

<iframe width="950" height="700" src="https://www.youtube.com/embed/80OX5xMvJP4">
</iframe>

</body>
</html>

<!--END YOUTUBE VIDEO-->

<!--LINK BY HTML-->
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title></title>

<style>
    p{
        font-size: 40px;
        text-align: center;
    }
</style>

</head>
<body>

    <h1>READ THE NEWSPAPER BELOW</h1>
    <p><a href="https://mepaper.anandabazar.com" style="background: black;">Click Here To Read Newspaper</a></p>
    <p><a href="https://www.anandabazar.com/" style="color:green; background: black;" >Click Here To Read Newspaper If the above does not Work</a></p>


</body>
</html>
<!--END LINK-->

<!--PDF HTML-->
<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <h1>👇👇 Read Bengali Stories Below 👇👇</h1>

    <iframe src="Story.pdf" width="100%" height="800px"></iframe>
    <a href="file:///P:/A%20HTML%20MY%20PROJECT/Story.pdf" style="background: black; color: yellow; font-size: 40px;"> OR CLICK HERE TO READ BENGALI STORY</a>


  </body>
</html>
<!--END PDF-->


<!--MUSIC PLAYER HTML-->
<!DOCTYPE html>
<html lang="en">
<head>
<title>Simple Music Player</title>
<!-- Load FontAwesome icons -->
<link rel="stylesheet"
        href=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">

<!-- Load the custom CSS style file -->
<link rel="stylesheet" type="text/css" href="style.css">

<style>

button{

  color: white;
  background: black;
  border: 15px solid black; 
  box-shadow: 0 16px 20px 0 rgba(0,0,0,0.2);
  box-sizing:60px;
  float:middle;
}

button:hover{
    background: blue;
}


body {
background-color: white;

/* Smoothly transition the background color */
transition: background-color .5s;
}

/* Using flex with the column direction to
align items in a vertical direction */
.player {
height: 95vh;
display: flex;
align-items: center;
flex-direction: column;
justify-content: center;
}

.details {
display: flex;
align-items: center;
flex-direction: column;
justify-content: center;
margin-top: 25px;
}

.track-art {
margin: 25px;
height: 250px;
width: 250px;
background-image: URL(
    "https://source.unsplash.com/Qrspubmx6kE/640x360");
background-size: cover;
background-position: center;
border-radius: 15%;
}

/* Changing the font sizes to suitable ones */
.now-playing {
font-size: 1rem;
}

.track-name {
font-size: 3rem;
}

.track-artist {
font-size: 1.5rem;
}

/* Using flex with the row direction to
align items in a horizontal direction */
.buttons {
display: flex;
flex-direction: row;
align-items: center;
}

.playpause-track,
.prev-track,
.next-track {
padding: 25px;
opacity: 0.8;

/* Smoothly transition the opacity */
transition: opacity .2s;
}

/* Change the opacity when mouse is hovered */
.playpause-track:hover,
.prev-track:hover,
.next-track:hover {
opacity: 1.0;
}

/* Define the slider width so that it scales properly */
.slider_container {
width: 75%;
max-width: 400px;
display: flex;
justify-content: center;
align-items: center;
}

/* Modify the appearance of the slider */
.seek_slider, .volume_slider {
-webkit-appearance: none;
-moz-appearance: none;
appearance: none;
height: 5px;
background: black;
opacity: 0.7;
-webkit-transition: .2s;
transition: opacity .2s;
}

/* Modify the appearance of the slider thumb */
.seek_slider::-webkit-slider-thumb,
.volume_slider::-webkit-slider-thumb {
-webkit-appearance: none;
-moz-appearance: none;
appearance: none;
width: 15px;
height: 15px;
background: white;
cursor: pointer;
border-radius: 50%;
}

/* Change the opacity when mouse is hovered */
.seek_slider:hover,
.volume_slider:hover {
opacity: 1.0;
}

.seek_slider {
width: 60%;
}

.volume_slider {
width: 30%;
}

.current-time,
.total-duration {
padding: 10px;
}

i.fa-volume-down,
i.fa-volume-up {
padding: 10px;
}

/* Change the mouse cursor to a pointer
when hovered over */
i.fa-play-circle,
i.fa-pause-circle,
i.fa-step-forward,
i.fa-step-backward {
cursor: pointer;
}

</style>

</head>
<body>
<div class="player">

    <!-- Define the section for displaying details -->
    <div class="details">
    <div class="now-playing">PLAYING x OF y</div>
    <div class="track-art"></div>
    <div class="track-name">Track Name</div>
    <div class="track-artist">Track Artist</div>
    </div>

    <!-- Define the section for displaying track buttons -->
    <div class="buttons">
    <div class="prev-track" onclick="prevTrack()">
        <i class="fa fa-step-backward fa-2x"></i>
    </div>
    <div class="playpause-track" onclick="playpauseTrack()">
        <i class="fa fa-play-circle fa-5x"></i>
    </div>
    <div class="next-track" onclick="nextTrack()">
        <i class="fa fa-step-forward fa-2x"></i>
    </div>
    </div>

    <!-- Define the section for displaying the seek slider-->
    <div class="slider_container">
    <div class="current-time">00:00</div>
    <input type="range" min="1" max="100"
        value="0" class="seek_slider" onchange="seekTo()">
    <div class="total-duration">00:00</div>
    </div>

    <!-- Define the section for displaying the volume slider-->
    <div class="slider_container">
    <i class="fa fa-volume-down"></i>
    <input type="range" min="1" max="100"
        value="99" class="volume_slider" onchange="setVolume()">
    <i class="fa fa-volume-up"></i>
    </div>
</div>

<!-- Load the main script for the player -->
<script src="main.js"></script>

<script>
    
// Select all the elements in the HTML page
// and assign them to a variable
let now_playing = document.querySelector(".now-playing");
let track_art = document.querySelector(".track-art");
let track_name = document.querySelector(".track-name");
let track_artist = document.querySelector(".track-artist");

let playpause_btn = document.querySelector(".playpause-track");
let next_btn = document.querySelector(".next-track");
let prev_btn = document.querySelector(".prev-track");

let seek_slider = document.querySelector(".seek_slider");
let volume_slider = document.querySelector(".volume_slider");
let curr_time = document.querySelector(".current-time");
let total_duration = document.querySelector(".total-duration");

// Specify globally used values
let track_index = 0;
let isPlaying = false;
let updateTimer;

// Create the audio element for the player
let curr_track = document.createElement('audio');

// Define the list of tracks that have to be played
let track_list = [
{
    name: "ধুমগড়ের পিশাচ রহস্য",
    artist: "Broke For Free",
    image: "Image URL",
    path: "Sunday_Suspense.mp3"
},
{
    name: "অনাথ বাবুর ভয়",
    artist: "Tours",
    image: "Image URL",
    path: "Anath_Babur_Bhoy.mp3"
},
{
    name: "মানরো দ্বীপের রহস্য",
    artist: "Chad Crouch",
    image: "Image URL",
    path: "Manro_DeepEr_Rohossya.mp3",
},
];

function loadTrack(track_index) {
// Clear the previous seek timer
clearInterval(updateTimer);
resetValues();

// Load a new track
curr_track.src = track_list[track_index].path;
curr_track.load();

// Update details of the track
track_art.style.backgroundImage =
    "url(" + track_list[track_index].image + ")";
track_name.textContent = track_list[track_index].name;
track_artist.textContent = track_list[track_index].artist;
now_playing.textContent =
    "PLAYING " + (track_index + 1) + " OF " + track_list.length;

// Set an interval of 1000 milliseconds
// for updating the seek slider
updateTimer = setInterval(seekUpdate, 1000);

// Move to the next track if the current finishes playing
// using the 'ended' event
curr_track.addEventListener("ended", nextTrack);

// Apply a random background color
random_bg_color();
}

function random_bg_color() {
// Get a random number between 64 to 256
// (for getting lighter colors)
let red = Math.floor(Math.random() * 256) + 64;
let green = Math.floor(Math.random() * 256) + 64;
let blue = Math.floor(Math.random() * 256) + 64;

// Construct a color withe the given values
let bgColor = "rgb(" + red + ", " + green + ", " + blue + ")";

// Set the background to the new color
document.body.style.background = bgColor;
}

// Function to reset all values to their default
function resetValues() {
curr_time.textContent = "00:00";
total_duration.textContent = "00:00";
seek_slider.value = 0;
}

function playpauseTrack() {
// Switch between playing and pausing
// depending on the current state
if (!isPlaying) playTrack();
else pauseTrack();
}

function playTrack() {
// Play the loaded track
curr_track.play();
isPlaying = true;

// Replace icon with the pause icon
playpause_btn.innerHTML = '<i class="fa fa-pause-circle fa-5x"></i>';
}

function pauseTrack() {
// Pause the loaded track
curr_track.pause();
isPlaying = false;

// Replace icon with the play icon
playpause_btn.innerHTML = '<i class="fa fa-play-circle fa-5x"></i>';
}

function nextTrack() {
// Go back to the first track if the
// current one is the last in the track list
if (track_index < track_list.length - 1)
    track_index += 1;
else track_index = 0;

// Load and play the new track
loadTrack(track_index);
playTrack();
}

function prevTrack() {
// Go back to the last track if the
// current one is the first in the track list
if (track_index > 0)
    track_index -= 1;
else track_index = track_list.length - 1;
    
// Load and play the new track
loadTrack(track_index);
playTrack();
}

function seekTo() {
// Calculate the seek position by the
// percentage of the seek slider
// and get the relative duration to the track
seekto = curr_track.duration * (seek_slider.value / 100);

// Set the current track position to the calculated seek position
curr_track.currentTime = seekto;
}

function setVolume() {
// Set the volume according to the
// percentage of the volume slider set
curr_track.volume = volume_slider.value / 100;
}

function seekUpdate() {
let seekPosition = 0;

// Check if the current track duration is a legible number
if (!isNaN(curr_track.duration)) {
    seekPosition = curr_track.currentTime * (100 / curr_track.duration);
    seek_slider.value = seekPosition;

    // Calculate the time left and the total duration
    let currentMinutes = Math.floor(curr_track.currentTime / 60);
    let currentSeconds = Math.floor(curr_track.currentTime - currentMinutes * 60);
    let durationMinutes = Math.floor(curr_track.duration / 60);
    let durationSeconds = Math.floor(curr_track.duration - durationMinutes * 60);

    // Add a zero to the single digit time values
    if (currentSeconds < 10) { currentSeconds = "0" + currentSeconds; }
    if (durationSeconds < 10) { durationSeconds = "0" + durationSeconds; }
    if (currentMinutes < 10) { currentMinutes = "0" + currentMinutes; }
    if (durationMinutes < 10) { durationMinutes = "0" + durationMinutes; }

    // Display the updated duration
    curr_time.textContent = currentMinutes + ":" + currentSeconds;
    total_duration.textContent = durationMinutes + ":" + durationSeconds;
}
}

// Load the first track in the tracklist
loadTrack(track_index);


</script>

<button onclick="location.href='https://www.youtube.com/channel/UC4xK1SCP7tia6k9lynuXFaA'" type="button" style=" color:white; font-size: 50px; text-align: center;">SUBSCRIBE MY YOUTUBE CHANNEL</button>



</body>
</html>

<!--END MUSIC PLAYER-->

<br></br>

<!--SLIDESHOW-->

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
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
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
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
  .text {font-size: 11px}
}


h2{
    font-size: 80px;
    color: white;
}

</style>
</head>
<body>

<h2>DURGA PUJA 2021 SLIDESHOW</h2>
<p>Change image every 2 seconds:</p>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 6</div>
  <img src="puja2.jpeg" style="width:100%">
  <div class="text">Caption Text</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 6</div>
  <img src="puja6.jpeg" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 6</div>
  <img src="puja45.jpeg" style="width:100%">
  <div class="text">Caption Three</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 6</div>
  <img src="puja27.jpeg" style="width:100%">
  <div class="text">Caption Four</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 6</div>
  <img src="puja25.jpeg" style="width:100%">
  <div class="text">Caption Four</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 6</div>
  <img src="puja30.jpeg" style="width:100%">
  <div class="text">Caption Four</div>
</div>


</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>


</body>
</html> 


<!--END SLIDESHOW-->

<br></br>

<!--VIDEO-->
<!DOCTYPE html> 
<html> 
<body> 

<video width="950" height="450" controls>
  <source src="DUI_PRITHIBI.mp4" type="video/mp4">
  <source src="mov_bbb.ogg" type="video/ogg">
  Your browser does not support HTML video.
</video>

<br></br>

<h1 style="font-size:80px;">বক্রেশ্বর নদীর বান</h1>

<br></br>
<iframe src="RIVER1.jpg" width="1550px" height="1200px"></iframe>
  
<p>
Video courtesy of 
<a href="https://www.covid19india.org" target="_blank" style="background: black; color:white;">CLICK HERE TO SHOW CORONA UPDATE IN INDIA</a>.
</p>

<center style="font-size:25px;background:red"><u><a style="color:white;">Privacy Policy</a></u>&nbsp;<u><a style="color:white">Terms & Conditions</a></u></center>
<center style="font-size:25px;background:#17D4FE">Copyright &copy; By Pradipta Ghosh.com 2021</center>


</body> 
</html>


<!--END VIDEO-->
