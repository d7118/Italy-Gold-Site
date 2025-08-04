<!-- Italian Gold Business Website: OroLusso -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OroLusso - Italian Gold</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #fdf8f2;
      color: #333;
    }
    header {
      background-color: #111;
      color: #fff;
      padding: 1.5rem;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5rem;
      color: #ffd700;
    }
    nav {
      background-color: #333;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
    }
    nav a {
      color: #ffd700;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 1200px;
      margin: auto;
    }
    .hero {
      background-image: url('https://images.unsplash.com/photo-1600356052375-4bb6e0560f01');
      background-size: cover;
      background-position: center;
      height: 400px;
      position: relative;
      color: #fff;
    }
    .hero h2 {
      position: absolute;
      bottom: 2rem;
      left: 2rem;
      font-size: 3rem;
      font-family: 'Playfair Display', serif;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .product {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 1rem;
      width: 250px;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }
    footer {
      background-color: #111;
      color: #aaa;
      text-align: center;
      padding: 2rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>OroLusso</h1>
    <p>Crafting Timeless Elegance in Gold - Made in Italy</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <h2>Pure Italian Luxury</h2>
  </section>

  <section id="products">
    <h2>Our Collection</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1598454447119-cdb5c8b0a35f" alt="Gold Ring">
        <h3>Roma Ring</h3>
        <p>18K handcrafted gold ring with classic Roman detail.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1622519407090-0e55a3b9520b" alt="Gold Necklace">
        <h3>Milano Chain</h3>
        <p>Elegant 24K gold chain inspired by Milan fashion.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1581578017424-8b1a2d7d4ec8" alt="Gold Bracelet">
        <h3>Venetian Cuff</h3>
        <p>Refined 22K bracelet with a touch of Venice elegance.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About OroLusso</h2>
    <p>OroLusso was founded in the heart of Florence with a mission to bring timeless Italian craftsmanship to the world. We source only the finest gold and work with master artisans who infuse every piece with centuries of tradition and beauty.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@orolusso.it</p>
    <p>Phone: +39 055 1234567</p>
    <p>Visit us in Florence, Italy</p>
  </section>

  <footer>
    <p>&copy; 2025 OroLusso. All rights reserved.</p>
  </footer>
</body>
</html>
# Italy-Gold-Site
