<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Bridge Travel Solutions | Travel, Jobs & Study Abroad</title>

<style>
body{
margin:0;
font-family:Arial;
background:#050505;
color:white;
overflow-x:hidden;
}

/* NAV */
nav{
display:flex;
justify-content:center;
gap:25px;
padding:15px;
background:#000;
border-bottom:1px solid gold;
position:sticky;
top:0;
z-index:1000;
}

nav a{
color:#ccc;
text-decoration:none;
font-size:14px;
}

nav a:hover{color:gold;}

/* HERO */
.hero{
position:relative;
text-align:center;
padding:120px 20px;
background:url('https://images.unsplash.com/photo-1502920917128-1aa500764ce7') center/cover;
}

.hero::before{
content:"";
position:absolute;
inset:0;
background:rgba(0,0,0,0.75);
}

.hero-content{
position:relative;
max-width:900px;
margin:auto;
animation:fadeIn 1.2s ease-in;
}

.hero img{
width:170px;
margin-bottom:10px;
}

.hero h1{
color:gold;
font-size:48px;
margin:10px 0;
}

.hero p{
color:#ccc;
font-size:16px;
line-height:1.6;
}

.btn{
display:inline-block;
margin-top:20px;
padding:14px 28px;
background:gold;
color:black;
border-radius:50px;
text-decoration:none;
font-weight:bold;
transition:0.3s;
}

.btn:hover{
transform:scale(1.05);
}

/* TRUST NUMBERS SECTION */
.stats-section{
position:relative;
background:url('https://images.unsplash.com/photo-1526779259212-939e64788e3c') center/cover;
padding:80px 20px;
text-align:center;
}

.stats-section::before{
content:"";
position:absolute;
inset:0;
background:rgba(0,0,0,0.8);
}

.stats-content{
position:relative;
max-width:1000px;
margin:auto;
}

.stats{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
margin-top:20px;
}

.stat{
background:rgba(255,255,255,0.05);
border:1px solid #333;
padding:20px 25px;
border-radius:12px;
font-size:18px;
font-weight:bold;
color:gold;
min-width:180px;
transition:0.3s;
}

.stat:hover{
transform:translateY(-5px);
}

/* SECTION */
.container{
max-width:1100px;
margin:auto;
padding:60px 20px;
}

h2{
color:gold;
text-align:center;
margin-bottom:30px;
}

/* ABOUT */
.about-wrap{
display:flex;
flex-wrap:wrap;
gap:20px;
align-items:center;
background:#111;
padding:20px;
border-radius:12px;
border:1px solid #222;
}

.about-wrap img{
width:100%;
max-width:400px;
border-radius:10px;
}

.about-text{
flex:1;
color:#ccc;
line-height:1.7;
}

.small-btn{
display:inline-block;
margin-top:15px;
padding:10px 18px;
background:gold;
color:black;
border-radius:30px;
text-decoration:none;
font-weight:bold;
font-size:13px;
}

/* SERVICES */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:20px;
}

.card{
background:#111;
border-radius:12px;
border:1px solid #222;
overflow:hidden;
transition:0.3s;
}

.card:hover{
transform:scale(1.03);
}

.card img{
width:100%;
height:160px;
object-fit:cover;
}

.card-content{
padding:15px;
}

.card h3{
color:gold;
margin:0;
}

.card p{
color:#ccc;
font-size:14px;
line-height:1.5;
}

/* READ MORE BUTTON */
.readmore{
display:inline-block;
margin-top:10px;
padding:8px 14px;
background:gold;
color:black;
border-radius:20px;
font-size:12px;
font-weight:bold;
text-decoration:none;
}

/* CTA */
.cta{
text-align:center;
padding:50px 20px;
background:#111;
border-top:1px solid gold;
border-bottom:1px solid gold;
}

/* FOOTER */
footer{
text-align:center;
padding:20px;
color:#777;
}

/* ANIMATION */
@keyframes fadeIn{
from{opacity:0; transform:translateY(20px);}
to{opacity:1; transform:translateY(0);}
}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
padding:14px 18px;
border-radius:50px;
color:white;
text-decoration:none;
}
</style>
</head>

<body>

<!-- NAV -->
<nav>
<a href="index.html">Home</a>
<a href="about.html">About</a>
<a href="services.html">Services</a>
<a href="gallery.html">Gallery</a>
<a href="contact.html">Contact</a>
</nav>

<!-- HERO -->
<div class="hero">
<div class="hero-content">

<img src="logo.png">

<h1>Bridge Travel Solutions</h1>

<p>
We connect people to global travel, jobs, and education opportunities through trusted guidance and end-to-end support.
</p>

<a class="btn" href="contact.html">Start Your Journey</a>

</div>
</div>

<!-- STATS -->
<div class="stats-section">

<div class="stats-content">

<h2>Trusted by Clients Across Borders</h2>

<div class="stats">

<div class="stat">100+ Clients Assisted</div>
<div class="stat">Global Travel Support</div>
<div class="stat">Visa & Job Guidance</div>
<div class="stat">Fast Response Service</div>

</div>

</div>
</div>

<!-- ABOUT -->
<div class="container">
<h2>About Us</h2>

<div class="about-wrap">

<img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d">

<div class="about-text">
Bridge Travel Solutions was created from real-life travel experience and the challenges faced when moving across countries.
The founder, an African traveler, experienced difficulties accessing reliable travel, visa, and job information abroad.
This inspired the creation of a support system that helps others travel, work, and study internationally with confidence.
We provide step-by-step guidance and trusted connections to make global opportunities easier to access.

<br><br>

<a class="small-btn" href="about.html">Read More About Us</a>
</div>

</div>
</div>

<!-- SERVICES -->
<div class="container">
<h2>Our Services</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1436491865332-7a61a109cc05">
<div class="card-content">
<h3>Flight Booking</h3>
<p>Affordable international flights with flexible travel options.</p>
<a class="readmore" href="services.html">Read More</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1508780709619-79562169bc64">
<div class="card-content">
<h3>Visa Assistance</h3>
<p>Full support for travel, work, and study visa applications.</p>
<a class="readmore" href="services.html">Read More</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d">
<div class="card-content">
<h3>Jobs Abroad</h3>
<p>Verified job opportunities and relocation guidance.</p>
<a class="readmore" href="services.html">Read More</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f">
<div class="card-content">
<h3>Study Abroad</h3>
<p>University admissions, scholarships, and student visas.</p>
<a class="readmore" href="services.html">Read More</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70">
<div class="card-content">
<h3>Airport Pick-up</h3>
<p>Safe and reliable airport transfer services in Dubai.</p>
<a class="readmore" href="services.html">Read More</a>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1526779259212-939e64788e3c">
<div class="card-content">
<h3>City Tours</h3>
<p>Guided Dubai tours and customized travel experiences.</p>
<a class="readmore" href="services.html">Read More</a>
</div>
</div>

</div>
</div>

<!-- CTA -->
<div class="cta">
<h2>Ready to Start Your Journey?</h2>
<p style="color:#ccc;">Let’s help you move, travel, and grow globally with confidence.</p>
<a class="btn" href="contact.html">Contact Us on WhatsApp</a>
</div>

<footer>
© 2026 Bridge Travel Solutions | Dubai UAE
</footer>

<a class="whatsapp" href="https://wa.me/971583017066">WhatsApp</a>

</body>
</html>
