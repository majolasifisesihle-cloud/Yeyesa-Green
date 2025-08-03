<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Yeyesa Green</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f9f4;
      color: #333;
    }
    header {
      background-color: #2e7d32;
      color: white;
      padding: 20px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    header img {
      height: 60px;
    }
    header span {
      font-weight: bold;
    }
    nav {
      margin-top: 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: #c8e6c9;
    }
    .hero h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2em;
      color: #444;
    }
    .content {
      padding: 30px 20px;
      max-width: 800px;
      margin: auto;
    }
    .contact {
      background-color: #e8f5e9;
      padding: 20px;
      border-radius: 8px;
      margin-top: 40px;
    }
    .contact h2 {
      margin-top: 0;
    }
    .contact a {
      color: #2e7d32;
      text-decoration: none;
      font-weight: bold;
    }
    .gallery {
      max-width: 800px;
      margin: 40px auto;
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .gallery img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
      flex: 1 1 200px;
    }
  </style>
</head>
<body>

<header>
  <img src="logo.png" alt="Yeyesa Green Logo" />
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">
  <h1>Welcome to Yeyesa Green</h1>
  <p>Your sustainable gardening partner.</p>
</section>

<section class="content" id="about">
  <h2>About Us</h2>
  <p>Yeyesa Green is dedicated to bringing eco-friendly gardening services to your home and community. We specialize in sustainable landscaping, garden design, and maintenance using green practices.</p>
</section>

<section class="contact" id="contact">
  <h2>Contact Us</h2>
  <p>Email: <a href="mailto:info@yeyesagreen.com">info@yeyesagreen.com</a></p>
  <p>Phone: <a href="tel:+27715509075">+27715509075</a></p>
</section>

<section class="gallery">
  <img src="Garden 1.jpg" alt="Garden 1.jpg" />
  <img src="Garden 2.jpg" alt="Garden 2.jpg" />
  <img src="Garden 3.jpg" alt="Garden 3.jpg" />
</section>

</body>
</html>
