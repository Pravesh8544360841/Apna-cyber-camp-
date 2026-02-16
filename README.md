<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apna Cyber Camp</title>

  <meta name="description" content="Apna Cyber Camp - Online Cyber Services & Form Filling">
  <meta name="keywords" content="Cyber Cafe, Online Services, Apna Cyber Camp">
  <meta name="author" content="Apna Cyber Camp">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #e60000, #990000);
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 30px 15px;
      max-width: 1100px;
      margin: auto;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .card h3 {
      margin-top: 0;
      color: #e60000;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: 0;
      border-radius: 10px;
    }

    form input, form textarea, form button {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    form button {
      background: #e60000;
      color: white;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }

    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 12px 18px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 15px;
      font-size: 14px;
    }

    @media (max-width:600px){
      header p {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Apna Cyber Camp</h1>
  <p>Online Cyber & Digital Services</p>
  <nav>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
    <a href="#location">Location</a>
  </nav>
</header>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Online Form Filling</h3>
      <p>Government & private forms filling support.</p>
    </div>
    <div class="card">
      <h3>Aadhaar / PAN Work</h3>
      <p>Correction, update & related services.</p>
    </div>
    <div class="card">
      <h3>Online Applications</h3>
      <p>Job, exam & admission applications.</p>
    </div>
    <div class="card">
      <h3>Printing & Scanning</h3>
      <p>Document print, scan & upload help.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form action="https://formspree.io/f/xxxxx" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>

<section id="location">
  <h2>Our Location</h2>
  <iframe 
    src="https://www.google.com/maps?q=INDIA&output=embed">
  </iframe>
</section>

<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX" target="_blank">
  💬 Chat Now
</a>

<footer>
  © 2026 Apna Cyber Camp | All Rights Reserved
</footer>

</body>
</html>
