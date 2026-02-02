<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pro Learning Academy</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f6f9;
      color: #222;
    }

    header {
      background: #0a58ca;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 32px;
    }

    header p {
      margin-top: 8px;
      font-size: 16px;
    }

    nav {
      background: #063b8f;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 12px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .hero {
      text-align: center;
    }

    .hero h2 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .hero button {
      padding: 12px 25px;
      background: #0a58ca;
      border: none;
      color: white;
      font-size: 16px;
      border-radius: 6px;
      cursor: pointer;
    }

    .hero button:hover {
      background: #084298;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .card h3 {
      margin-top: 0;
      color: #0a58ca;
    }

    .price {
      font-size: 20px;
      font-weight: bold;
      margin-top: 10px;
    }

    footer {
      background: #063b8f;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    .contact p {
      font-size: 18px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 24px;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Pro Learning Academy</h1>
  <p>Learn Skills. Build Your Future.</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#courses">Courses</a>
  <a href="#pricing">Pricing</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home" class="hero">
  <h2>India’s Trusted Online Learning Platform</h2>
  <p>Job-ready skills sikhye experts ke sath</p>
  <br>
  <button onclick="alert('Courses section dekhiye')">Explore Courses</button>
</section>

<section id="courses">
  <h2>Popular Courses</h2>

  <div class="cards">
    <div class="card">
      <h3>Basic Computer Course</h3>
      <p>Computer fundamentals, MS Office, Internet</p>
    </div>

    <div class="card">
      <h3>Digital Marketing</h3>
      <p>SEO, Social Media, Ads, Freelancing</p>
    </div>

    <div class="card">
      <h3>Web Development</h3>
      <p>HTML, CSS, JavaScript, Website Design</p>
    </div>
  </div>
</section>

<section id="pricing">
  <h2>Course Pricing</h2>

  <div class="cards">
    <div class="card">
      <h3>Starter Plan</h3>
      <p>1 Course Access</p>
      <div class="price">₹499</div>
    </div>

    <div class="card">
      <h3>Pro Plan</h3>
      <p>All Courses Access</p>
      <div class="price">₹999</div>
    </div>

    <div class="card">
      <h3>Premium Plan</h3>
      <p>Courses + Support</p>
      <div class="price">₹1999</div>
    </div>
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>📞 Phone: <b>8102911143</b></p>
  <p>📧 Email: <b>rahulpatel.ji1930@gmail.com</b></p>
</section>

<footer>
  <p>© 2026 Pro Learning Academy. All Rights Reserved.</p>
</footer>

</body>
</html>
