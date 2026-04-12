<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bridge Travel Solutions | Dubai Travel Agency</title>

<style>
body{
margin:0;
font-family:Arial;
background:#050505;
color:white;
}

/* NAV */
nav{
display:flex;
justify-content:center;
gap:25px;
padding:15px;
background:#000;
border-bottom:1px solid gold;
}

nav a{
color:#ccc;
text-decoration:none;
font-size:14px;
}

nav a:hover{
color:gold;
}

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
}

.hero img{
width:180px;
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

/* CARDS */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:20px;
}

.card{
background:#111;
padding:20px;
border-radius:12px;
border:1px solid #222;
text-align:center;
}

.card h3{
color:gold;
}

/* CTA STRIP */
.cta{
text-align:center;
padding:40px 20px;
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
<p>Your trusted partner for Travel, Jobs & Study Abroad</p>

<a class="btn" href="https://wa.me/971583017066">
Start Your Journey
</a>

</div>
</div>

<!-- SERVICES -->
<div class="container">
<h2>Our Services</h2>

<div class="grid">
<div class="card">
<h3>✈️ Flight Booking</h3>
<p>Affordable international flights with best routes and airlines.</p>
</div>

<div class="card">
<h3>🛂 Visa Assistance</h3>
<p>Complete visa support for travel, work and study abroad.</p>
</div>

<div class="card">
<h3>🌍 Jobs Abroad</h3>
<p>Access verified job opportunities and relocation guidance.</p>
</div>

<div class="card">
<h3>🎓 Study Abroad</h3>
<p>University applications, scholarships and student visas.</p>
</div>
</div>
</div>

<!-- WHY -->
<div class="container">
<h2>Why Choose Us</h2>

<div class="grid">
<div class="card">✔ Dubai Based Agency</div>
<div class="card">✔ Trusted Global Network</div>
<div class="card">✔ Fast Response</div>
<div class="card">✔ End-to-End Support</div>
</div>
</div>

<!-- CTA -->
<div class="cta">
<h2>Ready to Start Your Journey?</h2>
<a class="btn" href="https://wa.me/971583017066">Contact Us on WhatsApp</a>
</div>

<footer>
© 2026 Bridge Travel Solutions | Dubai UAE
</footer>

<a class="whatsapp" href="https://wa.me/971583017066">WhatsApp</a>

</body>
</html>
