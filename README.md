<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Stratosphere Aviation Detailing</title>
  <meta name="description" content="Premium aircraft detailing across Southeast Queensland and Northern NSW. Specialising in private, training, and FBO contracts." />
  <link rel="icon" href="favicon.ico" type="image/x-icon">
  <style>
    :root {
      --primary-color: #000000;
      --accent-color: #007bff;
      --text-light: #ffffff;
      --text-dark: #ffffff;
      --bg-light: #000000;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: var(--bg-light);
      color: var(--text-light);
    }

    header {
      background: var(--primary-color);
      color: var(--text-light);
      padding: 80px 20px 60px;
      text-align: center;
      position: relative;
    }

    header img {
      max-height: 120px;
      margin-bottom: 20px;
      background-color: transparent;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    header h1 {
      margin: 10px 0 10px;
      font-size: 3em;
    }

    header p {
      margin: 0;
      font-size: 1.3em;
    }

    nav {
      background: var(--primary-color);
      padding: 12px;
      text-align: center;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    nav a {
      color: var(--text-light);
      text-decoration: none;
      font-weight: 600;
      padding: 8px 12px;
      transition: background 0.3s;
    }

    nav a:hover {
      background: var(--accent-color);
      color: var(--text-light);
      border-radius: 5px;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      font-size: 2em;
      color: var(--accent-color);
      margin-bottom: 20px;
    }

    ul {
      padding-left: 20px;
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
      border: 2px solid #ccc;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(255,255,255,0.1);
      transition: transform 0.3s;
    }

    .photos img:hover {
      transform: scale(1.03);
    }

    .services-image, .products-image {
      text-align: center;
      margin-top: 30px;
    }

    .services-image img, .products-image img {
      width: 100%;
      max-width: 700px;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.5);
    }

    .book-now {
      background: var(--primary-color);
      color: var(--text-light);
      text-align: center;
      padding: 40px 20px;
      border-radius: 10px;
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
    }

    .contact-icons {
      display: flex;
      justify-content: center;
      gap: 30px;
      font-size: 1.2em;
      margin-top: 20px;
    }

    .contact-icons a {
      color: var(--accent-color);
      text-decoration: none;
    }

    .whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25d366;
      color: white;
      border-radius: 50%;
      padding: 15px;
      font-size: 1.5em;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      z-index: 1000;
    }

    .whatsapp-button:hover {
      background-color: #1ebe5d;
    }

    footer {
      background: var(--primary-color);
      color: var(--text-light);
      text-align: center;
      padding: 25px 10px;
      font-size: 0.9em;
    }

    footer a {
      color: var(--accent-color);
      margin: 0 10px;
      text-decoration: none;
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
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="sha512-p9xUtgJwGq4T3tB6MTI1+iV5X1p3BoH4FfL1KUt5kPeQ3w05GVn3T6kCAXq/udfrvEcjP13TivCEuN+eL+Hedg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
  <a class="whatsapp-button" href="https://wa.me/61479101490" target="_blank" title="Chat with us on WhatsApp">
    <i class="fab fa-whatsapp"></i>
  </a>

  <header>
    <img src="logo.png" alt="Stratosphere Logo">
    <h1>Stratosphere Aviation Detailing</h1>
    <p>Premium aircraft detailing across SE QLD and Northern NSW</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#photos">Photos</a>
    <a href="#products">Products</a>
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
    <div class="services-image">
      <img src="services-photo.jpg" alt="Stratosphere Aviation Services">
    </div>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <p>We use and recommend professional-grade aviation-safe products for cleaning, polishing, and protecting your aircraft surfaces.</p>
    <div class="products-image">
      <img src="products-photo.jpg" alt="Detailing Products">
    </div>
  </section>

  <section id="photos" class="photos">
    <h2>Our Work</h2>
    <img src="photo1.jpg" alt="Aircraft 1">
    <img src="photo2.jpg" alt="Aircraft 2">
    <img src="photo3.jpg" alt="Aircraft 3">
  </section>

  <section id="coverage">
    <h2>Service Coverage Areas</h2>
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
    <a href="mailto:stratosphereads@yahoo.com">Book Now via Email</a>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form action="https://formspree.io/f/mlekrpyw" method="POST">
      <label>Name:<br><input type="text" name="name" required></label><br><br>
      <label>Email:<br><input type="email" name="email" required></label><br><br>
      <label>Message:<br><textarea name="message" rows="5" required></textarea></label><br><br>
      <button type="submit">Send Message</button>
    </form>
    <p><strong>Phone:</strong> 0479 101 490</p>
    <p><strong>Email:</strong> <a href="mailto:stratosphereads@yahoo.com">stratosphereads@yahoo.com</a></p>
    <p><strong>Location:</strong> Gold Coast, QLD, Australia</p>
  </section>

  <footer>
    <p>&copy; 2025 Stratosphere Aviation Detailing. All rights reserved.</p>
    <div class="contact-icons">
      <a href="https://www.facebook.com/profile.php?id=61577069496524" target="_blank"><i class="fab fa-facebook"></i> Facebook</a>
      <a href="https://www.instagram.com/gary.alandisney/" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
    </div>
  </footer>
</body>
</html>
