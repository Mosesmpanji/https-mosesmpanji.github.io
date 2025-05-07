<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mosempanji Aquifer Oil Genesis Ltd</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(to right, #5c3317, #a0522d);
      color: white;
      padding: 2em 1em;
      text-align: center;
    }
    nav {
      background-color: #d0f0c0;
      padding: 1em;
      display: flex;
      justify-content: center;
      gap: 2rem;
      flex-wrap: wrap;
    }
    nav a {
      color: #333;
      text-decoration: none;
      font-weight: bold;
    }
    .slider {
      width: 100%;
      height: 400px;
      overflow: hidden;
      position: relative;
    }
    .slides {
      display: flex;
      width: 300%;
      animation: slide 180s infinite;
    }
    .slides img {
      width: 100%;
      height: 400px;
      object-fit: cover;
    }
    @keyframes slide {
      0% { transform: translateX(0%); }
      33% { transform: translateX(-100%); }
      66% { transform: translateX(-200%); }
      100% { transform: translateX(0%); }
    }
    section {
      padding: 2em 5%;
      max-width: 1200px;
      margin: auto;
    }
    ul {
      padding-left: 1.5em;
    }
    .product-inquiry {
      background-color: #eefbef;
      border: 1px solid #ccc;
      padding: 2em;
      margin: 2em 0;
    }
    .product-inquiry label {
      display: block;
      margin-top: 1em;
    }
    .product-inquiry input, .product-inquiry textarea {
      width: 100%;
      padding: 0.5em;
      margin-top: 0.5em;
    }
    .product-inquiry button {
      margin-top: 1em;
      padding: 0.75em 1.5em;
      background-color: #5c3317;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      background-color: #5c3317;
      color: white;
      text-align: center;
      padding: 2em 1em;
      margin-top: 2em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mosempanji Aquifer Oil Genesis Ltd</h1>
    <p><em>Smoothening the future</em></p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="slider">
    <div class="slides">
      <img src="IMG-20240831-WA0121.jpg" alt="Slide 1">
      <img src="IMG-20240831-WA0141.jpg" alt="Slide 2">
      <img src="Oil_sources-1200x772.jpg" alt="Slide 3">
    </div>
  </div>

  <section id="about">
    <h2>About Us</h2>
    <p>We are a forward-looking energy company focused on delivering quality gasoline and hydrocarbon products, while providing dependable logistics and importing services from abroad.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <ul>
      <li>Gasoline – High-quality refined fuel</li>
      <li>Hydrocarbons – Broad range for industrial needs</li>
    </ul>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Logistics – Seamless transport by road, rail, or sea</li>
      <li>Importing – Bringing energy products from international sources</li>
    </ul>
  </section>

  <section class="product-inquiry">
    <h3>Request a Product</h3>
    <form>
      <label for="name">Your Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Your Email</label>
      <input type="email" id="email" name="email" required>

      <label for="inquiry">Product Inquiry</label>
      <textarea id="inquiry" name="inquiry" rows="4" required></textarea>

      <button type="submit">Submit Request</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:mosesmpanji123@gmail.com">mosesmpanji123@gmail.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Mosempanji Aquifer Oil Genesis Ltd. All rights reserved.</p>
  </footer>
</body>
</html>
