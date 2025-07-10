<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Stratosphere Aviation Detailing Services</title>
  
  <!-- SEO Meta Tags -->
  <meta name="description" content="Stratosphere Aviation Detailing Services - Premium aircraft cleaning and detailing services in SE Queensland and Northern NSW. Book your appointment today!"/>
  <meta name="keywords" content="aviation detailing, aircraft cleaning, SE Queensland, Northern NSW, aircraft polishing"/>
  <meta name="author" content="Stratosphere Aviation Detailing Services"/>
  
  <!-- Favicon -->
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />

  <style>
    :root {
      --primary-color: #000000; /* company black background */
      --accent-color: #004080;  /* blue for icons and highlights */
      --text-light: #ffffff;    /* white text */
      --text-dark: #cccccc;     /* light gray for subtle text */
      --bg-light: #111111;      /* very dark gray background for sections */
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: var(--primary-color);
      color: var(--text-light);
    }

    header {
      background: var(--primary-color);
      color: var(--text-light);
      padding: 40px 20px;
      text-align: center;
      position: relative;
    }

    header img {
      max-height: 80px;
      margin-bottom: 10px;
      filter: brightness(0) invert(1); /* invert logo if it has color to show on black */
    }

    header h1 {
      margin: 10px 0 5px;
      font-size: 2.5em;
      color: var(--text-light);
    }

    header p {
      margin: 0;
      font-size: 1.2em;
      color: var(--accent-color);
      font-weight: 600;
    }

    nav {
      background: var(--primary-color);
      padding: 12px;
      text-align: center;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      border-top: 1px solid var(--accent-color);
      border-bottom: 1px solid var(--accent-color);
    }

    nav a {
      color: var(--accent-color);
      text-decoration: none;
      font-weight: 600;
      padding: 8px 12px;
      transition: background 0.3s, color 0.3s;
      border-radius: 4px;
    }

    nav a:hover {
      background: var(--accent-color);
      color: var(--text-light);
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      background: var(--bg-light);
      border-radius: 10px;
      margin-bottom: 30px;
      box-shadow: 0 0 15px rgba(0, 64, 128, 0.6);
    }

    h2 {
      font-size: 2em;
      color: var(--accent-color);
      margin-bottom: 20px;
    }

    ul {
      padding-left: 20px;
      color: var(--text-light);
    }

    ul li {
      margin-bottom: 10px;
    }

    .photos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .photos img {
      width: 100%;
      max-width: 320px;
      border: 2px solid var(--accent-color);
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,64,128,0.8);
      transition: transform 0.3s;
    }

    .photos img:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0,64,128,1);
    }

    .book-now {
      background: var(--primary-color);
      color: var(--accent-color);
      text-align: center;
      padding: 40px 20px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 64, 128, 0.8);
      margin-bottom: 40px;
    }

    .book-now a {
      background: var(--accent-color);
      color: var(--text-light);
      text-decoration: none;
      font-weight: bold;
      padding: 12px 30px;
      border-radius: 6px;
      font-size: 1.1em;
      display: inline-block;
      margin-top: 20px;
      transition: background 0.3s, color 0.3s;
    }

    .book-now a:hover {
      background: var(--text-light);
      color: var(--accent-color);
    }

    footer {
      background: var(--primary-color);
      color: var(--text-light);
      text-align: center;
      padding: 25px 10px;
      font-size: 0.9em;
      border-top: 1px solid var(--accent-color);
    }

    footer a {
      color: var(--accent-color);
      margin: 0 10px;
      text-decoration: none;
      font-weight: 600;
    }

    .contact-icons {
      display: flex;
      justify-content: center;
      gap: 30px;
      font-size: 1.3em;
      margin-top: 20px;
    }

    .contact-icons a {
      color: var(--accent-color);
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    /* Contact Form Styling */
    form {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    form label {
      font-weight: 600;
      color: var(--text-light);
    }

    form input, form textarea {
      padding: 10px;
      font-size: 1em;
      border: 1px solid var(--accent-color);
      border-radius: 5px;
      background: var(--primary-color);
      color: var(--text-light);
      resize: vertical;
      transition: border-color 0.3s;
    }

    form input:focus, form textarea:focus {
      outline: none;
      border-color: var(--text-light);
      background: #002040;
    }

    form button {
      background: var(--accent-color);
      color: var(--primary-color);
      border: none;
      padding: 15px;
      font-size: 1.1em;
      font-weight: bold;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s;
    }

    form button:hover {
      background: var(--text-light);
    }

    /* Floating WhatsApp Button */
    .whatsapp-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 30px;
      right: 30px;
      background-color: #25d366;
      color: white;
      border-radius: 50%;
      text-align: center;
      font-size: 30px;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
      z-index: 1000;
      cursor: pointer;
      display: flex;
      justify-content: center;
      align-items: center;
      transition: background 0.3s;
    }

    .whatsapp-float:hover {
      background-color: #1ebe57;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
      .photos {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Stratosphere Logo" />
    <h1>Stratosphere Aviation Detailing Services</h1>
    <p>Premium aircraft detailing across SE QLD and Northern NSW</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#photos">Photos</a>
    <a href="#coverage">Coverage</a>
    <a href="#contact">Contact</a>
    <a href="#book">Book Now</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>Stratosphere Aviation Detailing provides elite cleaning and detailing for light aircraft, flying schools, FBOs, maintenance hangars and private owners across Southeast Queensland and Northern New South Wales. With rapid call-outs and a commitment to quality, we leave every aircraft gleaming and airworthy.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Interior & exterior aircraft cleaning</li>
      <li>Paintwork polishing and protection</li>
      <li>Brightwork & plexiglass polishing</li>
      <li>Cabin deodorising and deep cleaning</li>
      <li>FBO and flying school contracts</li>
      <li>Emergency / short-notice callouts</li>
    </ul>
  </section>

  <section id="photos" class="photos">
    <h2>Our Work</h2>
    <img src="photo1.jpg" alt="Aircraft 1" />
    <img src="photo2.jpg" alt="Aircraft 2" />
    <img src="photo3.jpg" alt="Aircraft 3" />
  </section>

  <section id="coverage">
    <h2>Service Coverage Areas</h2>
    <p>We proudly service the following regions:</p>
    <ul>
      <li>North New South Wales</li>
      <li>Southeast Queensland</li>
      <li>Toowoomba</li>
      <li>Archerfield</li>
      <li>Sunshine Coast</li>
    </ul>
  </section>

  <section id="book" class="book-now">
    <h2>Ready to Book?</h2>
    <p>We offer short-notice appointments and flexible scheduling. Contact us now to get your aircraft looking its best!</p>
    <a href="mailto:info@stratosphereaviationdetailing.com.au">Book Now via Email</a>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form action="https://formspree.io/f/mlekrpyw" method="POST">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required placeholder="Your full name" />

      <label for="email">Email:</label>
      <input type="email" id="email" name="_replyto" required placeholder="your.email@example.com" />

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required placeholder="Your message"></textarea>

      <!-- honeypot field to reduce spam -->
      <input type="text" name="_gotcha" style="display:none" />

      <button type="submit">Send Message</button>
    </form>

    <p style="margin-top: 20px; color: var(--text-light);">
      <strong>Email:</strong> <a href="mailto:info@stratosphereaviationdetailing.com.au" style="color: var(--accent-color);">info@stratosphereaviationdetailing.com.au</a><br />
      <strong>Phone:</strong> 0479 101 490<br />
      <strong>Location:</strong> Gold Coast, QLD, Australia
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Stratosphere Aviation Detailing Services. All rights reserved.</p>
    <div class="contact-icons">
      <a href="https://facebook.com/stratosphereaviationdetailingservices" target="_blank" aria-label="Facebook"><i class="fab fa-facebook" style="color: var(--accent-color);"></i> Facebook</a>
      <a href="https://instagram.com/stratosphereaviationdetailingservices" target="_blank" aria-label="Instagram"><i class="fab fa-instagram" style="color: var(--accent-color);"></i> Instagram</a>
    </div>
  </footer>

  <!-- Floating WhatsApp Button -->
  <a href="https://wa.me/61479101490" class="whatsapp-float" target="_blank" aria-label="Chat on WhatsApp">
    <i class="fab fa-whatsapp"></i>
  </a>

</body>
</html>
