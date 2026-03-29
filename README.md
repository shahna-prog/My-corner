<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Shop</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #f8f8f8;
}

header {
  background: #111;
  color: white;
  padding: 20px;
  text-align: center;
  font-size: 26px;
  letter-spacing: 3px;
}

.banner {
  background: linear-gradient(to right, #000, #333);
  color: white;
  padding: 40px;
  text-align: center;
}

.banner h1 {
  margin: 0;
  font-size: 32px;
}

.container {
  padding: 30px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 25px;
}

.product {
  background: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
  transition: 0.3s;
}

.product:hover {
  transform: translateY(-8px);
}

.product img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.product-content {
  padding: 15px;
  text-align: center;
}

.price {
  color: #27ae60;
  font-size: 18px;
  margin: 10px 0;
  font-weight: bold;
}

.btn {
  display: inline-block;
  padding: 10px 18px;
  background: black;
  color: white;
  border-radius: 6px;
  text-decoration: none;
  transition: 0.3s;
}

.btn:hover {
  background: #444;
}

footer {
  background: #111;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}
</style>
</head>

<body>

<header>🛍️ LUXURY SHOP</header>

<div class="banner">
  <h1>Exclusive Collection</h1>
  <p>Simple. Elegant. Affordable.</p>
</div>

<div class="container">

  <div class="product">
    <img src="https://via.placeholder.com/300">
    <div class="product-content">
      <h3>Stylish Bag</h3>
      <p class="price">₹799</p>
      <a class="btn" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20Stylish%20Bag">Buy Now</a>
    </div>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/300">
    <div class="product-content">
      <h3>Classic Watch</h3>
      <p class="price">₹1299</p>
      <a class="btn" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20Classic%20Watch">Buy Now</a>
    </div>
  </div>

  <div class="product">
    <img src="https://via.placeholder.com/300">
    <div class="product-content">
      <h3>Trendy Shoes</h3>
      <p class="price">₹999</p>
      <a class="btn" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20Trendy%20Shoes">Buy Now</a>
    </div>
  </div>

</div>

<footer>
  © 2026 My Shop | Contact on WhatsApp
</footer>

</body>
</html>