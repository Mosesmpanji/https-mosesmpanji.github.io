<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=5.0" />
  <title>Mosempanji Aquifer Oil Genesis Ltd</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f0fff0;
    }
    header {
      background: linear-gradient(to right, lightblue, chocolate);
      padding: 1rem;
      display: flex;
      align-items: center;
      color: white;
    }
    .logo {
      height: 60px;
      margin-right: 1rem;
    }
    header h1 {
      font-size: 1.8rem;
      margin: 0;
    }
    header p {
      font-size: 1rem;
    }
    nav {
      background: palegreen;
      padding: 0.75rem;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
    }
    nav a {
      color: #333;
      text-decoration: none;
      font-weight: bold;
    }
    .slider {
      width: 100%;
      max-height: 400px;
      overflow: hidden;
      position: relative;
    }
    .slides {
      display: flex;
      width: 400%;
      animation: slide 12s infinite;
    }
    .slides img {
      width: 100%;
      height: 400px;
      object-fit: cover;
    }
    @keyframes slide {
      0% { transform: translateX(0); }
      25% { transform: translateX(-100%); }
      50% { transform: translateX(-200%); }
      75% { transform: translateX(-300%); }
      100% { transform: translateX(0); }
    }
    section {
      padding: 2rem;
    }
    #home {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background-color: #8d9e6a; /* Updated to a fitting color */
      color: white;
    }
    .product-inquiry {
      margin-top: 2rem;
      padding: 1rem;
      background: #e0ffe0;
      border: 1px solid #ccc;
    }
    .product-inquiry input, .product-inquiry textarea {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
    }
    footer {
      background: lightblue;
      color: #000;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo_resized.png" alt="Company Logo" class="logo" />
    <div>
      <h1>Mosempanji Aquifer Oil Genesis Ltd</h1>
      <p><em>Smoothening the future</em></p>
    </div>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="slider">
    <div class="slides">
      <img src="IMG-20240831-WA0121.jpg" alt="Slide 1">
      <img src="IMG-20240831-WA0141.jpg" alt="Slide 2">
      <img src="Oil_sources-1200x772.jpg" alt="Slide 3">
     <img src="images/R4.jpeg" alt="Slide 4">
    </div>
  </div>

  <section id="home">
    <!-- Removed the h2 and p tags as requested -->
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Mosempanji Aquifer Oil Genesis Ltd is a leading provider of energy solutions, specializing in the supply of premium gasoline and hydrocarbons to meet the growing demands of the industrial and commercial sectors. With a vision rooted in innovation, sustainability, and excellence, our company was established to bridge the energy needs of local and international markets through seamless importing and logistics services.</p>
    <p>We pride ourselves on our commitment to environmental responsibility and customer satisfaction. Our operations are designed to ensure efficient sourcing, safe transportation, and timely delivery of petroleum products. Through strategic partnerships and a dedicated team of professionals, Mosempanji Aquifer Oil Genesis Ltd strives to play a key role in the development of reliable energy infrastructure and economic progress.</p>
    <p>From sourcing quality hydrocarbons globally to delivering them at your doorstep, we handle everything with precision and care. Trust us to power your industry, business, or community with integrity and a smooth approach to energy supply.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <ul>
      <li><strong>Gasoline:</strong> High-quality fuel for vehicles and industrial machines, ensuring performance and efficiency.</li>
      <li><strong>Hydrocarbons:</strong> A wide range of refined petroleum products used across multiple energy and manufacturing sectors.</li>
    </ul>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Logistics Solutions:</strong> End-to-end energy product delivery through road, rail, and sea logistics.</li>
      <li><strong>Importing Energy Products:</strong> We specialize in bringing in quality gasoline and hydrocarbons from international sources to ensure local energy stability.</li>
    </ul>
  </section>

  <section class="product-inquiry">
    <h3>Request a Product</h3>
    <form>
      <label for="name">Your Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>

      <label for="product">Product Description / Inquiry</label>
      <textarea id="product" name="product" rows="4" required></textarea>

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
