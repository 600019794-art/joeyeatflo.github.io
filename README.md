# joeyeatflo.github.io
demo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Swim Club</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      line-height: 1.6;
      background: #f4fbff;
      color: #033047;
    }

    header {
      background: linear-gradient(135deg, #00a8e8, #0077b6);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
    }

    nav {
      background: #023e8a;
      text-align: center;
      padding: 12px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .about, .programs, .contact {
      margin-bottom: 40px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #0077b6;
    }

    footer {
      background: #023e8a;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background: white;
      color: #0077b6;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
    }

    .btn:hover {
      background: #caf0f8;
    }
  </style>
</head>
<body>

  <header>
    <h1>Blue Wave Swim Club</h1>
    <p>Dive into excellence, fitness, and fun.</p>
    <a href="#contact" class="btn">Join Now</a>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#programs">Programs</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>
      Welcome to Blue Wave Swim Club! We help swimmers of all ages improve their skills,
      build confidence in the water, and enjoy a healthy, active lifestyle.
    </p>
  </section>

  <section id="programs" class="programs">
    <h2>Our Programs</h2>
    <div class="cards">
      <div class="card">
        <h3>Beginner Lessons</h3>
        <p>Perfect for young swimmers learning water safety and basic techniques.</p>
      </div>
      <div class="card">
        <h3>Competitive Training</h3>
        <p>Advanced coaching for swimmers looking to improve speed and endurance.</p>
      </div>
      <div class="card">
        <h3>Adult Fitness Swim</h3>
        <p>Low-impact swim workouts designed for health, fitness, and stress relief.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: info@bluewaveswim.com</p>
    <p>Phone: (123) 456-7890</p>
    <p>Location: 123 Ocean Lane, Beach City</p>
  </section>

  <footer>
    <p>&copy; 2026 Blue Wave Swim Club. All rights reserved.</p>
  </footer>

</body>
</html>

If you want, I can also make you:

a more modern version
a school swim team version
or split it into index.html, style.css, and script.js
