# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ShingNoor | Creative & Tech Services</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background: #f4f4f4;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
  padding: 20px;
}

header {
  background: blue;
  color: #fff;
  padding: 40px 0;
  text-align: center;
}

nav {
  background: #444;
  padding: 10px 0;
  text-align: center;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  
  a hover: blue;
}

nav ul li a:hover {
  text-decoration: underline
}

section {
  padding: 40px 0;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.service {
  background: #fff;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.service:hover {
  transform: scale(1.03);
}

footer {
  background: blue;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}
</style>

<body>
  <header>
    <div class="container">
      <h1>ShingNoor</h1>
      <p>Your one-stop solution for creative and tech services</p>
    </div>
  </header>

  <nav>
    <ul>
      <li><a href="#services">Services</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="services" class="container">
    <h2>Our Services</h2>
    <div class="service-grid">
      <div class="service">
        <h3>Logo Design</h3>
        <p>Modern, creative logos tailored to your brand.</p>
      </div>
      <div class="service">
        <h3>Flyer & Poster Design</h3>
        <p>Eye-catching marketing materials for your events or promotions.</p>
      </div>
      <div class="service">
        <h3>Photo & Video Editing</h3>
        <p>High-quality editing to bring your visuals to life.</p>
      </div>
      <div class="service">
        <h3>Windows Installation</h3>
        <p>Professional Windows setup and configuration.</p>
      </div>
      <div class="service">
        <h3>Troubleshooting</h3>
        <p>Fix software issues and optimize your system performance.</p>
      </div>
    </div>
  </section>

  <section id="about" class="container">
    <h2>About ShingNoor</h2>
    <p>At ShingNoor, we blend creativity with technical skills to offer design and tech services that meet your every need. Whether you're a business, student, or content creator, we're here to help you shine.</p>
  </section>

  <section id="contact" class="container">
    <h2>Contact Us</h2>
    <p>Reach out on WhatsApp: <strong>+255 715 629 779</strong> <br>
       Or email: <strong>nurdinmohamedy25@gmail.com</strong></p>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 ShingNoor. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
-
