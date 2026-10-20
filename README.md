<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#0756b9">

<title>Fast2Fix Service Centre | Home Appliance Repair & Service</title>

<meta name="description" content="Fast2Fix Service Centre provides home appliance repair, AC service, refrigerator repair, washing machine repair, LED TV repair, microwave, geyser and RO service. Contact us for service enquiries and home visits.">

<meta name="keywords" content="Fast2Fix Service Centre, AC Repair Near Me, AC Service, Refrigerator Repair, Washing Machine Repair, LED TV Repair, Microwave Repair, Geyser Repair, RO Repair, Home Appliance Repair">

<meta name="robots" content="index,follow">

<style>
:root {
  --blue: #0756b9;
  --dark: #092447;
  --red: #e52b35;
  --light: #f3f7fc;
  --text: #26364a;
  --white: #ffffff;
}

* {
  box-sizing: border-box; 
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 80px;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  background: #fff;
  color: var(--text);
  line-height: 1.65;
}

a {
  text-decoration: none;
}

button, input, select, textarea {
  font: inherit;
}

.container {
  width: min(1120px, 92%);
  margin: auto;
}

header {
  background: #fff;
  position: sticky;
  top: 0;
  z-index: 100;
  box-shadow: 0 3px 18px #09244712;
}

.navbar {
  min-height: 76px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 18px;
  flex-wrap: wrap;
  padding: 12px 0;
}

.logo {
  font-size: 26px;
  font-weight: 900;
  letter-spacing: -.8px;
  color: var(--blue);
  line-height: 1.15;
}

.logo span {
  color: var(--red);
}

.logo small {
  display: block;
  font-size: 12px;
  color: var(--dark);
  letter-spacing: 2px;
  margin-top: 4px;
}

nav {
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}

nav a {
  font-size: 14px;
  font-weight: 700;
  color: var(--dark);
}

nav a:hover {
  color: var(--red);
}

.btn {
  display: inline-flex;
  justify-content: center;
  align-items: center;
  gap: 8px;
  background: var(--red);
  color: #fff;
  border: 0;
  border-radius: 7px;
  padding: 12px 20px;
  font-weight: 800;
  cursor: pointer;
  transition: .2s;
}

.btn:hover {
  transform: translateY(-2px);
  filter: brightness(.96);
}

.btn-blue {
  background: var(--blue);
}

.hero {
  background: linear-gradient(120deg, #061e3e, #0756b9);
  color: #fff;
  padding: 85px 0;
  overflow: hidden;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.2fr .8fr;
  gap: 42px;
  align-items: center;
}

.eyebrow {
  display: inline-block;
  border: 1px solid #ffffff60;
  border-radius: 30px;
  padding: 6px 13px;
  font-size: 12px;
  font-weight: 800;
  letter-spacing: 1px;
  margin-bottom: 20px;
}

.hero h1 {
  font-size: clamp(34px, 5vw, 57px);
  line-height: 1.12;
  letter-spacing: -1.5px;
  margin-bottom: 20px;
}

.hero h1 span {
  color: #ff5962;
}

.hero p {
  color: #e0eaf8;
  font-size: 17px;
  max-width: 600px;
  margin-bottom: 25px;
}

.hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.btn-outline {
  border: 1px solid #ffffff80;
  background: transparent;
}

.hero-card {
  background: #fff;
  color: var(--dark);
  padding: 28px;
  border-radius: 16px;
  box-shadow: 0 20px 50px #0002;
}

.hero-card h2 {
  font-size: 23px;
  margin-bottom: 10px;
}

.hero-card p {
  color: #64748b;
  font-size: 14px;
  margin-bottom: 15px;
}

.hero-card ul {
  list-style: none;
}

.hero-card li {
  padding: 10px 0;
  border-bottom: 1px solid #e8eef6;
  font-weight: 700;
  font-size: 14px;
}

.hero-card li:last-child {
  border: 0;
}

.check {
  color: #13834b;
  font-weight: 900;
  margin-right: 9px;
}

.stats {
  background: #fff;
  box-shadow: 0 8px 30px #0924470b;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  text-align: center;
}

.stat {
  padding: 24px 12px;
  border-right: 1px solid #e8edf4;
}

.stat:last-child {
  border: 0;
}

.stat strong {
  display: block;
  color: var(--blue);
  font-size: 18px;
}

.stat span {
  font-size: 13px;
  color: #65748a;
}

section {
  padding: 75px 0;
}

.section-heading {
  text-align: center;
  max-width: 700px;
  margin: 0 auto 38px;
}

.section-heading .tag {
  color: var(--red);
  font-weight: 900;
  text-transform: uppercase;
  letter-spacing: 1.5px;
  font-size: 12px;
}

.section-heading h2 {
  color: var(--dark);
  font-size: clamp(27px, 4vw, 38px);
  line-height: 1.2;
  margin: 10px 0 13px;
}

.section-heading p {
  color: #64748b;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.service-card {
  border: 1px solid #e6edf6;
  border-radius: 12px;
  padding: 24px;
  background: #fff;
  transition: .2s;
}

.service-card:hover {
  border-color: #9dc5f7;
  box-shadow: 0 12px 30px #0756b910;
  transform: translateY(-3px);
}

.service-icon {
  width: 53px;
  height: 53px;
  display: grid;
  place-items: center;
  background: #eaf3ff;
  border-radius: 12px;
  font-size: 27px;
  margin-bottom: 17px;
}

.service-card h3 {
  color: var(--dark);
  font-size: 18px;
  margin-bottom: 8px;
}

.service-card p {
  color: #64748b;
  font-size: 14px;
  margin-bottom: 15px;
}

.text-link {
  color: var(--blue);
  font-weight: 800;
  font-size: 14px;
}

.soft {
  background: var(--light);
}

.why-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 18px;
}

.why-card {
  background: #fff;
  border-radius: 10px;
  padding: 22px;
  border: 1px solid #e7edf5;
}

.why-card h3 {
  color: var(--dark);
  font-size: 17px;
  margin-bottom: 6px;
}

.why-card p {
  font-size: 14px;
  color: #64748b;
}

.areas-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 12px;
}

.area {
  background: #fff;
  border: 1px solid #e2eaf5;
  border-radius: 8px;
  padding: 12px 10px;
  text-align: center;
  font-size: 14px;
  font-weight: 700;
  color: var(--dark);
}

.area:hover {
  border-color: var(--blue);
  color: var(--blue);
}

.area-note {
  text-align: center;
  color: #64748b;
  font-size: 13px;
  margin-top: 20px;
}

.branch-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
}

.branch {
  padding: 23px;
  border-radius: 12px;
  border: 1px solid #e5ebf4;
  background: #fff;
}

.branch h3 {
  color: var(--dark);
  margin-bottom: 6px;
}

.branch p {
  font-size: 14px;
  color: #64748b;
  margin-bottom: 12px;
}

.branch a {
  font-weight: 800;
  color: var(--blue);
  font-size: 14px;
}

.booking-wrap {
  display: grid;
  grid-template-columns: .8fr 1.2fr;
  gap: 35px;
  align-items: start;
}

.booking-info {
  background: var(--dark);
  color: #fff;
  padding: 30px;
  border-radius: 14px;
}

.booking-info h3 {
  font-size: 26px;
  line-height: 1.25;
  margin-bottom: 14px;
}

.booking-info p {
  color: #d1deee;
  font-size: 14px;
  margin-bottom: 20px;
}

.booking-info .contact-line {
  padding: 13px 0;
  border-top: 1px solid #ffffff24;
  font-size: 14px;
}

.booking-form {
  border: 1px solid #e4eaf3;
  border-radius: 14px;
  padding: 27px;
  background: #fff;
}

.booking-form h3 {
  color: var(--dark);
  font-size: 23px;
  margin-bottom: 5px;
}

.booking-form > p {
  font-size: 14px;
  color: #64748b;
  margin-bottom: 20px;
}

.form-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 15px;
}

.field {
  display: flex;
  flex-direction: column;
  gap: 6px;
}

.field.full {
  grid-column: 1 / -1;
}

.field label {
  font-weight: 700;
  font-size: 13px;
  color: var(--dark);
}

.field input,
.field select,
.field textarea {
  width: 100%;
  border: 1px solid #dce4ef;
  border-radius: 7px;
  padding: 12px;
  background: #fff;
  color: var(--text);
  outline: none;
}

.field input:focus,
.field select:focus,
.field textarea:focus {
  border-color: var(--blue);
}

.field textarea {
  min-height: 90px;
  resize: vertical;
}

.booking-form .btn {
  width: 100%;
  margin-top: 18px;
}

.privacy-note {
  font-size: 12px;
  color: #64748b;
  margin-top: 10px;
}

.faq-list {
  max-width: 800px;
  margin: auto;
}

details {
  background: #fff;
  border: 1px solid #e4eaf3;
  border-radius: 9px;
  padding: 17px 20px;
  margin-bottom: 12px;
}

summary {
  color: var(--dark);
  font-weight: 800;
  cursor: pointer;
}

details p {
  color: #64748b;
  font-size: 14px;
  padding-top: 12px;
}

.cta {
  background: linear-gradient(120deg, #0756b9, #092447);
  color: #fff;
  text-align: center;
  padding: 55px 20px;
}

.cta h2 {
  font-size: clamp(27px, 4vw, 37px);
  margin-bottom: 12px;
}

.cta p {
  color: #e0eaf8;
  margin-bottom: 22px;
}

footer {
  background: #061a34;
  color: #d5e0ef;
  padding: 38px 0 20px;
}

.footer-grid {
  display: grid;
  grid-template-columns: 1.3fr 1fr 1fr;
  gap: 30px;
  margin-bottom: 28px;
}

footer h3 {
  color: #fff;
  margin-bottom: 12px;
}

footer p, footer li {
  font-size: 13px;
  color: #c2d0e2;
}

footer ul {
  list-style: none;
}

footer li {
  margin: 7px 0;
}

footer a {
  color: #fff;
}

.copyright {
  border-top: 1px solid #ffffff20;
  padding-top: 18px;
  font-size: 12px;
  text-align: center;
  color: #9fb2ca;
}

.whatsapp-float {
  position: fixed;
  right: 18px;
  bottom: 18px;
  z-index: 200;
  background: #168c51;
  color: white;
  padding: 13px 17px;
  border-radius: 50px;
  font-size: 14px;
  font-weight: 900;
  box-shadow: 0 5px 20px #0003;
}

@media (max-width: 800px) {
  .hero-grid,
  .booking-wrap {
    grid-template-columns: 1fr;
  }

  .hero {
    padding: 60px 0;
  }

  .services-grid,
  .branch-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .areas-grid {
    grid-template-columns: repeat(3, 1fr);
  }

  nav {
    gap: 12px;
  }

  nav a {
    font-size: 12px;
  }

  .footer-grid {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 520px) {
  .navbar {
    justify-content: center;
  }

  nav {
    justify-content: center;
  }

  .hero h1 {
    font-size: 36px;
  }

  .services-grid,
  .branch-grid,
  .why-grid,
  .footer-grid {
    grid-template-columns: 1fr;
  }

  .areas-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .stats-grid {
    grid-template-columns: 1fr;
  }

  .stat {
    border-right: 0;
    border-bottom: 1px solid #e8edf4;
  }

  .form-grid {
    grid-template-columns: 1fr;
  }

  .field.full {
    grid-column: auto;
  }

  section {
    padding: 55px 0;
  }
}
</style>
</head>

<body>

<header>
  <div class="container navbar">
    <a class="logo" href="#home">
      Fast<span>2Fix</span>
      <small>SERVICE CENTRE</small>
    </a>

    <nav aria-label="Main navigation">
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#areas">Areas</a>
      <a href="#branches">Branches</a>
      <a href="#booking">Book Service</a>
    </nav>
  </div>
</header>

<main>
<section class="hero" id="home">
  <div class="container hero-grid">
    <div>
      <span class="eyebrow">HOME APPLIANCE REPAIR & SERVICE</span>
      <h1>Your Comfort,<br><span>Our Priority.</span></h1>

      <p>
        Looking for dependable home appliance repair?
        Fast2Fix Service Centre helps you enquire about
        AC service, refrigerator repair, washing machine repair,
        TV repair and more.
      </p>

      <div class="hero-buttons">
        <a class="btn" href="#booking">Book a Service</a>
        <a class="btn btn-outline"
           href="https://wa.me/917050129203?text=Hello%20Fast2Fix%20Service%20Centre%2C%20I%20need%20appliance%20repair%20service."
           target="_blank" rel="noopener">WhatsApp Us</a>
      </div>
    </div>

    <div class="hero-card">
      <h2>Repair Services at Your Convenience</h2>
      <p>Tell us your appliance problem and preferred service area.</p>
      <ul>
        <li><span class="check">✓</span> AC Service & Repair</li>
        <li><span class="check">✓</span> Refrigerator & Washing Machine</li>
        <li><span class="check">✓</span> LED TV & Microwave Repair</li>
        <li><span class="check">✓</span> Geyser, RO & Other Appliances</li>
        <li><span class="check">✓</span> Home Visit Enquiries</li>
      </ul>
    </div>
  </div>
</section>

<div class="stats">
  <div class="container stats-grid">
    <div class="stat">
      <strong>Multiple Services</strong>
      <span>Home appliance solutions</span>
    </div>
    <div class="stat">
      <strong>Service Enquiries</strong>
      <span>Connect with our team</span>
    </div>
    <div class="stat">
      <strong>Home Visit</strong>
      <span>Subject to area availability</span>
    </div>
  </div>
</div>

<section id="services">
  <div class="container">
    <div class="section-heading">
      <span class="tag">Our Services</span>
      <h2>Home Appliance Repair & Maintenance</h2>
      <p>
        Select your appliance to enquire about diagnosis,
        repair, installation or maintenance.
      </p>
    </div>

    <div class="services-grid">

      <article class="service-card">
        <div class="service-icon">❄️</div>
        <h3>AC Repair & Service</h3>
        <p>AC inspection, servicing, cooling issue diagnosis,
          installation and maintenance enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('AC Repair & Service')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">🧊</div>
        <h3>Refrigerator Repair</h3>
        <p>Fridge repair, cooling diagnosis, maintenance
          and refrigerator service enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('Refrigerator Repair')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">🫧</div>
        <h3>Washing Machine Repair</h3>
        <p>Front-load and top-load washing machine
          diagnosis and repair enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('Washing Machine Repair')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">📺</div>
        <h3>LED TV Repair</h3>
        <p>LED TV diagnosis, PCB repair, display-related
          inspection and TV installation enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('LED TV Repair')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">♨️</div>
        <h3>Geyser Repair</h3>
        <p>Water heater inspection, repair and
          installation enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('Geyser Repair')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">🍲</div>
        <h3>Microwave Oven Repair</h3>
        <p>Microwave oven fault diagnosis and
          repair service enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('Microwave Oven Repair')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">💧</div>
        <h3>RO & Water Purifier</h3>
        <p>Water purifier servicing, inspection
          and maintenance enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('RO & Water Purifier')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">🌀</div>
        <h3>Chimney Repair</h3>
        <p>Kitchen chimney inspection, cleaning
          and repair enquiries.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('Chimney Repair')">Enquire Now →</a>
      </article>

      <article class="service-card">
        <div class="service-icon">🔧</div>
        <h3>Installation & Other Services</h3>
        <p>Appliance installation, spare parts enquiries,
          plumbing, carpentry and related services.</p>
        <a class="text-link" href="#booking"
           onclick="chooseService('Installation & Other Services')">Enquire Now →</a>
      </article>

    </div>
  </div>
</section>

<section class="soft" id="why-us">
  <div class="container">
    <div class="section-heading">
      <span class="tag">Why Fast2Fix</span>
      <h2>A Straightforward Service Experience</h2>
      <p>We aim to make appliance service enquiries
        simple and convenient for our customers.</p>
    </div>

    <div class="why-grid">
      <div class="why-card">
        <h3>✓ Professional Workmanship</h3>
        <p>Service requests are handled according to
          appliance type and the reported problem.</p>
      </div>
      <div class="why-card">
        <h3>✓ Accurate Diagnosis</h3>
        <p>Inspection helps identify the fault before
          repair work and parts replacement.</p>
      </div>
      <div class="why-card">
        <h3>✓ Clear Communication</h3>
        <p>Ask about visit charges, estimated repair costs
          and parts before approving the work.</p>
      </div>
      <div class="why-card">
        <h3>✓ Proper Testing</h3>
        <p>Where applicable, repaired appliances should
          be checked before service completion.</p>
      </div>
    </div>
  </div>
</section>

<section id="areas">
  <div class="container">
    <div class="section-heading">
      <span class="tag">Kharagpur Service Areas</span>
      <h2>Local Appliance Repair Enquiries</h2>
      <p>Contact us with your exact location to confirm
        technician availability and home-visit coverage.</p>
    </div>

    <div class="areas-grid">
      <div class="area">Kharida</div>
      <div class="area">Bidhanpally</div>
      <div class="area">Inda</div>
      <div class="area">Malancha</div>
      <div class="area">Golbazar</div>
      <div class="area">Nimpura</div>
      <div class="area">Hijli</div>
      <div class="area">Kalaikunda</div>
      <div class="area">Prembazar</div>
      <div class="area">Gopali</div>
      <div class="area">Gokulpur</div>
      <div class="area">Talbagicha</div>
      <div class="area">Balarampur</div>
      <div class="area">Puratan Bazar</div>
      <div class="area">Bhawanipur</div>
      <div class="area">Salua</div>
      <div class="area">Midnapore</div>
      <div class="area">Bhadutala</div>
      <div class="area">Chandri</div>
      <div class="area">Belda</div>
    </div>

    <p class="area-note">
      Areas are indicative, not a guarantee of service within
      a fixed radius. Confirm availability before booking.
    </p>
  </div>
</section>

<section class="soft" id="branches">
  <div class="container">
    <div class="section-heading">
      <span class="tag">Our Service Network</span>
      <h2>Fast2Fix Service Locations</h2>
      <p>Choose your location when sending a service enquiry.
        Coverage and availability may vary by area.</p>
    </div>

    <div class="branch-grid">
      <article class="branch">
        <h3>Dhanbad, Jharkhand</h3>
        <p>Main service network location.</p>
        <a href="#booking" onclick="chooseArea('Dhanbad')">Enquire for Dhanbad →</a>
      </article>

      <article class="branch">
        <h3>Bokaro, Jharkhand</h3>
        <p>Appliance service enquiries.</p>
        <a href="#booking" onclick="chooseArea('Bokaro')">Enquire for Bokaro →</a>
      </article>

      <article class="branch">
        <h3>Kharagpur, West Bengal</h3>
        <p>Local repair and home-visit enquiries.</p>
        <a href="#booking" onclick="chooseArea('Kharagpur')">Enquire for Kharagpur →</a>
      </article>

      <article class="branch">
        <h3>Bihar Sharif, Bihar</h3>
        <p>Service enquiries for your area.</p>
        <a href="#booking" onclick="chooseArea('Bihar Sharif')">Enquire for Bihar Sharif →</a>
      </article>

      <article class="branch">
        <h3>Patna, Bihar</h3>
        <p>Appliance repair and service enquiries.</p>
        <a href="#booking" onclick="chooseArea('Patna')">Enquire for Patna →</a>
      </article>

      <article class="branch">
        <h3>Jamshedpur, Jharkhand</h3>
        <p>Contact us to confirm local coverage.</p>
        <a href="#booking" onclick="chooseArea('Jamshedpur')">Check Availability →</a>
      </article>
    </div>
  </div>
</section>

<section id="booking">
  <div class="container">
    <div class="section-heading">
      <span class="tag">Service Request</span>
      <h2>Book a Repair Enquiry</h2>
      <p>Fill in your details. Your enquiry will open in
        WhatsApp for you to review and send.</p>
    </div>

    <div class="booking-wrap">
      <div class="booking-info">
        <h3>Need Help With Your Appliance?</h3>
        <p>Share your appliance, problem and service location.
          Our team can discuss availability and next steps.</p>

        <div class="contact-line">
          <strong>WhatsApp Enquiries</strong><br>
          +91 70501 29203
        </div>
        <div class="contact-line">
          <strong>Website</strong><br>
          Fast2Fix Service Centre
        </div>
        <div class="contact-line">
          <strong>Before Booking</strong><br>
          Confirm visit charges, parts cost and service availability.
        </div>
      </div>

      <form class="booking-form" id="serviceForm">
        <h3>Tell Us What You Need</h3>
        <p>Fields marked * are required.</p>

        <div class="form-grid">
          <div class="field">
            <label for="customerName">Full Name *</label>
            <input id="customerName" name="customerName"
                   type="text" placeholder="Enter your name" required>
          </div>

          <div class="field">
            <label for="customerPhone">Mobile Number *</label>
            <input id="customerPhone" name="customerPhone"
                   type="tel" inputmode="numeric"
                   pattern="[0-9]{10}"
                   maxlength="10" placeholder="10-digit mobile" required>
          </div>

          <div class="field">
            <label for="serviceArea">Service Location *</label>
            <select id="serviceArea" name="serviceArea" required>
              <option value="">Select your location</option>
              <option>Dhanbad</option>
              <option>Bokaro</option>
              <option>Kharagpur</option>
              <option>Bihar Sharif</option>
              <option>Patna</option>
              <option>Jamshedpur</option>
              <option>Other Area</option>
            </select>
          </div>

          <div class="field">
            <label for="appliance">Appliance *</label>
            <select id="appliance" name="appliance" required>
              <option value="">Select appliance</option>
              <option>AC Repair & Service</option>
              <option>Refrigerator Repair</option>
              <option>Washing Machine Repair</option>
              <option>LED TV Repair</option>
              <option>Geyser Repair</option>
              <option>Microwave Oven Repair</option>
              <option>RO & Water Purifier</option>
              <option>Chimney Repair</option>
              <option>Installation & Other Services</option>
            </select>
          </div>

          <div class="field full">
            <label for="customerAddress">Full Address / Locality *</label>
            <input id="customerAddress" name="customerAddress"
                   type="text" placeholder="Area, street and landmark" required>
          </div>

          <div class="field full">
            <label for="problem">Describe the Problem</label>
            <textarea id="problem" name="problem"
                      placeholder="Tell us about the appliance problem"></textarea>
          </div>
        </div>

        <button class="btn" type="submit">
          Send Enquiry on WhatsApp
        </button>
        <p class="privacy-note">
          Your form is not stored by this website. The details are
          placed into a WhatsApp message for your review.
        </p>
      </form>
    </div>
  </div>
</section>

<section class="soft" id="faq">
  <div class="container">
    <div class="section-heading">
      <span class="tag">FAQs</span>
      <h2>Frequently Asked Questions</h2>
    </div>

    <div class="faq-list">
      <details>
        <summary>Which appliances can I enquire about?</summary>
        <p>You can enquire about AC, refrigerator, washing machine,
          LED TV, geyser, microwave oven, RO, chimney and other
          listed installation or repair services.</p>
      </details>

      <details>
        <summary>Do you provide home visits?</summary>
        <p>Home visits depend on your location, appliance type
          and technician availability. Contact us to confirm.</p>
      </details>

      <details>
        <summary>What are the repair charges?</summary>
        <p>Charges depend on the appliance, fault, parts required
          and service location. Request a quote before approving
          repair work.</p>
      </details>

      <details>
        <summary>How can I request a service?</summary>
        <p>Complete the service enquiry form and continue to
          WhatsApp. Review the details and press Send in WhatsApp
          to submit your enquiry.</p>
      </details>
    </div>
  </div>
</section>

<section class="cta">
  <div class="container">
    <h2>Let's Get Your Appliance Working Again</h2>
    <p>Contact Fast2Fix Service Centre for your repair enquiry.</p>
    <a class="btn" href="#booking">Request a Service</a>
  </div>
</section>
</main>

<footer>
  <div class="container">
    <div class="footer-grid">
      <div>
        <h3>Fast2Fix Service Centre</h3>
        <p>Home appliance repair and service enquiries
          across our service network.</p>
        <p style="margin-top:12px;">Your Comfort, Our Priority.</p>
      </div>

      <div>
        <h3>Quick Links</h3>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Our Services</a></li>
          <li><a href="#areas">Kharagpur Service Areas</a></li>
          <li><a href="#branches">Service Locations</a></li>
          <li><a href="#booking">Book a Service</a></li>
        </ul>
      </div>

      <div>
        <h3>Contact & Enquiries</h3>
        <p>WhatsApp: <a href="https://wa.me/917050129203"
           target="_blank" rel="noopener">+91 70501 29203</a></p>
        <p style="margin-top:8px;">
          Please confirm your location and service availability
          before arranging a visit.
        </p>
      </div>
    </div>

    <div class="copyright">
      © <span id="year"></span> Fast2Fix Service Centre.
      All rights reserved.
    </div>
  </div>
</footer>

<a class="whatsapp-float"
   href="https://wa.me/917050129203?text=Hello%20Fast2Fix%20Service%20Centre"
   target="_blank" rel="noopener"
   aria-label="Contact Fast2Fix on WhatsApp">WhatsApp ↗</a>

<script>
const WHATSAPP_NUMBER = "917050129203";

function chooseService(service) {
  const field = document.getElementById("appliance");
  field.value = service;
}

function chooseArea(area) {
  const field = document.getElementById("serviceArea");
  field.value = area;
}

document.getElementById("year").textContent =
  new Date().getFullYear();

document.getElementById("serviceForm").addEventListener("submit", function(e) {
  e.preventDefault();

  const name = document.getElementById("customerName").value.trim();
  const phone = document.getElementById("customerPhone").value.trim();
  const area = document.getElementById("serviceArea").value;
  const appliance = document.getElementById("appliance").value;
  const address = document.getElementById("customerAddress").value.trim();
  const problem = document.getElementById("problem").value.trim();

  if (!/^[0-9]{10}$/.test(phone)) {
    alert("Please enter a valid 10-digit mobile number.");
    return;
  }

  const message =
    "Hello Fast2Fix Service Centre,%0A%0A" +
    "*New Service Enquiry*%0A" +
    "Name: " + encodeURIComponent(name) + "%0A" +
    "Customer Mobile: " + encodeURIComponent(phone) + "%0A" +
    "Location: " + encodeURIComponent(area) + "%0A" +
    "Appliance: " + encodeURIComponent(appliance) + "%0A" +
    "Address: " + encodeURIComponent(address) + "%0A" +
    "Problem: " + encodeURIComponent(problem || "Not specified");

  const url = "https://wa.me/" + WHATSAPP_NUMBER + "?text=" + message;
  window.open(url, "_blank", "noopener");
});
</script>

</body>
</html>
