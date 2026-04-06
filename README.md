<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Plant Kingdom Nursery</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0b2e13;
      color: white;
    }

    header {
      background: #14532d;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
      letter-spacing: 2px;
    }

    nav {
      background: #166534;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 10px;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      height: 70vh;
      background: url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6') no-repeat center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero h1 {
      font-size: 50px;
      background: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 10px;
    }

    .section {
      padding: 50px 20px;
      text-align: center;
    }

    .section h2 {
      font-size: 32px;
      margin-bottom: 20px;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      background: #166534;
      padding: 20px;
      width: 250px;
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin-top: 30px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
    }

    .contact-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      padding: 15px 20px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 5px 10px rgba(0,0,0,0.3);
    }

    footer {
      background: #022c22;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }

    iframe {
      width: 100%;
      height: 400px;
      border: none;
      border-radius: 10px;
    }

    @media(max-width:600px){
      .hero h1 {
        font-size: 32px;
      }
    }
  </style>
</head>

<body>

<header>
  🌿 PLANT KINGDOM NURSERY
</header>

<nav>
  <a href="#about">About Us</a>
  <a href="#plants">Plants</a>
  <a href="#gallery">Gallery</a>
  <a href="#contact">Contact</a>
  <a href="#location">Location</a>
</nav>

<div class="hero">
  <h1>Build Your Green Empire 🌱</h1>
</div>

<div class="section" id="about">
  <h2>About Us</h2>
  <p>
    Plant Kingdom Nursery brings you a wide variety of healthy plants, trees, and garden essentials to create your perfect green environment. Grow bigger, greener, and better with us.
  </p>
</div>

<div class="section" id="plants">
  <h2>Our Plants</h2>
  <div class="cards">
    <div class="card">🌿 Indoor Plants</div>
    <div class="card">🌳 Outdoor Plants</div>
    <div class="card">🌸 Flowering Plants</div>
    <div class="card">🌱 Garden Supplies</div>
  </div>
</div>

<div class="section" id="gallery">
  <h2>Gallery</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1524594150484-9df5b8ab6370" alt="Plant 1">
    <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" alt="Plant 2">
    <img src="https://images.unsplash.com/photo-1617196032769-6b5b2a636a8b" alt="Plant 3">
    <img src="https://images.unsplash.com/photo-1594769701170-d72cf66e05f6" alt="Plant 4">
  </div>
</div>

<div class="section" id="contact">
  <h2>Contact Us</h2>
  <p>Email: yournursery@email.com</p>
  <p>Phone: +91 98765 43210</p>
</div>

<div class="section" id="location">
  <h2>Our Location</h2>
  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3650.7392928921456!2d90.39817681543269!3d23.745601484588944!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755c7a2d1cfa1c1%3A0x123456789abcdef!2sPlant+Kingdom+Nursery!5e0!3m2!1sen!2sin!4v1580000000000!5m2!1sen!2sin" 
    allowfullscreen="" loading="lazy">
  </iframe>
</div>

<a class="contact-button" href="https://wa.me/919876543210" target="_blank">WhatsApp Us</a>

<footer>
  © 2026 Plant Kingdom Nursery | Grow Big. Grow Green.
</footer>

</body>
</html># Plants-with-Garden.github.io
