<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mysty Concepts</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- Navbar -->
  <header class="navbar">
    <h1 class="logo">MYSTY CONCEPTS</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h2>Design. Strategy. Growth.</h2>
    <p>We help modern brands stand out with visuals and data-driven creativity.</p>
    <a href="#contact" class="btn">Work With Us</a>
  </section>

  <!-- Services -->
  <section id="services" class="services">
    <h3>What We Do</h3>
    <div class="service-box">
      <p>Brand Identity & Visual Design</p>
      <p>Social Media Strategy & Analytics</p>
      <p>Content Creation & Campaigns</p>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="about">
    <h3>About Mysty Concepts</h3>
    <p>
      Mysty Concepts is a creative studio focused on building strong digital
      brands through design, storytelling, and strategy.
    </p>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h3>Let’s Build Something</h3>
    <p>Email: mystyconcepts@gmail.com</p>
  </section>

  <footer>
    <p>© 2026 Mysty Concepts. All rights reserved.</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #0f0f0f;
  color: #ffffff;
  line-height: 1.6;
}

.navbar {
  display: flex;
  justify-content: space-between;
  padding: 20px 40px;
  background: #000;
}

.navbar a {
  color: #fff;
  margin-left: 20px;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 3rem;
}

.hero p {
  margin: 20px 0;
  opacity: 0.8;
}

.btn {
  display: inline-block;
  padding: 12px 30px;
  background: #ffffff;
  color: #000;
  text-decoration: none;
  font-weight: bold;
}

.services, .about, .contact {
  padding: 80px 40px;
  text-align: center;
}

.service-box p {
  margin: 10px 0;
}

footer {
  text-align: center;
  padding: 20px;
  background: #000;
  font-size: 0.9rem;
}
Initial Mysty Concepts landing page structure
