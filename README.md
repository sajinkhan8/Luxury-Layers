# Luxury-Layers
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Luxury Layers | Clothing Brand</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Helvetica Neue', sans-serif;
    }

    body {
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #000;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 28px;
      font-weight: 700;
      letter-spacing: 2px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1542068829-1115f7259450') no-repeat center center/cover;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 20px;
      max-width: 600px;
    }

    .section {
      padding: 60px 40px;
      text-align: center;
    }

    .section h3 {
      font-size: 32px;
      margin-bottom: 30px;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .product {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      width: 250px;
      padding: 20px;
      transition: 0.3s;
    }

    .product:hover {
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      border-radius: 8px;
    }

    .product h4 {
      margin: 15px 0 10px;
    }

    .product p {
      color: #666;
      font-size: 14px;
    }

    .about, .contact {
      max-width: 800px;
      margin: auto;
    }

    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    form button {
      background-color: #000;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.3s;
    }

    form button:hover {
      background-color: #333;
    }

    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 25px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .hero h2 {
        font-size: 36px;
      }

      .products {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Luxury Layers</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div>
      <h2>Style That Speaks Power</h2>
      <p>Discover premium streetwear and contemporary fashion designed to make a statement.</p>
    </div>
  </section>

  <section class="section" id="products">
    <h3>Featured Products</h3>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246" alt="T-Shirt" />
        <h4>Classic Black Tee</h4>
        <p>$35</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1602810316579-6c41873ca59d" alt="Jacket" />
        <h4>Oversized Denim Jacket</h4>
        <p>$75</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1552374196-c4e7ffc6e126" alt="Hoodie" />
        <h4>Essential Hoodie</h4>
        <p>$60</p>
      </div>
    </div>
  </section>

  <section class="section about" id="about">
    <h3>About Us</h3>
    <p>Luxury Layers is a Dhaka-based clothing brand blending luxury, comfort, and modern design. We focus on high-quality materials, minimalist aesthetics, and bold statements. Join the movement of confidence, expression, and luxury in layers.</p>
  </section>

  <section class="section contact" id="contact">
    <h3>Contact Us</h3>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Luxury Layers. All rights reserved.</p>
  </footer>

</body>
</html>
