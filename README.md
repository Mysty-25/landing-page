<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mysty Concepts | Creative Strategy & Design</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- NAVBAR -->
  <header class="navbar">
    <div class="logo">MYSTY CONCEPTS</div>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <h1>Designing Brands That Actually Grow</h1>
      <p>
        Mysty Concepts blends creative visuals with smart strategy
        to help brands stand out and scale.
      </p>
      <a href="#contact" class="btn">Start a Project</a>
    </div>
  </section>

  <!-- SERVICES -->
  <section id="services" class="services">
    <h2>What We Do</h2>

    <div class="services-grid">
      <div class="service-card">
        <img src="https://images.unsplash.com/photo-1529333166437-7750a6dd5a70" alt="">
        <h3>Brand Identity</h3>
        <p>
          Logos, visual systems, and brand guidelines that give your
          business a strong, memorable presence.
        </p>
      </div>

      <div class="service-card">
        <img src="https://images.unsplash.com/photo-1611162616475-46b635cb6868" alt="">
        <h3>Social Media & Content</h3>
        <p>
          Scroll-stopping content and data-driven strategies built
          for modern platforms.
        </p>
      </div>

      <div class="service-card">
        <img src="https://images.unsplash.com/photo-1556761175-5973dc0f32e7" alt="">
        <h3>Creative Strategy</h3>
        <p>
          We connect creativity with analytics to help brands grow
          intentionally, not randomly.
        </p>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="about">
    <div class="about-text">
      <h2>About Mysty Concepts</h2>
      <p>
        Mysty Concepts is a creative studio focused on helping modern
        brands communicate clearly, look premium, and grow with purpose.
      </p>
      <p>
        We don’t just design—we think, analyze, and build brands
        that last in the digital space.
      </p>
    </div>

    <div class="about-image">
      <img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf" alt="">
    </div>
  </section>

  <!-- PORTFOLIO -->
  <section id="portfolio" class="portfolio">
    <h2>Recent Work</h2>

    <div class="portfolio-grid">
      <img src="https://images.unsplash.com/photo-1492724441997-5dc865305da7" alt="">
      <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4" alt="">
      <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f" alt="">
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="contact">
    <h2>Let’s Work Together</h2>
    <p>
      Have an idea, a brand, or a project?
      Let’s turn it into something powerful.
    </p>

    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Tell us about your project"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2026 Mysty Concepts. All rights reserved.</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", sans-serif;
}

body {
  background: #0e0e0e;
  color: #ffffff;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
  background: #000;
}

.logo {
  font-weight: bold;
  letter-spacing: 2px;
}

.navbar a {
  color: #fff;
  margin-left: 20px;
  text-decoration: none;
  font-size: 0.9rem;
}

/* HERO */
.hero {
  height: 90vh;
  background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
    url("https://images.unsplash.com/photo-1498050108023-c5249f4df085") center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 20px;
}

.hero p {
  max-width: 600px;
  margin: auto;
  opacity: 0.85;
}

.btn {
  display: inline-block;
  margin-top: 30px;
  padding: 14px 36px;
  background: #fff;
  color: #000;
  text-decoration: none;
  font-weight: bold;
}

/* SECTIONS */
section {
  padding: 80px 40px;
}

h2 {
  text-align: center;
  margin-bottom: 50px;
}

/* SERVICES */
.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.service-card {
  background: #111;
  padding: 20px;
  border-radius: 10px;
}

.service-card img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 15px;
}

/* ABOUT */
.about {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  align-items: center;
}

.about img {
  width: 100%;
  border-radius: 12px;
}

/* PORTFOLIO */
.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.portfolio-grid img {
  width: 100%;
  border-radius: 10px;
}

/* CONTACT */
.contact form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

.contact input,
.contact textarea {
  padding: 12px;
  margin-bottom: 15px;
  border: none;
  border-radius: 6px;
}

.contact button {
  padding: 14px;
  background: #fff;
  color: #000;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

/* FOOTER */
footer {
  background: #000;
  text-align: center;
  padding: 20px;
  font-size: 0.85rem;
}
