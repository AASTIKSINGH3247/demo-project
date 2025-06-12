<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Travel & Shop | Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <a href="booking.html" style="text-decoration: none; color: inherit;">
  <div class="card">
    <img src="https://cdn-icons-png.flaticon.com/512/69/69979.png" alt="Bus Booking">
    <h3>Bus Tickets</h3>
    <p>Find the best bus routes and book instantly.</p>
  </div>
</a>

  <style>a
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: #f2f4f8;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #0a74da;
      color: white;
      padding: 1.5rem 0;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    header .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }
    header h1 {
      font-size: 2rem;
      font-weight: 800;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 2rem;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover no-repeat;
      height: 500px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
    }
    .hero .hero-content {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 2rem;
      border-radius: 10px;
    }
    .hero h2 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.25rem;
    }
    .sections {
      padding: 4rem 0;
      background: white;
    }
    .sections .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }
    .card {
      background: #ffffff;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      padding: 2rem;
      text-align: center;
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 80px;
      margin-bottom: 1rem;
    }
    .card h3 {
      margin-bottom: 0.5rem;
    }
    .card p {
      font-size: 0.95rem;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 2rem 0;
      margin-top: 4rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Travel & Shop</h1>
      <nav>
        <a href="index.html">Home</a>
        <a href="booking.html">Booking</a>
        <a href="shop.html">Shop</a>
        <a href="login.html">Login</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Explore the World & Shop Your Style</h2>
      <p>Book your travel and shop the best items — all in one place</p>
    </div>
  </section>

  <section class="sections">
    <div class="container">
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/69/69979.png" alt="Bus Booking">
        <h3>Bus Tickets</h3>
        <p>Find the best bus routes and book instantly.</p>
      </div>
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/747/747310.png" alt="Flight Booking">
        <h3>Flight Tickets</h3>
        <p>Compare flight prices and travel comfortably.</p>
      </div>
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046771.png" alt="Cab Booking">
        <h3>Cab Booking</h3>
        <p>Book cabs locally or for outstation trips.</p>
      </div>
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/2738/2738347.png" alt="Hotel Booking">
        <h3>Hotel Booking</h3>
        <p>Stay at top-rated hotels at affordable rates.</p>
      </div>
      <div class="card">
        <img src="https://cdn-icons-png.flaticon.com/512/892/892458.png" alt="E-Commerce">
        <h3>Online Shopping</h3>
        <p>Shop clothing, watches and more from trusted brands.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Travel & Shop. Crafted with passion.</p>
  </footer>
</body>
</html>
