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
      gap: 2rem;
    }
    nav a {
      color: #333;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .carousel {
      width: 100%;
      max-height: 400px;
      overflow: hidden;
      position: relative;
    }
    .carousel img {
      width: 100%;
      height: auto;
      display: none;
    }
    .carousel img.active {
      display: block;
    }
    footer {
      background: lightblue;
      color: #000;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
.slider {
  position: relative;
  width: 100%;
  height: 400px;
  overflow: hidden;
  margin-bottom: 2rem;
}

.slides {
  display: flex;
  width: 400%;
  height: 100%;
  animation: slide 16s infinite;
}

.slides img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

@keyframes slide {
  0% { transform: translateX(0%); }
  25% { transform: translateX(-100%); }
  50% { transform: translateX(-200%); }
  75% { transform: translateX(-300%); }
  100% { transform: translateX(0%); }
}

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

 <section id="home">
  <div class="slider">
    <div class="slides">
      <img src="IMG-20240831-WA0121.jpg" alt="Slide 1">
      <img src="IMG-20240831-WA0141.jpg" alt="Slide 2">
      <img src="Oil_sources-1200*772.jpg" alt="Slide 3">
      <img src="R(1).jpeg" alt="Slide 4">
    </div>
  </div>

  <h2>Welcome to Mosempanji Aquifer Oil Genesis Ltd</h2>
  <p>Your reliable partner in hydrocarbons and gasoline logistics, smoothing the future with every drop.</p>
</section>


  <section id="about">
    <h2>About Us</h2>
    <p>Mosempanji Aquifer Oil Genesis Ltd is committed to energy excellence by providing top-tier gasoline and hydrocarbon products, while ensuring efficient global logistics and importing services.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <ul>
      <li><strong>Gasoline:</strong> High-performance fuel for vehicles, power tools, and machines. Sourced with care and delivered with efficiency.</li>
      <li><strong>Hydrocarbons:</strong> Diverse range of organic compounds including fuels, solvents, and industrial raw materials, sourced and processed to the highest standards.</li>
    </ul>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Logistics Solutions – Safe, timely, and efficient energy transport solutions across regions.</li>
      <li>Importing Energy Products from Abroad – Seamless and compliant global procurement of gasoline and hydrocarbons.</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:mosesmpanji123@gmail.com">mosesmpanji123@gmail.com</a></p>
    <p>Need a product? <a href="mailto:mosesmpanji123@gmail.com?subject=Requesting%20Product">Click here to send a request</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Mosempanji Aquifer Oil Genesis Ltd. All rights reserved.</p>
  </footer>

  <script>
    // Carousel functionality
    let index = 0;
    const slides = document.querySelectorAll('.carousel img');
    setInterval(() => {
      slides[index].classList.remove('active');
      index = (index + 1) % slides.length;
      slides[index].classList.add('active');
    }, 3000);
  </script>
</body>
</html>
