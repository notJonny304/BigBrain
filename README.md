

<!DOCTYPE html>
<html>
<head>
      <link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
     <link href="fonts.googleapis.com" rel="stylesheet">
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
     <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Spectral">
          <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Orbitron">
           <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Space Mono">
            <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sekuya">
      <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Geologica"> 
      <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lora">
 <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Crimson Text"><style>
:root {
  --color: var(--yellow-5);
  --shadow: var(--yellow-8);
  --glare: hsl(0 0% 100% / 0.75);
  --font-size: var(--font-size-fluid-3);
  --transition: 0.2s;
}

* {
  box-sizing: border-box;
}
body {font-family: Georgia, ARial}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-image: url(https://images.unsplash.com/photo-1659469377768-4f42f2f091c5?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8ZGFyayUyMGdyYWRpZW50fGVufDB8fDB8fHww&fm=jpg&q=60&w=3000);
}

/* Style the buttons inside the tab */
.tab button {
  background-color: black;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
  color:#39FF14
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: orange;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: red;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
   -webkit-animation: fadeEffect 1s;
  animation: fadeEffect 1s;

}
@-webkit-keyframes fadeEffect {
transition: opacity 0.5s ease-in-out; /* Smooth transition for opacity */
    position: absolute; /* Position all content in the same spot for seamless transition */
    padding: 20px;
    border: 1px solid #ccc
}

@keyframes fadeEffect {
  from {opacity: .8;}
  to {opacity: 1;}
}
.btn {
  background-color: black;
  border: none;
  color: white;
  padding: 5px 13px;
  text-align: center;
  font-size: 16px;
  margin: 4px 2px;
  opacity: 0.7;
  transition: 0.3s;
  color:#FF007F

  
}
.btn:hover {opacity: 1.2;   transform: scale(1.1);}
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
.glow {
  font-size: 80px;
  color: #fff;
  text-align: center;
  animation: glow 1s ease-in-out infinite alternate;
}

@-webkit-keyframes glow {
  from {
    text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #e60073, 0 0 40px #e60073, 0 0 50px #e60073, 0 0 60px #e60073, 0 0 70px #e60073;
  }
  
  to {
    text-shadow: 0 0 20px #fff, 0 0 30px #ff4da6, 0 0 40px #ff4da6, 0 0 50px #ff4da6, 0 0 60px #ff4da6, 0 0 70px #ff4da6, 0 0 80px #ff4da6;
  }
}
.neon-text {
    font-size: 4rem;
    color: #fff;
    text-shadow: 0 0 5px #ff005e, 0 0 10px #ff005e, 0 0 20px #ff005e, 0 0 40px #ff005e, 0 0 80px #ff005e;
    animation: glow 1.5s infinite alternate;
}

@keyframes glow {
    0% {
        text-shadow: 0 0 5px #ff005e, 0 0 10px #ff005e, 0 0 20px #ff005e, 0 0 40px #ff005e, 0 0 80px #ff005e;
    }
    100% {
        text-shadow: 0 0 10px #00d4ff, 0 0 20px #00d4ff, 0 0 40px #00d4ff, 0 0 80px #00d4ff, 0 0 160px #00d4ff;
    }
}
.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
    position: relative;
}

.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
   position: relative;
}

.dropdown-content a:hover {
  background-color: #ddd;

    position: relative;
}

.dropdown:hover .dropdown-content {
  display: block;
    position: absolute;
  
}
.glow-on-hover {
    width: 220px;
    height: 50px;
    border: none;
    outline: none;
    color: #fff;
    background: #111;
    cursor: pointer;
    position: relative;
    z-index: 0;
    border-radius: 10px;
}

.glow-on-hover:before {
    content: '';
    background: linear-gradient(45deg, #ff0000, #ff7300, #fffb00, #48ff00, #00ffd5, #002bff, #7a00ff, #ff00c8, #ff0000);
    position: absolute;
    top: -2px;
    left:-2px;
    background-size: 400%;
    z-index: -1;
    filter: blur(5px);
    width: calc(100% + 4px);
    height: calc(100% + 4px);
    animation: glowing 20s linear infinite;
    opacity: 0;
    transition: opacity .3s ease-in-out;
    border-radius: 10px;
}

.glow-on-hover:active {
    color: #000
}

.glow-on-hover:active:after {
    background: transparent;
}

.glow-on-hover:hover:before {
    opacity: 1;
}

.glow-on-hover:after {
    z-index: -1;
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background: #111;
    left: 0;
    top: 0;
    border-radius: 10px;
}

@keyframes glowing {
    0% { background-position: 0 0; }
    50% { background-position: 400% 0; }
    100% { background-position: 0 0; }
}
.rain {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: repeating-linear-gradient(
    0deg,
    rgba(0, 255, 0, 0.1) 0,
    rgba(0, 255, 0, 0.2) 2px,
    transparent 4px
  );
  animation: rain 10s linear infinite;
  z-index: 1; /* Place it behind the text */
}

/* Animation for the rain effect */
@keyframes rain {
  0% {
    transform: translateY(-100%);
  }
  100% {
    transform: translateY(100%);
  }
}

/* Glitch effect for the text */
.hover-underline {
  font-size: 2rem;
  color: #ffffff;
  position: relative;
  display: inline-block;
}

.hover-underline::after,
.hover-underline::before {
  content: '';
  position: absolute;
  width: 100%;
  height: 2px;
  background: linear-gradient(to right, #ff0000, #00ffff);
  bottom: -5px;
  left: 0;
  transform: scaleX(0);
  transform-origin: right;
  transition: transform 0.4s ease-out;
}

.hover-underline::before {
  top: -5px;
  transform-origin: left;
}

.hover-underline:hover::after,
.hover-underline:hover::before {
  transform: scaleX(1);
}
.container {
	width: 100%;
	height: 100%;
	display: grid;
	place-items: center;
	overflow: hidden;
}

.title {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
}
.title h1 {
	font-size: 25vmin;
	font-weight: 900;
	font-family: "Montserrat", sans-serif;
	color: black;
}


main {
  transition: all 0.5s;
  -webkit-text-stroke: 4px #d6f4f4;
  font-variation-settings: "wght" 900, "ital" 1;
  font-size: 15rem;
  text-align: center;
  color: transparent;
  font-family: "Meta", sans-serif;
  text-shadow: 10px 10px 0px #07bccc,
    15px 15px 0px #e601c0,
    20px 20px 0px #e9019a,
    25px 25px 0px #f40468,
    45px 45px 10px #482896;
  cursor: pointer;
}

main:hover {
  font-variation-settings: "wght" 100, "ital" 0;
  text-shadow: none;
}
.notJonny {
    background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background for content */
    padding: 20px;
    border-radius: 8px;
    text-align: center;
}
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
.glitch-button {
  position: relative;
  background-color: #333;
  color: #fff;
  padding: 15px 30px;
  font-family: 'Arial', sans-serif;
  font-size: 24px;
  border: none;
  overflow: hidden; /* Hide overflowing pseudo-elements */
  cursor: pointer;
}

.glitch-button span {
  position: relative;
  z-index: 2; /* Ensure text is above glitch layers */
}

/* Pseudo-elements for glitch effect */
.glitch-button::before,
.glitch-button::after {
  content: 'Click Me'; /* Duplicate button text */
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #333; /* Match button background */
  color: #ff00ff; /* Glitch color 1 (e.g., magenta) */
  overflow: hidden;
  clip-path: inset(0 0 0 0); /* Initially fully visible */
}

.glitch-button::after {
  color: #00ffff; /* Glitch color 2 (e.g., cyan) */
}

/* Glitch animation on hover */
.glitch-button:hover::before {
  animation: glitch-before 0.4s infinite alternate;
}

.glitch-button:hover::after {
  animation: glitch-after 0.4s infinite alternate;
}

/* Keyframe animations for glitch effect */
@keyframes glitch-before {
  0% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
  20% {
    transform: translate(-2px, 2px);
    clip-path: inset(10% 0 10% 0);
  }
  40% {
    transform: translate(2px, -2px);
    clip-path: inset(20% 0 20% 0);
  }
  60% {
    transform: translate(-1px, 1px);
    clip-path: inset(30% 0 30% 0);
  }
  80% {
    transform: translate(1px, -1px);
    clip-path: inset(40% 0 40% 0);
  }
  100% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
}

@keyframes glitch-after {
  0% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
  25% {
    transform: translate(3px, -3px);
    clip-path: inset(5% 0 5% 0);
  }
  50% {
    transform: translate(-3px, 3px);
    clip-path: inset(15% 0 15% 0);
  }
  75% {
    transform: translate(2px, -2px);
    clip-path: inset(25% 0 25% 0);
  }
  100% {
    transform: translate(0, 0);
    clip-path: inset(0 0 0 0);
  }
}
.futuristic-button {
  background-color: #1a1a2e; /* Dark background */
  color: #e0e0e0; /* Light text color */
  border: none;
  padding: 15px 30px;
  font-size: 18px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  cursor: pointer;
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 255, 255, 0.5); /* Initial subtle glow */
  transition: all 0.3s ease;
}

.futuristic-button::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(0, 255, 255, 0.3), transparent);
  transition: all 0.7s ease;
}

.futuristic-button:hover {
  box-shadow: 0 0 20px rgba(0, 255, 255, 0.8), 0 0 40px rgba(0, 255, 255, 0.6); /* Enhanced glow on hover */
  transform: translateY(-2px); /* Slight lift on hover */
}

.futuristic-button:hover::before {
  left: 100%; /* Animate gradient across the button */
}

.futuristic-button:active {
  transform: translateY(0); /* Return to original position on click */
  box-shadow: 0 0 10px rgba(0, 255, 255, 0.5);
}
.neon-green-text {
  font-family: 'Arial Black', sans-serif; /* Choose a bold, impactful font */
  font-size: 60px;
  color: #00ff00; /* Bright neon green base color */
  text-align: center;
  text-shadow:
    0 0 5px #00ff00,    /* Inner, subtle glow */
    0 0 10px #00ff00,   /* Medium glow */
    0 0 20px #00ff00,   /* Stronger glow */
    0 0 40px #00ff00;   /* Widest, most diffused glow */
}
#container {
  color:#999;
  text-transform: uppercase;
  font-size:36px;
  font-weight:bold;
  padding-top:200px;  
  position:fixed;
  width:100%;
  bottom:45%;
  display:block;
}

#flip {
  height:50px;
  overflow:hidden;
}

#flip > div > div {
  color:#fff;
  padding:4px 12px;
  height:45px;
  margin-bottom:45px;
  display:inline-block;
}

#flip div:first-child {
  animation: show 5s linear infinite;
}

#flip div div {
  background:#42c58a;
}
#flip div:first-child div {
  background:#4ec7f3;
}
#flip div:last-child div {
  background:#DC143C;
}

@keyframes show {
  0% {margin-top:-270px;}
  5% {margin-top:-180px;}
  33% {margin-top:-180px;}
  38% {margin-top:-90px;}
  66% {margin-top:-90px;}
  71% {margin-top:0px;}
  99.99% {margin-top:0px;}
  100% {margin-top:-270px;}
}
.loading-bar-container {
  width: 100%;
  height: 10px;
  background-color: #f0f0f0;
  border-radius: 5px;
  overflow: hidden; /* Hide overflow for the progress bar */
  display: none; /* Initially hide the loading bar */
}

.loading-bar {
  height: 100%;
  width: 0%; /* Start with 0% width */
  background-color: #4CAF50; /* Green color for the progress */
  border-radius: 5px;
  transition: width 0.5s ease-in-out; /* Smooth transition for width changes */
}

/* Optional: Add a class for active loading state */
.loading-active .loading-bar-container {
  display: block; /* Show the loading bar when active */
}
.matrix-container {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    z-index: 2; /* Ensure it stays above the rain effect */
}

.matrix-text {
    color: #0f0;
    font-size: 70px; /* Changed to 70px */
    font-family: 'Courier New', monospace; /* Changed to Courier New */
    position: relative;
    text-shadow: 0 0 10px #0f0, 0 0 20px #0f0, 0 0 30px #0f0;
    z-index: 2; /* Ensure it stays above the rain effect */
}

.matrix-text::before {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    animation: glitch 2s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
    transform: translate(-2px, -2px);
    color: #0f0;
    text-shadow: 0 0 5px #0f0, 0 0 15px #0f0;
}

.rain {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: transparent; /* Ensures no background for the rain effect itself */
    animation: rain 10s linear infinite;
    z-index: 1; /* Place it behind the text */
}

/* Animation for the rain effect */
@keyframes rain {
    0% { transform: translateY(-100%); }
    100% { transform: translateY(100%); }
}

/* Glitch effect for the text */
@keyframes glitch {
    0%, 100% {
        clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
        transform: translate(0);
    }
    33% {
        clip-path: polygon(0 0, 100% 0, 100% 15%, 0 15%);
        transform: translate(-5px, -5px);
    }
    66% {
        clip-path: polygon(0 85%, 100% 85%, 100% 100%, 0 100%);
        transform: translate(5px, 5px);
    }
}
.neon-pink-text {
  font-family: 'Arial', sans-serif; /* Or a suitable neon-style font */
  font-size: 3em; /* Adjust size as needed */
  color: #fff; /* Base text color, white for a bright glow */
  text-shadow: 
    0 0 5px #ff00ff, /* Bright pink glow */
    0 0 10px #ff00ff,
    0 0 20px #ff00ff,
    0 0 40px #ff00ff,
    0 0 80px #ff00ff,
    0 0 90px #ff00ff; /* Deeper glow */
  animation: neonGlow 1.5s ease-in-out infinite alternate; /* Animation details */
}

@keyframes neonGlow {
  from {
    text-shadow: 
      0 0 5px #ff00ff, 
      0 0 10px #ff00ff, 
      0 0 20px #ff00ff, 
      0 0 40px #ff00ff;
  }
  to {
    text-shadow: 
      0 0 10px #ff00ff, 
      0 0 20px #ff00ff, 
      0 0 40px #ff00ff, 
      0 0 80px #ff00ff, 
      0 0 90px #ff00ff,
      0 0 100px #ff00ff;
  }
}
.glowin.blue.and.black {
    /* Set the text color and background */
    color: #fff; /* White text for contrast */
    background-color: #000; /* Black background as requested */
    font-family: 'Arial', sans-serif; /* Example font, 'Satisfy' font would need to be linked */
    font-size: 72px; /* Large font size */
    text-align: center;
    padding: 20px;
    
    /* Apply the blue glowing effect */
    text-shadow: 
        0 0 10px #00bfff,  /* Inner glow */
        0 0 20px #00bfff,  /* Medium glow */
        0 0 30px #00bfff,  /* Outer glow */
        0 0 40px #00bfff,
        0 0 50px #00bfff,
        0 0 60px #00bfff,
        0 0 70px #00bfff;
}
.neon-green-text {
    color: #39ff14; /* Bright neon green for the text */
    font-size: 5em;
    text-align: center;
    text-shadow:
        0 0 7px #39ff14,   /* Inner glow */
        0 0 10px #39ff14,  /* Medium glow */
        0 0 21px #39ff14,  /* Larger glow */
        0 0 42px #0f0,     /* Wider, slightly different shade of green for depth */
        0 0 82px #0f0,
        0 0 92px #0f0,
        0 0 102px #0f0,
        0 0 151px #0f0;
}
.glitch-text {
  position: relative;
  font-family: 'monospace', sans-serif; /* Use a monospace or futuristic font */
  color: #fff;
}

.glitch-text::before,
.glitch-text::after {
  content: attr(data-text); /* Use data-text attribute for content */
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.glitch-text::before {
  left: 2px;
  text-shadow: -2px 0 #ff00c1; /* Red glitch */
  animation: glitch-anim-1 2s infinite alternate-reverse;
}

.glitch-text::after {
  left: -2px;
  text-shadow: 2px 0 #00ffff; /* Cyan glitch */
  animation: glitch-anim-2 2s infinite alternate-reverse;
}

@keyframes glitch-anim-1 {
  0% { transform: translate(0); }
  20% { transform: translate(-2px, 2px); }
  40% { transform: translate(-2px, -2px); }
  60% { transform: translate(2px, 2px); }
  80% { transform: translate(2px, -2px); }
  100% { transform: translate(0); }
}

@keyframes glitch-anim-2 {
  0% { transform: translate(0); }
  20% { transform: translate(2px, -2px); }
  40% { transform: translate(2px, 2px); }
  60% { transform: translate(-2px, -2px); }
  80% { transform: translate(-2px, 2px); }
  100% { transform: translate(0); }
}
.awesome-buzz-effect {
    position: relative;
    font-family: monospace; /* Glitch effects often work well with techy/mono fonts */
    font-size: 4rem;
    color: white;
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #FF00FF, 0 0 20px #FF00FF; /* Optional neon glow */
    animation: buzz-animation 1s infinite alternate; /* Main buzz/shake */
}

/* Create distorted layers with pseudo-elements */
.awesome-buzz-effect::before,
.awesome-buzz-effect::after {
    content: attr(class="awesome-buzz-effect"); /* Use the text content */
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: transparent;
    overflow: hidden;
}

.awesome-buzz-effect::before {
    left: 2px;
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #00FFFF, 0 0 20px #00FFFF;
    clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%); /* Clip to top third */
    animation: buzz-top 1s infinite alternate-reverse;
}

.awesome-buzz-effect::after {
    left: -2px;
    text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #FF00FF, 0 0 20px #FF00FF;
    clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%); /* Clip to bottom third */
    animation: buzz-bottom 1.5s infinite alternate-reverse;
}

/* Main shake animation */
@keyframes buzz-animation {
    0%, 100% {
        transform: translateX(0);
    }
    10% {
        transform: translateX(-1px);
    }
    90% {
        transform: translateX(1px);
    }
}

/* Top layer distortion */
@keyframes buzz-top {
    0% {
        transform: translate(0, 0);
    }
    100% {
        transform: translate(5px, -5px);
    }
}

/* Bottom layer distortion */
@keyframes buzz-bottom {
    0% {
        transform: translate(0, 0);
    }
    100% {
        transform: translate(-5px, 5px);
    }
}
.hologram-container {
  position: relative;
  perspective: 1000px;
}

.hologram-text {
  font-family: 'Courier New', monospace;
  font-size: 4rem;
  font-weight: bold;
  color: #0ff;
  text-shadow: 
    0 0 10px #0ff,
    0 0 20px #0ff,
    0 0 30px #0ff;
  animation: float 3s ease-in-out infinite alternate;
  position: relative;
  z-index: 2;
}

.hologram-glitch {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: 
    linear-gradient(0deg, transparent 45%, rgba(0, 255, 255, 0.2) 50%, transparent 55%),
    linear-gradient(90deg, transparent 45%, rgba(0, 255, 255, 0.2) 50%, transparent 55%);
  background-size: 10px 10px;
  animation: glitch 0.5s linear infinite;
  opacity: 0.7;
  z-index: 1;
}

/* Scan lines */
.hologram-container::before {
  content: '';
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
 

  pointer-events: none;
}

@keyframes float {
  0% { transform: translateY(0) rotateX(20deg); }
  100% { transform: translateY(-20px) rotateX(20deg); }
}

@keyframes glitch {
  0% { background-position: 0 0; }
  100% { background-position: 20px 20px; }
}

.matrix-container {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    z-index: 2; /* Ensure it stays above other elements if any */
}

.matrix-text {
    color: #0f0;
    font-size: 80px;
    font-family: monospace;
    position: relative;
    text-shadow: 0 0 10px #0f0, 0 0 20px #0f0, 0 0 30px #0f0;
    z-index: 2; /* Ensure it stays above other elements if any */
}

.matrix-text::before {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    animation: glitch 2s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
    transform: translate(-2px, -2px);
    color: #0f0;
    text-shadow: 0 0 5px #0f0, 0 0 15px #0f0;
}

/* Glitch effect for the text */
@keyframes glitch {
    0%, 100% {
        clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
        transform: translate(0);
    }
    33% {
        clip-path: polygon(0 0, 100% 0, 100% 15%, 0 15%);
        transform: translate(-5px, -5px);
    }
    66% {
        clip-path: polygon(0 85%, 100% 85%, 100% 100%, 0 100%);
        transform: translate(5px, 5px);
    }
}
section {
  width: 100%;
  max-width: 2400px;   
  height: 100vh;
  margin: 100vh auto 0;
  display: flex;
  flex-direction: column;
}
section:nth-child(odd) {
  align-items: flex-end;
}
section:first-child {
  margin-top: 30vh;
}
.text-wrapper {
  margin: 6rem 4rem;
  padding: 1px;
  width: 100%;
  max-width: 1000px;   
  position: sticky;
  top: 6rem;
}
.fade-from-left{
  background: 
    linear-gradient(to top left, transparent 50%, var(--text-color) 60%, var(--text-color) 0) left bottom 25vh / 100vw 30vh fixed no-repeat,
    linear-gradient(to top, transparent 55%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}  
.fade-from-top{
  background: 
    linear-gradient(to top, transparent 27%,  var(--text-color) 40%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}  
.fade-from-right{
  background: 
    linear-gradient(to top right, transparent 50%, var(--text-color) 60%, var(--text-color) 0) left bottom 25vh / 100vw 30vh fixed no-repeat,
    linear-gradient(to top, transparent 55%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
} 

.fade-from-top-dots{
  background: 
    url('data:image/svg+xml,%3Csvg xmlns="http://www.w3.org/2000/svg" width="4" height="4" viewBox="0 0 4 4"%3E%3Cpath fill="%23ffffff" fill-opacity="0.8" d="M1 3h1v1H1V3zm2-2h1v1H3V1z"%3E%3C/path%3E%3C/svg%3E'),
    linear-gradient(to top, transparent 27%,  var(--text-color) 40%, var(--text-color) 0) left bottom 0vh / 100vw 100vh fixed no-repeat;
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
} 
.ywwqjowihojqdnw{
  width: 35px;
  height: 5px;
  background-color: black;
  margin: 6px 0;
}
</style>
</head>
<body>


<div class="tab" style="height:50px">
  <button class="tablinks" onclick="openCity(event, 'Homepage')" id=defaultOpen >
<i class="material-icons" style="font-size:17px;">home</i><span style="margin-left:4px;position:relative;top:-3px">Homepage</span></button>
   <button class="tablinks" onclick="openCity(event, 'Profiles') "style="position:relative;top:-3px">
<i class='fas fa-user-circle'></i><span style="margin-left:4px">Profiles</span></button>
  <button class="tablinks" onclick="openCity(event, 'myJourney')" style="position:relative;top:-3px" ><span><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-globe" viewBox="0 0 16 16">
  <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8m7.5-6.923c-.67.204-1.335.82-1.887 1.855A8 8 0 0 0 5.145 4H7.5zM4.09 4a9.3 9.3 0 0 1 .64-1.539 7 7 0 0 1 .597-.933A7.03 7.03 0 0 0 2.255 4zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a7 7 0 0 0-.656 2.5zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5zM8.5 5v2.5h2.99a12.5 12.5 0 0 0-.337-2.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5zM5.145 12q.208.58.468 1.068c.552 1.035 1.218 1.65 1.887 1.855V12zm.182 2.472a7 7 0 0 1-.597-.933A9.3 9.3 0 0 1 4.09 12H2.255a7 7 0 0 0 3.072 2.472M3.82 11a13.7 13.7 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5zm6.853 3.472A7 7 0 0 0 13.745 12H11.91a9.3 9.3 0 0 1-.64 1.539 7 7 0 0 1-.597.933M8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855q.26-.487.468-1.068zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.7 13.7 0 0 1-.312 2.5m2.802-3.5a7 7 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7 7 0 0 0-3.072-2.472c.218.284.418.598.597.933M10.855 4a8 8 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4z"style="position:relative;top:5px"style/>
</svg><span style="margin-left:4px">My Journey</span></span></button>
  <button class="tablinks" onclick="openCity(event, 'Paris')" style="position:relative;top:-3px" >   <span class="material-icons" style="font-size:19px;position:relative; top:4px">desktop_windows</span><span style="margin-left:4px">My Awesome Project Pool</span></button>
  <button class="tablinks" onclick="openCity(event,'Info')" style="position:relative;top:-3px"> About Us</button>
     

</div>
  
<div id="Homepage" class="tabcontent" style="height:450px;background-image: url(data:image/jpeg;base64,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)">
<h1 class="neon-text" style="font-size:40px;font-family:Courier New;text-align:center;font-weight:550">
notJonny's Awesome HTML Site</h1>





<h2
style="Color: White;font-family:Courier New;font-size:25px;text-align:center;font-weight:550">


Not sure what to explore on this website? Here are some ideas!






</h2>
<p> 
   
 <div class="row">
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7auMssyLgJgUwqBew8nYRY_RoABxwamYgSw&s" width="180" height="132" alt="Google Logo" alt="Snow" style="width:100%;height:200px">
  </div>
  <div class="column">
    <img src="data:image/jpeg;base64,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" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="data:image/jpeg;base64,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" alt="Mountains" style="height:200px">
  </div>
  </div>

  <a href="https://docs.google.com/document/d/1oWycSjjtCSOlB0_-A8_8fTs5N6a6dH8CexyUJWZkL1Q/edit?tab=t.0"><button class="btn" style="font-size:23px;width:300px;margin-left:15px;height:50px;"><span style="color:#FF007F;border-radius: 8px; padding: 10px 20px;">My Awesome Stories</span>   </button></a><a href="https://sites.google.com/students.wcpss.net/the-deviant-studio"><button class="btn" style="margin-left:17px;font-size:23px;width:300px;height:50px;color:#FF007F"><span>Our Google Site!</span></button></a><a href="https://www.youtube.com/@thegenius334"><button class="btn" style="font-size:19px;width:340px;margin-left:18px;height:50px;"><span style="color:#FF007F;border-radius: 8px; padding: 10px 20px;">My Friend's Youtube Channel!</span>   </button></a></div>
<div id="myJourney" class="tabcontent"  style="background-image: url(data:image/jpeg;base64,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);
background-attachment:fixed">

    <div class="notJonny">
<main style="font-style:oblique;font-size:80px">My Journey</main>
</div>
 
  
  <h2 style="color:#0096FF;font-family:Crimson Text;font-size:30px;font-weight:950px ">Chapter One: The Start of My Writing Addiction 
  </h2>
  <p style=" color:white; font-size:19px; font-family:Spectral;position:relative; top:-15px"><br> I started writing stories online in 4th Grade. Before, I only used the computer for gaming or occasionally writing essays for school. I had wrote a few short stories on paper, but without the help of a computer, my stories didn't go very far. This all changed, however, when I went to a writing camp over the summer after 3rd Grade with my friend Vincent. There, I was introduced to typing stories on a computer. I remember coming up with a character named Wyatt Plague. It was about a nerdy kid who's dad kept on making him excersize. He was invited to join a battalion that belonged to a differenmt multiverese, provided he complete a quest. He meets Willow, a knowledgeble girl who knows about the different dimensions and helps his quest. I'm not going to spoil more than that, but   </p>
</div>
<div id="Profiles" class="tabcontent">
  
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>

<div id="Paris" class="tabcontent" style="background-image:url(https://media.istockphoto.com/id/865457032/vector/abstract-futuristic-cyberspace-with-binary-code-matrix-background-with-digits-well-organized.jpg?s=612x612&w=0&k=20&c=IQcdedY8fn_DMq6nwc5MaHUBe0H0d5DPyibHR8J2usk=)">
<div class="notJonny">
<main style="font-style:oblique;font-size:90px;background-color:transparent">MY PROJECTS</main>
</div>
    <ul style="color:white">
<button class="glow-on-hover" type="button"  onclick="scrollToElement('section1')"style="height:45px; font-size:21.6px;width:280px;font-family:Courier New">AWESOME STORIES!</button> <button class="glow-on-hover" type="button"  onclick="scrollToElement('section2')"style="height:48px; font-size:21.6px;width:280px;font-family:Courier New">COOL WEBITES!</button>
<button class="glow-on-hover" type="button"  onclick="scrollToElement('section3')"style="height:48px; font-size:21.6px;width:280px;font-family:Courier New">HTML WEBSITES!</button>
        <li>Amazing Canva Creations (including a Canva Site!)</li>
        <li>Cool Coded Creations (Not Just Webites) </li>
    </ul>
    



<br><br><br><br><br><br><br><br><br>
<div id="section1" style="height:500px; background-image: url(data:image/jpeg;base64,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);background-repeat: no-repeat; background-size: cover; height:800px;">

  <div class="hologram-container">
  <div class="hologram-text" style="background-color: transparent;text-align:center;font-size:60px;position-relative;top:60px;">Awesome Stories</div>
<p style="color:white;font-family:Spectral;font-size:21px;position:relative;top:60px">
Some of Deviant Studios' largest projects are our stories. All of our members have either edited or wrote a story. Some of the Story Creators are notJonny, who created notJonny's Awesome Stories, theGenius9, the owner of theGenius9's Horrible STori</p>
</div></div>
<div id="section2" style="height:1000px;">
HELLO

</div>
<div id="section3" style="height:1000px;background-image:url(data:image/jpeg;base64,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);background-size: cover; background-position: center; background-repeat: no-repeat;">
  <div class="hologram-container"  style="background-color: transparent">
  <div class="hologram-text" style="background-color: transparent;text-align:center;font-size:63px;position-relative;top:22px;">HTML Sites</div>
<p style="color:white;font-family:Spectral;font-size:20px;text-indent:18px">
I started coding HTML when</p>
</div></div>

</div>
<div id="Info" class="tabcontent" style="background-image:url(data:image/jpeg;base64,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)">
HI
<div class="notJonny">
<main style="font-style:oblique;font-size:100px">ABOUT US</main>
</div>

<h1>
HIII
</h1>
<div class="matrix-container">
    <div class="matrix-text" data-text="How to Join">How to Join</div><div class="rain"></div>
</div><h1 class="neon-green-text" style="text-align:center;font-size:27px;font-weight:normal;font-family:Courier New;position: relative; top: -90px;">To Join, Contact the Founders or Fill out this Google Form!</h1>
    <h1 class="glitch-text" data-text="Want Cool CSS Effects Like These?">Want Cool CSS Effects Like These?
<div class="container">
    <h1 class="awesome-buzz-effect">Awesome Buzz Effect</h1>
   <h1> Credits: Thank you to Ashish Ranjan for the Floating Holographic Blue text effects in the tab, "My Awesome Project Pool". Thank you to Emadamerho Nefe for the Neon Green Matrix Text Animation and the Neon Blue and Red Text effects. Thank you to Gayane Gasparyan for the text effect I used for the headers I used for Info,My Projects, and My Journey.
  </h1>
<section>
<div class="text-wrapper" style="--text-color: #fff; ">
  <h1 class="fade-from-left;"style="margin-left:-50px">Asset uploading is a PRO feature</h1>
  <p class="fade-from-left" style="width: 2000px; margin-left:-50px">As a PRO member, you can drag-and-drop upload files here to use as resources. Images, Libraries, JSON data... anything you want. You can even edit them anytime, like any other code on CodePen.</p>
</div>  
</section>
<section>
<p>
  
  
  
  
  </p>
</section>

</section>
</h1>
</body>


<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
document.getElementById("defaultOpen").click();
 function scrollToElement(elementId) {
    const targetElement = document.getElementById(elementId);
    if (targetElement) {
        targetElement.scrollIntoView({
            behavior: 'smooth', // Optional: for smooth scrolling
            block: 'start'      // Aligns the top of the element with the top of the viewport
        });
    }
}
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
   

</html> 

































