<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Bridge Travel Solutions</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #070707;
  color: white;
}

/* HERO */
.hero {
  text-align: center;
  padding: 90px 20px;
  background: radial-gradient(circle at top, #1a1a1a, #000);
  border-bottom: 2px solid gold;
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
}

.card:hover {
  transform: translateY(-5px);
  border-color: gold;
}

/* LINKS */
.link {
  color: gold;
  text-decoration: none;
}

.link:hover {
  text-decoration: underline;
}

/* FLOATING WHATSAPP */
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

<!-- HERO -->
<div class="hero">

  <img src="logo.png" alt="Logo"
       style="width:130px; margin-bottom:15px;
              border-radius:12px;
              box-shadow:0 0 20px rgba(255,215,0,0.3);" />

  <h1>Bridge Travel Solutions</h1>
  <p>Travel ✈️ | Jobs Abroad 🌍 | Study Opportunities 🎓</p>

  <a class="btn" href="https://wa.me/971583017066" target="_blank">
    Book on WhatsApp
  </a>

</div>

<!-- ABOUT -->
<div class="container">
  <h2>About Us</h2>
  <p style="color:#ccc; line-height:1.6;">
    We are a Dubai-based travel and opportunity agency helping people travel, work, and study abroad.
    We provide full end-to-end support including documentation, bookings, and placement guidance.
  </p>
</div>

<!-- SERVICES -->
<div class="container">
  <h2>Our Services</h2>

  <div class="grid">
    <div class="card">✈️ Flight Booking</div>
    <div class="card">🛂 Visa Assistance</div>
    <div class="card">🏨 Hotel Reservations</div>
    <div class="card">🌍 Jobs Abroad Support</div>
    <div class="card">🎓 Study Abroad Guidance</div>
    <div class="card">📄 Travel Consultation</div>
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
      <a class="link" href="https://wa.me/971583017066" target="_blank">
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

<!-- FLOATING WHATSAPP -->
<a class="whatsapp" href="https://wa.me/971583017066" target="_blank">
  WhatsApp
</a>

<!-- FOOTER -->
<footer>
  © 2026 Bridge Travel Solutions | Dubai
</footer>

</body>
</html>
