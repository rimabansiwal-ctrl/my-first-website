# my-first-website
My first website 

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>My Flower Shop</title>
<style>
  body { font-family: Arial; margin:0; background:#fffaf7; color:#333; }
  header { background:#d6336c; color:#fff; padding:20px; text-align:center; }
  header h1 { margin:0; font-size:26px; }
  .hero { text-align:center; padding:40px 20px; }
  .hero h2 { font-size:24px; }
  .hero p { color:#666; }
  .products { padding:20px; max-width:600px; margin:auto; }
  .card { background:#fff; border-radius:12px; padding:16px; margin-bottom:16px;
          box-shadow:0 2px 8px rgba(0,0,0,.08); }
  .card h3 { margin:0 0 6px; }
  .price { color:#d6336c; font-weight:bold; font-size:18px; }
  .btn { display:inline-block; background:#d6336c; color:#fff; padding:10px 20px;
         border-radius:20px; text-decoration:none; margin-top:8px; }
  footer { text-align:center; padding:20px; color:#888; font-size:14px; }
</style>
</head>
<body>

<header>
  <h1>🌸 My Flower Shop</h1>
  <p style="margin:6px 0 0;">Fresh flowers delivered to your door</p>
</header>

<div class="hero">
  <h2>Beautiful Bouquets for Every Occasion</h2>
  <p>Order today, delivered tomorrow</p>
  <a href="https://wa.me/919999999999" class="btn">Order on WhatsApp</a>
</div>

<div class="products">

  <div class="card">
    <h3>🌹 Rose Bouquet</h3>
    <p>12 fresh red roses, beautifully wrapped</p>
    <div class="price">₹799</div>
    <a href="https://wa.me/919999999999?text=Hi%2C%20I%20want%20the%20Rose%20Bouquet" class="btn">Order</a>
  </div>

  <div class="card">
    <h3>💐 Mixed Flower Basket</h3>
    <p>A colorful mix of seasonal flowers</p>
    <div class="price">₹1,299</div>
    <a href="https://wa.me/919999999999?text=Hi%2C%20I%20want%20the%20Mixed%20Flower%20Basket" class="btn">Order</a>
  </div>

  <div class="card">
    <h3>🎂 Chocolate Cake</h3>
    <p>Rich chocolate truffle cake, 500g</p>
    <div class="price">₹649</div>
    <a href="https://wa.me/919999999999?text=Hi%2C%20I%20want%20the%20Chocolate%20Cake" class="btn">Order</a>
  </div>

</div>

<footer>
  © 2025 My Flower Shop · Call: +91 99999 99999
</footer>

</body>
</html>