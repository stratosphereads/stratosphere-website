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
      padding: 40px 20px 60px;
      text-align: center;
      position: relative;
    }

    .header-photo {
      width: 100%;
      max-height: 350px;
      object-fit: cover;
      display: block;
    }

    header h1 {
      margin: 40px 0 10px;
      font-size: 3em;
    }

    header p {
      margin: 0;
      font-size: 1.3em;
    }

    details {
      margin: 30px auto;
      background: #111;
      padding: 15px;
      border-radius: 10px;
      border: 1px solid #333;
      max-width: 1000px;
    }

    summary {
      cursor: pointer;
      font-size: 1.45em; /* slightly smaller to keep Service Coverage on one line */
      font-weight: bold;
      color: var(--accent-color);
      margin-bottom: 10px;
    }

    summary h2 {
      display: inline;
      margin: 0;
    }

    details[open] summary::after {
      content: "";
      display: block;
      margin-top: 10px;
    }

    #home {
      text-align: center;
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
      box-shadow: 0 0 8px rgba(255,255,255,0.4);
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
      .photos {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" />
</head>
<body>
  <a class="whatsapp-button" href="https://wa.me/61479101490" target="_blank" title="Chat with us on WhatsApp">
    <i class="fab fa-whatsapp"></i>
  </a>

  <header>
    <img src="new-header.jpg" alt="Stratosphere Jet Polished in Hangar" class="header-photo">
    <h1>Stratosphere Aviation Detailing</h1>
    <p>Premium aircraft detailing across SE QLD and Northern NSW</p>
  </header>

  <details id="home" open>
    <summary><h2>Welcome</h2></summary>
    <br>
    <div style="text-align:center">
      <p><strong>Welcome to Stratosphere Aviation Detailing</strong></p>
      <p><em>Where Perfection Takes Flight.</em></p>
      <p>
        We offer premium aircraft detailing across Southeast Queensland and Northern NSW.<br>
        Use the menu to explore our services, photos, coverage areas, and booking options.
      </p>
    </div>
  </details>

  <details id="services">
    <summary><h2>Our Services</h2></summary>
    <br>
    <ul>
      <li>Interior & exterior aircraft cleaning</li>
      <li>Paintwork polishing and protection</li>
      <li>Brightwork & plexiglass polishing</li>
      <li>Cabin deodorising and deep cleaning</li>
      <li>FBO and flying school contracts</li>
      <li>Emergency / short-notice callouts</li>
    </ul>
    <div class="services-image">
      <img src="services-photo.jpg" alt="Aircraft Detailing Services">
    </div>
  </details>

  <details id="photos">
    <summary><h2>Our Work</h2></summary>
    <br>
    <div class="photos">
      <img src="ourwork1.jpg" alt="Our Work 1">
      <img src="ourwork2.jpg" alt="Our Work 2">
      <img src="ourwork3.jpg" alt="Our Work 3">
      <img src="ourwork4.jpg" alt="Our Work 4">
      <img src="ourwork5.jpg" alt="Our Work 5">
    </div>
  </details>

  <details id="products">
    <summary><h2>Our Products</h2></summary>
    <div class="products-image">
      <img src="product1.jpg" alt="Detailing Product">
    </div>
  </details>

  <details id="coverage">
    <summary><h2>Service Coverage</h2></summary>
    <br>
    <p>We proudly service North New South Wales and Southeast Queensland including Toowoomba, Archerfield, and the Sunshine Coast.</p>
    <div class="services-image">
      <img src="coverage-map.jpg" alt="Service Coverage Map">
    </div>
  </details>

  <details id="contact">
    <summary><h2>Contact Us</h2></summary>
    <br>
    <p><strong>Email:</strong> <a href="mailto:stratosphereads@yahoo.com">stratosphereads@yahoo.com</a></p>
    <p><strong>Phone:</strong> <a href="tel:+61479101490">0479 101 490</a></p>
    <p><strong>Facebook:</strong> <a href="https://www.facebook.com/profile.php?id=61577069496524" target="_blank">Stratosphere Aviation Detailing Services</a></p>
    <p><strong>Instagram:</strong> <a href="https://www.instagram.com/gary.alandisney/" target="_blank">@gary.alandisney</a></p>
  </details>

  <details id="book" class="book-now">
    <summary><h2>Book a Service</h2></summary>
    <br>
    <p>Ready to give your aircraft the shine it deserves? Book now!</p>
    <a href="mailto:stratosphereads@yahoo.com">Book via Email</a>
  </details>

  <footer>
    <p><strong>Stratosphere Aviation Detailing Services</strong></p>
    <p>
      <a href="mailto:stratosphereads@yahoo.com">stratosphereads@yahoo.com</a> |
      <a href="https://stratosphereaviationdetailing.com.au" target="_blank">stratosphereaviationdetailing.com.au</a>
    </p>
    <p>ABN: 83623559197</p>
    <p>Servicing Southeast Queensland & Northern New South Wales</p>
    <p>
      <a href="https://www.facebook.com/profile.php?id=61577069496524" target="_blank">Facebook</a> |
      <a href="https://www.instagram.com/gary.alandisney/" target="_blank">Instagram</a>
    </p>
  </footer>
</body>
</html>
