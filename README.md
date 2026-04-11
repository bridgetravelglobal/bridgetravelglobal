<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Bridge Travel Solutions</title>

<meta name="description" content="Dubai-based travel agency for flights, visas, jobs abroad and study opportunities." />

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #070707;
  color: white;
}

/* HEADER */
.header {
  background: linear-gradient(90deg, #000, #111, #000);
  padding: 15px;
  text-align: center;
  border-bottom: 1px solid gold;
  font-size: 14px;
  color: #ccc;
}

/* HERO */
.hero {
  text-align: center;
  padding: 100px 20px;
  background: url('https://images.unsplash.com/photo-1502920917128-1aa500764ce7') center/cover;
  position: relative;
}

.hero::after {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.75);
}

.hero-content {
  position: relative;
}

.hero img {
  width: 180px;
  margin-bottom: 15px;
}

.hero h1 {
  color: gold;
  font-size: 48px;
}

.hero p {
  color: #ccc;
}

/* BUTTON */
.btn {
  display: inline-block;
  padding: 14px 26px;
  background: gold;
  color: black;
  border-radius: 50px;
  text-decoration: none;
  font-weight: bold;
}

/* SECTIONS */
.container {
  padding: 50px 20px;
  max-width: 1100px;
  margin: auto;
}

h2 {
  color: gold;
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
  gap: 20px;
}

/* CARDS */
.card {
  background: #141414;
  padding: 20px;
  border-radius: 12px;
  border: 1px solid #222;
  cursor: pointer;
}

.card:hover {
  border-color: gold;
}

/* SERVICE BOX */
#serviceBox {
  margin-top: 20px;
  padding: 20px;
  background: #111;
  border-radius: 10px;
}

/* SOCIAL ICONS */
.socials {
  margin-top: 20px;
  display: flex;
  justify-content: center;
  gap: 15px;
}

.socials a {
  width: 45px;
  height: 45px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px solid #333;
  border-radius: 50%;
  background: #111;
}

.socials svg {
  width: 20px;
  fill: white;
}

/* WHATSAPP */
.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25D366;
  color: white;
  padding: 12px 16px;
  border-radius: 50px;
  text-decoration: none;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 20px;
  color: #777;
}
</style>
</head>

<body>

<div class="header">
  Dubai-Based Travel & Opportunity Agency
</div>

<!-- HERO -->
<div class="hero">
  <div class="hero-content">
    <img src="logo.png" />
    <h1>Bridge Travel Solutions</h1>
    <p>Travel ✈️ | Jobs Abroad 🌍 | Study Opportunities 🎓</p>

    <a class="btn" href="https://wa.me/971583017066">Book on WhatsApp</a>

    <!-- SOCIAL ICONS -->
    <div class="socials">

      <!-- Instagram -->
      <a href="#"><svg viewBox="0 0 24 24"><path d="M7 2C4 2 2 4 2 7v10c0 3 2 5 5 5h10c3 0 5-2 5-5V7c0-3-2-5-5-5H7zm5 5a5 5 0 110 10 5 5 0 010-10zm6-2a1 1 0 110 2 1 1 0 010-2z"/></svg></a>

      <!-- Facebook -->
      <a href="#"><svg viewBox="0 0 24 24"><path d="M13 3h4v4h-4v14h-5V7H5V3h3V1h5v2z"/></svg></a>

      <!-- Twitter -->
      <a href="#"><svg viewBox="0 0 24 24"><path d="M22 5.8c-.8.3-1.6.6-2.5.7.9-.6 1.5-1.4 1.8-2.4-.9.5-1.8.9-2.8 1.1A4.5 4.5 0 0015.5 4c-2.5 0-4.5 2-4.5 4.5 0 .4 0 .8.1 1.1C7.7 9.4 5 7.8 3.2 5.3c-.4.6-.6 1.4-.6 2.2 0 1.5.8 2.8 2 3.6-.7 0-1.3-.2-1.9-.5v.1c0 2.1 1.5 3.9 3.5 4.3-.4.1-.8.2-1.2.2-.3 0-.6 0-.8-.1.6 1.7 2.2 3 4.2 3A9 9 0 012 19.5 12.7 12.7 0 008.9 21c8.3 0 12.8-6.9 12.8-12.8v-.6c.9-.6 1.6-1.3 2.2-2.1z"/></svg></a>

      <!-- TikTok -->
      <a href="https://www.tiktok.com/@bridgetravelglobal" target="_blank">
        <svg viewBox="0 0 24 24"><path d="M12 2h3a5 5 0 005 5v3a8 8 0 01-5-2v7a6 6 0 11-6-6c.3 0 .7 0 1 .1v3a3 3 0 103 3V2z"/></svg>
      </a>

    </div>
  </div>
</div>

<!-- SERVICES -->
<div class="container">
  <h2>Our Services</h2>

  <div class="grid">
    <div class="card" onclick="showService('flights')">✈️ Flights</div>
    <div class="card" onclick="showService('visa')">🛂 Visa</div>
    <div class="card" onclick="showService('jobs')">🌍 Jobs</div>
    <div class="card" onclick="showService('study')">🎓 Study</div>
  </div>

  <div id="serviceBox">
    Click a service to view details.
  </div>
</div>

<!-- FOOTER -->
<footer>
  © 2026 Bridge Travel Solutions
</footer>

<a class="whatsapp" href="https://wa.me/971583017066">WhatsApp</a>

<script>
function showService(type) {
  let text = "Professional service with full support from start to finish. We guide you step by step, ensure all requirements are met, and provide trusted assistance tailored to your needs.";

  document.getElementById("serviceBox").innerHTML = text;
}
</script>

</body>
</html>
