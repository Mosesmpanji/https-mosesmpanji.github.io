<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mosempanji Aquifer Oil Genesis Ltd</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f0fff0;
      color: #222;
    }
    header {
      background: chocolate;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background: palegreen;
      padding: 0.5rem;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2rem;
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
      width: 400%;
      height: 100%;
      animation: slide 20s infinite;
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
    footer {
      background: lightblue;
      color: #000;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    .inquiry-form {
      background-color: #e0ffe0;
      padding: 1rem;
      border-radius: 10px;
    }
    .inquiry-form input,
    .inquiry-form textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.5rem;
      margin-bottom: 1rem;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .inquiry-form button {
      background-color: chocolate;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mosempanji Aquifer Oil Genesis Ltd</h1>
    <p><em>Smoothening the future</em></p>
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
      <img src="IMG-20240831-WA0121.jpg" alt="Slide 1" />
      <img src="IMG-20240831-WA0141.jpg" alt="Slide 2" />
      <img src="Oil_sources-1200*772.jpg" alt="Slide 3" />
      <img src="R(1).jpeg" alt="Slide 4" />
    </div>
  </div>

  <section id="home">
    <h2>Welcome to Mosempanji Aquifer Oil Genesis Ltd</h2>
    <p>Your reliable partner in hydrocarbons and gasoline logistics, smoothing the future with every drop. We are dedicated to bridging energy solutions across borders with unmatched professionalism and commitment.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>
      Mosempanji Aquifer Oil Genesis Ltd is a dynamic energy company committed to driving growth and sustainability in the oil and gas industry. Founded with a vision to provide dependable energy solutions, our company has rapidly evolved into a trusted name in the logistics and importation of hydrocarbon products.
    </p>
    <p>
      Our business model is centered on customer satisfaction, safety, and efficiency. We specialize in the importation and distribution of premium-grade gasoline and hydrocarbons, ensuring clients across Tanzania and beyond have access to consistent energy supplies.
    </p>
    <p>
      With a strong logistical network and strategic international partnerships, Mosempanji Aquifer Oil Genesis Ltd guarantees seamless delivery of energy products to businesses and institutions. We believe in innovation, environmental responsibility, and transparency. Our team of experienced professionals continuously works to optimize operations while maintaining compliance with industry standards and government regulations.
    </p>
    <p>
      As we expand our footprint, our commitment remains steadfast: to empower communities, enhance energy accessibility, and shape a cleaner and more energy-secure future for all.
    </p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <ul>
      <li>
        <strong>Gasoline:</strong> High-quality petrol refined and tested to meet regulatory and environmental standards, ideal for automobiles and machinery.
      </li>
      <li>
        <strong>Hydrocarbons:</strong> A range of organic compounds including alkanes, alkenes, and other derivatives used in fuel, industrial processing, and petrochemical production.
      </li>
    </ul>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Logistics Solutions:</strong> We manage the full transport and distribution of energy products from international sources to your local facility.</li>
      <li><strong>Importing Energy Products:</strong> Expertise in international trade and procurement of fuel, ensuring you receive safe and certified energy supplies.</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:mosesmpanji123@gmail.com">mosesmpanji123@gmail.com</a></p>

    <div class="inquiry-form">
      <h3>Request a Product</h3>
      <form>
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="product">Requested Product:</label>
        <textarea id="product" name="product" rows="4" required></textarea>

        <button type="submit">Submit Inquiry</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Mosempanji Aquifer Oil Genesis Ltd. All rights reserved.</p>
  </footer>
</body>
</html>
