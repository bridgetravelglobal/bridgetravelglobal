<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Bridge Travel Solutions | Travel, Jobs & Study Abroad Dubai</title>

<meta name="description" content="Bridge Travel Solutions based in Dubai offers flight booking, visa assistance, hotel reservations, jobs abroad support, and study abroad guidance." />

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #070707;
  color: white;
}

/* TOP BAR */
.topbar {
  background: #000;
  text-align: center;
  padding: 10px;
  font-size: 14px;
  color: #aaa;
  border-bottom: 1px solid #222;
}

/* HERO */
.hero {
  text-align: center;
  padding: 100px 20px;
  background: radial-gradient(circle at top, #1a1a1a, #000);
  border-bottom: 2px solid gold;
}

.hero img {
  width: 180px;
  margin-bottom: 15px;
  border-radius: 12px;
  box-shadow: 0 0 25px rgba(255,215,0,0.25);
}

.hero h1 {
  font-size: 48px;
  color: gold;
  margin-bottom: 10px;
}

.hero p {
  color: #ccc;
  font-size: 18px;
}

/* BUTTON */
.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 14px 26px;
  background: gold;
  color: black;
  font-weight: bold;
  border-radius: 50px;
  text-decoration: none;
  transition: 0.3s;
}

.btn:hover {
  background: #d4af37;
}

/* SECTIONS */
.container {
  max-width: 1100px;
  margin: auto;
  padding: 50px 20px;
}

h2 {
  color: gold;
  margin-bottom: 20px;
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: #141414;
  padding: 20px;
  border-radius: 12px;
  border: 1px solid #222;
  transition: 0.3s;
  cursor: pointer;
}

.card:hover {
  transform: translateY(-5px);
  border-color: gold;
}

/* SERVICE BOX */
#serviceBox {
  margin-top: 30px;
  color: #ccc;
  background: #111;
  padding: 25px;
  border-radius: 12px;
  border: 1px solid #222;
}

/* CONTACT LINKS */
.link {
  color: gold;
  text-decoration: none;
}

/* SOCIALS */
.socials {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-top: 15px;
}

.socials a {
  width: 45px;
  height: 45px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #141414;
  border: 1px solid #333;
  border-radius: 50%;
  text-decoration: none;
  font-size: 20px;
  color: white;
  transition: 0.3s;
}

.socials a:hover {
  border-color: gold;
  transform: translateY(-3px);
}

/* WHATSAPP FLOAT */
.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25D366;
  color: white;
  padding: 14px 18px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: bold;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 20px;
  color: #666;
  border-top: 1px solid #222;
}
</style>
</head>

<body>

<div class="topbar">
  Dubai Based Travel & Opportunity Agency
</div>

<!-- HERO -->
<div class="hero">

  <img src="logo.png" alt="Bridge Travel Solutions Logo" />

  <h1>Bridge Travel Solutions</h1>
  <p>Travel ✈️ | Jobs Abroad 🌍 | Study Opportunities 🎓</p>

  <a class="btn" href="https://wa.me/971583017066" target="_blank">
    Book on WhatsApp
  </a>

  <!-- SOCIALS -->
  <div class="socials">
    <a href="#" title="Instagram">📸</a>
    <a href="#" title="Facebook">📘</a>
    <a href="#" title="Twitter">🐦</a>
    <a href="https://www.tiktok.com/@bridgetravelglobal" target="_blank" title="TikTok">🎵</a>
  </div>

</div>

<!-- ABOUT -->
<div class="container">
  <h2>About Us</h2>
  <p style="color:#ccc; line-height:1.6;">
    Bridge Travel Solutions is a Dubai-based travel and opportunity agency helping people travel,
    study, and work abroad. We provide end-to-end support including documentation, bookings, and guidance.
  </p>
</div>

<!-- SERVICES -->
<div class="container">
  <h2>Our Services (Click to Learn More)</h2>

  <div class="grid">

    <div class="card" onclick="showService('flights')">✈️ Flight Booking</div>
    <div class="card" onclick="showService('visa')">🛂 Visa Assistance</div>
    <div class="card" onclick="showService('hotels')">🏨 Hotel Reservations</div>
    <div class="card" onclick="showService('jobs')">🌍 Jobs Abroad Support</div>
    <div class="card" onclick="showService('study')">🎓 Study Abroad Guidance</div>
    <div class="card" onclick="showService('travel')">📄 Travel Consultation</div>

  </div>

  <div id="serviceBox">
    Click a service above to see full details.
  </div>
</div>

<!-- CONTACT -->
<div class="container">
  <h2>Contact Us</h2>

  <div class="grid">

    <div class="card">
      📧 Email<br/>
      <a class="link" href="mailto:bridgetravelsolutionsglobal@gmail.com">
        bridgetravelsolutionsglobal@gmail.com
      </a>
    </div>

    <div class="card">
      📲 WhatsApp<br/>
      <a class="link" href="https://wa.me/971583017066">
        +971 58 301 7066
      </a>
    </div>

    <div class="card">
      🎵 TikTok<br/>
      <a class="link" href="https://www.tiktok.com/@bridgetravelglobal" target="_blank">
        @bridgetravelglobal
      </a>
    </div>

  </div>
</div>

<!-- WHY US -->
<div class="container">
  <h2>Why Choose Us</h2>

  <div class="grid">
    <div class="card">Fast & Reliable Support</div>
    <div class="card">Dubai-Based Agency</div>
    <div class="card">End-to-End Service</div>
    <div class="card">Trusted Guidance</div>
  </div>
</div>

<!-- CTA -->
<div class="container" style="text-align:center;">
  <h2>Start Your Journey Today</h2>

  <a class="btn" href="https://wa.me/971583017066" target="_blank">
    Chat on WhatsApp
  </a>
</div>

<!-- WHATSAPP FLOAT -->
<a class="whatsapp" href="https://wa.me/971583017066" target="_blank">
  WhatsApp
</a>

<!-- FOOTER -->
<footer>
  © 2026 Bridge Travel Solutions | Dubai
</footer>

<!-- SCRIPT -->
<script>
function showService(type) {
  let content = "";

  if (type === "flights") {
    content = "✈️ Flight Booking: We provide international and domestic flight booking support with the best available prices. We compare airlines, routes, and timings to give you the most affordable options. We assist with urgent bookings and flexible travel planning. Our team ensures smooth travel preparation and guidance on baggage rules. We make sure your journey is stress-free from booking to departure.";
  }

  if (type === "visa") {
    content = "🛂 Visa Assistance: We help with tourist, work, and study visa applications. We guide you through documentation, embassy requirements, and submission processes. Our support reduces errors and improves approval chances. We provide step-by-step assistance tailored to your destination. We stay updated with visa regulations for different countries.";
  }

  if (type === "hotels") {
    content = "🏨 Hotel Reservations: We help you book safe, comfortable, and affordable hotels worldwide. We match hotels based on your budget and location preferences. We ensure trusted and verified accommodation options. We assist with short-term and long-term stays. Our goal is to make your stay convenient and secure.";
  }

  if (type === "jobs") {
    content = "🌍 Jobs Abroad Support: We guide you in finding international job opportunities. We help with CV preparation and application processes. We connect candidates with verified opportunities. We provide interview and relocation guidance. Our goal is to support safe and legal employment abroad.";
  }

  if (type === "study") {
    content = "🎓 Study Abroad Guidance: We assist students in applying to international universities. We help with course selection, admissions, and documentation. We provide scholarship and visa guidance. We support you throughout the application journey. Our goal is to make studying abroad simple and achievable.";
  }

  if (type === "travel") {
    content = "📄 Travel Consultation: We provide personalized travel planning and advice. We help you understand requirements, costs, and destinations. We assist with itinerary planning and preparation. We guide first-time travelers step by step. Our aim is to make travel simple and well-organized.";
  }

  document.getElementById("serviceBox").innerHTML = content;
}
</script>

</body>
</html>
