<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Bridge Travel Solutions</title>

<style>
body{
margin:0;
font-family:Arial;
background:#050505;
color:white;
}

/* HEADER FIXED (NO BLUE FEEL) */
.header{
background:linear-gradient(90deg,#000,#111,#000);
text-align:center;
padding:12px;
border-bottom:1px solid gold;
color:#d6d6d6;
font-size:13px;
letter-spacing:1px;
}

/* HERO */
.hero{
position:relative;
padding:110px 20px;
text-align:center;
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
width:200px;
filter:drop-shadow(0 0 20px gold);
}

.hero h1{
font-size:52px;
color:gold;
margin:10px 0;
}

.hero p{
color:#ccc;
}

/* BUTTON */
.btn{
display:inline-block;
padding:14px 28px;
background:gold;
color:black;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

/* SOCIALS */
.socials{
display:flex;
justify-content:center;
gap:15px;
margin-top:20px;
}

.socials a{
position:relative;
width:45px;
height:45px;
display:flex;
align-items:center;
justify-content:center;
border-radius:50%;
background:#111;
border:1px solid #333;
text-decoration:none;
color:white;
}

/* TOOLTIP (NAME ON HOVER) */
.socials a span{
display:none;
position:absolute;
bottom:-30px;
background:#000;
color:gold;
padding:4px 8px;
font-size:11px;
border-radius:5px;
white-space:nowrap;
}

.socials a:hover span{
display:block;
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

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:20px;
}

/* CARD */
.card{
background:#111;
border:1px solid #222;
border-radius:15px;
overflow:hidden;
transition:0.3s;
cursor:pointer;
}

.card:hover{
transform:scale(1.03);
border-color:gold;
}

.card img{
width:100%;
height:170px;
object-fit:cover;
}

.card-content{
padding:15px;
}

.card-content h3{
color:gold;
margin:0;
}

/* SERVICE BOX */
#serviceBox{
margin-top:20px;
padding:20px;
background:#111;
border-radius:12px;
border:1px solid #222;
color:#ccc;
line-height:1.6;
}

/* FOOTER */
footer{
text-align:center;
padding:20px;
color:#777;
border-top:1px solid #222;
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

<div class="header">
BRIDGE TRAVEL SOLUTIONS • DUBAI BASED TRAVEL AGENCY
</div>

<!-- HERO -->
<div class="hero">
<div class="hero-content">

<img src="logo.png">

<h1>Bridge Travel Solutions</h1>
<p>Travel ✈️ | Jobs 🌍 | Study 🎓 | Global Support</p>

<a class="btn" href="https://wa.me/971583017066">Start Now</a>

<!-- SOCIALS -->
<div class="socials">

<a href="#"><span>Instagram</span>📸</a>
<a href="#"><span>Facebook</span>📘</a>
<a href="#"><span>Twitter</span>🐦</a>
<a href="https://www.tiktok.com/@bridgetravelglobal" target="_blank"><span>TikTok</span>🎵</a>

</div>

</div>
</div>

<!-- ABOUT US (RESTORED + 10 SENTENCES) -->
<div class="container">
<h2>About Us</h2>

<p style="color:#ccc; line-height:1.7;">
Bridge Travel Solutions is a Dubai-based travel and opportunity agency dedicated to connecting people with global opportunities. We specialize in travel services, visa assistance, job abroad support, and international education guidance. Our mission is to simplify global mobility for individuals and families. We work with trusted partners across different countries to ensure safe and reliable services. We assist clients from the first inquiry until the completion of their journey. Our team focuses on transparency, guidance, and fast response times. We understand that every client has unique goals and we tailor our services accordingly. We are committed to making international travel accessible and stress-free. We continuously update our knowledge of travel regulations and opportunities worldwide. Our vision is to become a trusted global bridge between people and opportunities abroad.
</p>
</div>

<!-- SERVICES -->
<div class="container">
<h2>Our Services</h2>

<div class="grid">

<div class="card" onclick="showService('flights')">
<img src="https://images.unsplash.com/photo-1436491865332-7a61a109cc05">
<div class="card-content"><h3>Flight Booking</h3></div>
</div>

<div class="card" onclick="showService('visa')">
<img src="https://images.unsplash.com/photo-1508780709619-79562169bc64">
<div class="card-content"><h3>Visa Assistance</h3></div>
</div>

<div class="card" onclick="showService('jobs')">
<img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d">
<div class="card-content"><h3>Jobs Abroad</h3></div>
</div>

<div class="card" onclick="showService('study')">
<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f">
<div class="card-content"><h3>Study Abroad</h3></div>
</div>

<div class="card" onclick="showService('pickup')">
<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70">
<div class="card-content"><h3>Airport Pick-up</h3></div>
</div>

<div class="card" onclick="showService('tour')">
<img src="https://images.unsplash.com/photo-1526779259212-939e64788e3c">
<div class="card-content"><h3>City Tours</h3></div>
</div>

</div>

<div id="serviceBox">
Click a service to view full details.
</div>
</div>

<!-- FOOTER -->
<footer>
© 2026 Bridge Travel Solutions | Dubai UAE
</footer>

<a class="whatsapp" href="https://wa.me/971583017066">WhatsApp</a>

<!-- SCRIPT -->
<script>
function showService(type){

let content="";

if(type==="flights"){
content="We provide international flight booking with best price comparisons, airline selection support, and travel planning assistance for individuals and families.";
}

if(type==="visa"){
content="We assist with tourist, work, and study visa applications including document preparation, embassy guidance, and step-by-step support.";
}

if(type==="jobs"){
content="We connect clients to verified job opportunities abroad and provide CV preparation, application support, and relocation guidance.";
}

if(type==="study"){
content="We guide students to international universities, assist with admissions, scholarships, and student visa applications.";
}

if(type==="pickup"){
content="We offer airport pick-up services in Dubai ensuring safe, comfortable, and reliable transportation from airport to destination.";
}

if(type==="tour"){
content="We provide guided city tours in Dubai including landmark visits, cultural experiences, and customized travel routes.";
}

document.getElementById("serviceBox").innerHTML = content;
}
</script>

</body>
</html>
