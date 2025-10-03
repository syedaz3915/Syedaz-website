<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Syedaz Import & Export</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
      scroll-behavior: smooth;
    }
    header {
      background: url('https://images.openai.com/static-rsc-1/ZR7f-L1qb1No0COYAAD3IRn2x6J9b2HSWwh0xG_xiDNyRkj7M9Q3MJ5nyYJzJavd_UB9b-9tZ5k9Bn6aKx2bv_dU-_cFkIrQAbmR44WBhNLKemUtCg87n_vmo2QbvRl7D9_lTAcfHlpo8sVkKaB7ag') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2.8rem;
      background: rgba(0,0,0,0.5);
      display: inline-block;
      padding: 10px 25px;
      border-radius: 5px;
    }
    nav {
      background: #0a3d62;
      padding: 14px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd32a;
    }
    .container {
      width: 90%;
      max-width: 1100px;
      margin: auto;
      padding: 50px 20px;
    }
    section {
      margin-bottom: 70px;
    }
    h2 {
      color: #0a3d62;
      margin-bottom: 20px;
      text-align: center;
    }
    .services p {
      font-size: 1.1rem;
      text-align: center;
      max-width: 800px;
      margin: auto;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      border-radius: 6px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    .contact-form {
      background: white;
      padding: 30px;
      border-radius: 6px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: auto;
    }
    .contact-form input, 
    .contact-form textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }
    .contact-form button {
      background: #0a3d62;
      color: white;
      border: none;
      padding: 12px 20px;
      font-size: 1rem;
      border-radius: 4px;
      cursor: pointer;
      width: 100%;
    }
    .contact-form button:hover {
      background: #1e3799;
    }
    footer {
      background: #1e3799;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Syedaz Import & Export</h1>
    <p>Reliable • On Time • Global Connections</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">

    <section id="services" class="services">
      <h2>Our Services</h2>
      <p>
        At <strong>Syedaz Import & Export</strong>, we specialize in importing and exporting all kinds of goods worldwide.  
        With years of expertise, we ensure timely services, competitive prices, and reliable global connections.  
        From containers shipped overseas to air freight deliveries, we cover it all with professionalism and efficiency.
      </p>
    </section>

    <section id="gallery" class="gallery">
      <h2>Gallery</h2>
      <img src="https://images.openai.com/static-rsc-1/1Fxnh3kVTgExStH1u0Fj3XsspnQkG0liQoY3KKLSd85keUSgXqEI9kjBSst4Mc32dSvoZGPCcfR1dbTMeGQ3Y2PdyjEE3c5YUG27Mo-I1rz8ufJF7SoI1SoWFVGs0THPuFCU-iSd5-VCgeX_kmJEfQ" alt="Container Ship">
      <img src="https://images.openai.com/static-rsc-1/MdTJ34GZS18EK_CgriNImHtQuWhY3xBB-6nB_Wi3RnP2LncW6B7eQqch-NyYYCOmee6n4mIuP3GciyzaloVySfV2t_yGZkousps6oKwv9UdSVqPtMh3Ij4dDYazlnQhNc_YhdRDbNhvXzbOTW_dQvw" alt="Air Freight">
      <img src="https://images.openai.com/static-rsc-1/ZR7f-L1qb1No0COYAAD3IRn2x6J9b2HSWwh0xG_xiDNyRkj7M9Q3MJ5nyYJzJavd_UB9b-9tZ5k9Bn6aKx2bv_dU-_cFkIrQAbmR44WBhNLKemUtCg87n_vmo2QbvRl7D9_lTAcfHlpo8sVkKaB7ag" alt="Cargo Ship">
      <img src="https://images.openai.com/static-rsc-1/_ZP9S45hHDFzMIG666UlcWbeMWjrY3YvD8vHf9zZK2AJuAGHPlVtUp3jrWbvmstuBd2CqTxcZq7aMCs6KYDboApNDKtgHmcUzw013kNVKn7bayCRv02TU-fGDmKn_Bc_44gaMP-3c8GdHSmI8KEqmA" alt="Air & Sea Shipping">
    </section>

    <section id="contact" class="contact">
      <h2>Contact Us</h2>
      <p style="text-align:center;"><strong>Location:</strong> Jersey City, New Jersey</p>
      <p style="text-align:center;"><strong>Phone:</strong> +1 (201) 920-8734</p>
      <p style="text-align:center;"><strong>Email:</strong> <a href="mailto:syedaz3915@gmail.com">syedaz3915@gmail.com</a></p>
      
      <div class="contact-form">
        <h3>Send us a message</h3>
        <form action="https://formspree.io/f/your-form-id" method="POST">
          <input type="text" name="name" placeholder="Your Name" required>
          <input type="email" name="_replyto" placeholder="Your Email" required>
          <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
          <button type="submit">Send Message</button>
        </form>
      </div>
    </section>

  </div>

  <footer>
    &copy; 2025 Syedaz Import & Export. All Rights Reserved.
  </footer>

</body>
</html>
