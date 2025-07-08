# Craze.gadgets
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gadget Hub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      gap: 1rem;
      padding: 0.5rem;
    }
    nav a {
      color: #fff;
      text-decoration: none;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      padding: 1rem;
    }
    .product {
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 1rem;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 4px;
    }
    .product button {
      background-color: #222;
      color: #fff;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 4px;
      cursor: pointer;
      margin-top: 0.5rem;
    }
    .product button:hover {
      background-color: #444;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #222;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gadget Hub</h1>
    <p>Your one-stop shop for cool tech</p>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Contact</a>
  </nav>
  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Smartwatch X">
      <h2>Smartwatch X</h2>
      <p>$199.99</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Wireless Earbuds Pro">
      <h2>Wireless Earbuds Pro</h2>
      <p>$99.99</p>
      <button>Buy Now</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x150" alt="Portable Speaker">
      <h2>Portable Speaker</h2>
      <p>$49.99</p>