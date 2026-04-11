<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Bridge Travel Solutions | Dubai Travel Agency</title>

<style>
body{
margin:0;
font-family:Arial;
background:#050505;
color:white;
}

/* HEADER */
.header{
text-align:center;
padding:10px;
background:#000;
border-bottom:1px solid gold;
color:#aaa;
font-size:13px;
}

/* HERO VIDEO */
.hero{
position:relative;
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
overflow:hidden;
}

.hero video{
position:absolute;
top:0;
left:0;
width:100%;
height:100%;
object-fit:cover;
}

.overlay{
position:absolute;
inset:0;
background:rgba(0,0,0,0.7);
}

.hero-content{
position:relative;
z-index:2;
}

.hero img{
width:200px;
filter:drop-shadow(0 0 20px gold);
}

.hero h1{
font-size:55px;
color:gold;
margin:10px 0;
}

.hero p{
color:#ccc;
font-size:18px;
}

.btn{
display:inline-block;
margin-top:20px;
padding:15px 30px;
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
margin-bottom:20px;
}

/* GRID CARDS */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:20px;
}

.card{
background:#111;
border:1px solid #222;
border-radius:15px;
overflow:hidden;
transition:0.3s;
}

.card:hover{
transform:scale(1.03);
border-color:gold;
}

.card img{
width:100%;
height:180px;
object-fit:cover;
}

.card-content{
padding:15px;
}

.card-content h3{
color:gold;
margin:0;
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

/* FOOTER */
footer{
text-align:center;
padding:20px;
color:#777;
border-top:1px solid #222;
}
</style>
</head>

<body>

<div class="header">
Dubai Based Travel • Jobs • Study Abroad Agency
</div>

<!-- HERO VIDEO SECTION -->
<div class="hero">

<!-- Dubai skyline video -->
<video autoplay muted loop>
<source src="https://cdn.coverr.co/videos/coverr-dubai-skyline-4437/1080p.mp4" type="video/mp4">
</video>

<div class="overlay"></div>

<div class="hero-content">

<img src="logo.png">

<h1>Bridge Travel Solutions</h1>
<p>We connect you to the world — Travel ✈️ | Jobs 🌍 | Study 🎓</p>

<a class="btn" href="https://wa.me/971583017066">Start Your Journey</a>

</div>
</div>

<!-- SERVICES -->
<div class="container">

<h2>Our Premium Services</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1436491865332-7a61a109cc05">
<div class="card-content">
<h3>Flight Booking</h3>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1508780709619-79562169bc64">
<div class="card-content">
<h3>Visa Assistance</h3>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f">
<div class="card-content">
<h3>Study Abroad</h3>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d">
<div class="card-content">
<h3>Jobs Abroad</h3>
</div>
</div>

</div>
</div>

<!-- WHY US -->
<div class="container">
<h2>Why Choose Us</h2>

<div class="grid">

<div class="card">
<div class="card-content">
<h3>Dubai Based Agency</h3>
<p>Trusted local support with global reach.</p>
</div>
</div>

<div class="card">
<div class="card-content">
<h3>End-to-End Support</h3>
<p>We handle everything from booking to guidance.</p>
</div>
</div>

<div class="card">
<div class="card-content">
<h3>Fast Response</h3>
<p>Instant WhatsApp communication.</p>
</div>
</div>

</div>
</div>

<!-- CTA -->
<div class="container" style="text-align:center;">
<h2>Start Your Journey Today</h2>
<a class="btn" href="https://wa.me/971583017066">Contact Us</a>
</div>

<footer>
© 2026 Bridge Travel Solutions | Dubai UAE
</footer>

<a class="whatsapp" href="https://wa.me/971583017066">WhatsApp</a>

</body>
</html>
