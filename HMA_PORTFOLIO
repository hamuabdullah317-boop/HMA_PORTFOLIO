<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HAFIZ MUHAMMAD ABDULLAH | Official</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">

<style>

/* ===== GLOBAL ===== */
*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Poppins',sans-serif;
}

body{
background:#0f2027;
color:white;
overflow-x:hidden;
transition:0.4s;
}

body.light{
background:#f4f4f4;
color:black;
}

/* ===== PRELOADER ===== */
#preloader{
position:fixed;
width:100%;
height:100%;
background:black;
display:flex;
justify-content:center;
align-items:center;
z-index:9999;
}

.loader{
width:50px;
height:50px;
border:5px solid #00f7ff;
border-top:5px solid transparent;
border-radius:50%;
animation:spin 1s linear infinite;
}

@keyframes spin{
100%{transform:rotate(360deg);}
}

/* ===== PROGRESS BAR ===== */
#progress{
position:fixed;
top:0;
left:0;
height:4px;
background:#00f7ff;
width:0%;
z-index:2000;
}

/* ===== NAVBAR ===== */
nav{
position:fixed;
width:100%;
top:0;
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 20px;
background:rgba(0,0,0,0.7);
backdrop-filter:blur(10px);
z-index:1000;
}

.logo{
font-weight:800;
font-size:16px;
letter-spacing:2px;
}

nav ul{
display:flex;
list-style:none;
gap:15px;
}

nav ul li a{
color:white;
text-decoration:none;
font-size:14px;
position:relative;
}

nav ul li a::after{
content:"";
position:absolute;
left:0;
bottom:-5px;
width:0%;
height:2px;
background:#00f7ff;
transition:0.4s;
}

nav ul li a:hover::after{
width:100%;
}

/* ===== DARK MODE BUTTON ===== */
.toggle{
cursor:pointer;
background:#00f7ff;
border:none;
padding:5px 10px;
border-radius:20px;
font-size:12px;
}

/* ===== HERO ===== */
.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
url('https://images.unsplash.com/photo-1498050108023-c5249f4df085') center/cover;
animation:bgSlide 10s infinite alternate;
}

@keyframes bgSlide{
0%{background-position:center;}
100%{background-position:top;}
}

.hero h1{
font-size:22px;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{text-shadow:0 0 10px #00f7ff;}
to{text-shadow:0 0 25px #00ff88;}
}

.typing{
color:#00f7ff;
margin-top:10px;
font-size:14px;
}

/* ===== BUTTON ===== */
.btn{
margin-top:20px;
padding:8px 20px;
border-radius:25px;
border:none;
background:linear-gradient(45deg,#00f7ff,#00ff88);
color:black;
cursor:pointer;
transition:0.4s;
}

.btn:hover{
transform:scale(1.1);
}

/* ===== SECTION ===== */
section{
padding:70px 20px;
text-align:center;
}

.section-title{
margin-bottom:30px;
font-size:20px;
}

/* ===== CARDS ===== */
.cards{
display:grid;
grid-template-columns:1fr;
gap:20px;
}

.card{
background:rgba(255,255,255,0.05);
padding:20px;
border-radius:15px;
backdrop-filter:blur(8px);
box-shadow:0 0 20px rgba(0,255,255,0.3);
transition:0.4s;
}

.card:hover{
transform:translateY(-8px) scale(1.03);
box-shadow:0 0 30px rgba(0,255,255,0.7);
}

/* ===== COUNTER ===== */
.counter{
font-size:25px;
color:#00f7ff;
}

/* ===== CONTACT ===== */
.contact{
background:rgba(0,0,0,0.7);
padding:20px;
border-radius:15px;
box-shadow:0 0 20px #00f7ff;
}

/* ===== SOCIAL ===== */
.social{
margin-top:15px;
}

.social a{
color:#00f7ff;
margin:0 10px;
font-size:20px;
transition:0.3s;
}

.social a:hover{
color:#00ff88;
transform:scale(1.3);
}

/* ===== WHATSAPP FLOAT ===== */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:12px;
border-radius:50%;
font-size:20px;
text-decoration:none;
box-shadow:0 0 15px #25D366;
}

/* ===== MOBILE ===== */
@media(max-width:768px){
nav ul{
display:none;
}
}

</style>
</head>
<body>

<div id="preloader"><div class="loader"></div></div>
<div id="progress"></div>

<nav>
<div class="logo">HAFIZ MUHAMMAD ABDULLAH</div>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
<button class="toggle" onclick="toggleMode()">Mode</button>
</nav>

<div class="hero" id="home">
<h1>HAFIZ MUHAMMAD ABDULLAH</h1>
<div class="typing" id="typing"></div>
<button class="btn">Explore</button>
</div>

<section id="about">
<h2 class="section-title">About Me</h2>
<div class="cards">
<div class="card">
<p>I am a Professional Developer, Digital Creator and Islamic Content Creator. I build VIP professional websites and digital solutions.</p>
</div>
</div>
</section>

<section id="services">
<h2 class="section-title">My Services</h2>
<div class="cards">
<div class="card"><h3>Web Development</h3></div>
<div class="card"><h3>Branding</h3></div>
<div class="card"><h3>Content Creation</h3></div>
</div>
</section>

<section>
<h2 class="section-title">Achievements</h2>
<div class="counter" id="counter">0</div>
</section>

<section id="contact">
<h2 class="section-title">Contact</h2>
<div class="contact">
<p><strong>Name:</strong> HAFIZ MUHAMMAD ABDULLAH</p>
<p><strong>Phone:</strong> 0312 6746161</p>
<p><strong>Email:</strong> info.hafiz1555@email.com</p>
<div class="social">
<a href="#">🌐</a>
<a href="#">📘</a>
<a href="#">📸</a>
</div>
</div>
</section>

<a href="https://wa.me/923126746161" class="whatsapp">💬</a>

<script>

/* PRELOADER */
window.onload = function(){
document.getElementById("preloader").style.display="none";
}

/* SCROLL PROGRESS */
window.onscroll = function(){
let winScroll = document.body.scrollTop || document.documentElement.scrollTop;
let height = document.documentElement.scrollHeight - document.documentElement.clientHeight;
let scrolled = (winScroll / height) * 100;
document.getElementById("progress").style.width = scrolled + "%";
}

/* DARK MODE */
function toggleMode(){
document.body.classList.toggle("light");
}

/* TYPING EFFECT */
let text = "Professional Developer | Digital Creator | Islamic Content Creator";
let i=0;
function typing(){
if(i<text.length){
document.getElementById("typing").innerHTML+=text.charAt(i);
i++;
setTimeout(typing,50);
}
}
typing();

/* COUNTER */
let count=0;
let target=500;
let counter=document.getElementById("counter");
let interval=setInterval(()=>{
if(count<target){
count+=5;
counter.innerHTML=count+"+ Projects";
}else{
clearInterval(interval);
}
},50);

</script>

</body>
</html>
