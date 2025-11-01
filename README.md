# BALWANT-YADAV
All electronic goods and retail and wholesale 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  Chandrika Enterprises | Electrical Retail & Services</title>
  <style>
    body {
      font-family: "Segoe UI", Arial, sans-serif;
      margin: 0;
      background-color: #f7f9fc;
      color: #333;
    }

    header {
      background-color: #004aad;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #00367a;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #004aad;
      border-bottom: 2px solid #004aad;
      display: inline-block;
      margin-bottom: 15px;
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
        url("https://images.unsplash.com/photo-1569420074762-1efb7a66bfa6?auto=format&fit=crop&w=1350&q=80");
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 2.5em;
      margin: 0;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .contact form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    input, textarea, button {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
    }

    button {
      background-color: #004aad;
      color: white;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: #00367a;
    }

    footer {
      background-color: #00367a;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Chandrika Enterprises</h1>
    <p>Electrical Retail | Wholesale | Services</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="hero">
    <h1>Your Trusted Partner for Electrical Solutions</h1>
    <p>Supplying quality electrical products and services for homes, businesses, and industries.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>
      Chandrika Enterprises is a leading name in electrical retail, wholesale, and services. 
      We provide top-quality electrical components, tools, and professional installation 
      and maintenance services. Our commitment to reliability and customer satisfaction has 
      earned us the trust of countless clients in the region.
    </p>
  </section>

  <section id="services">
    <h2>Our Products & Services</h2>
    <div class="services">
      <div class="card">
        <h3>Retail & Wholesale</h3>
        <p>We supply electrical products, wires, switches, panels, and lighting solutions for homes, offices, and industries.</p>
      </div>
      <div class="card">
        <h3>Electrical Installation</h3>
        <p>Expert wiring, lighting, and setup services for residential and commercial projects.</p>
      </div>
      <div class="card">
        <h3>Maintenance & Repair</h3>
        <p>Reliable electrical maintenance and fault repair by our experienced technicians.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p>📍 Address: (Rakhiya Barahata Captainganj Basti)</p>
    <p>📞 Phone: (7905651485)</p>
    <p>✉️ Email: (sy113374@gmail.com)</p>
  </section>

  <footer>
    &copy; 2025 Chandrika Enterprises. All rights reserved.
  </footer>

</body>
</html>