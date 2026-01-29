<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>National Housing Portal</title>

  <!-- Basic CSS for mobile-friendly official look -->
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f4f6f8;
      color: #222;
    }

    header {
      background: #0b3c5d;
      color: white;
      padding: 16px;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: space-around;
      background: white;
      padding: 10px 0;
      border-bottom: 1px solid #ddd;
    }

    nav a {
      text-decoration: none;
      color: #0b3c5d;
      font-weight: bold;
      font-size: 14px;
    }

    .container {
      padding: 15px;
    }

    .house {
      background: white;
      border-radius: 6px;
      padding: 12px;
      margin-bottom: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .house img {
      width: 100%;
      border-radius: 5px;
    }

    .house h3 {
      margin: 10px 0 5px;
    }

    .house p {
      margin: 5px 0;
      font-size: 14px;
      color: #555;
    }

    .apply-btn {
      display: block;
      width: 100%;
      padding: 10px;
      background: #0b3c5d;
      color: white;
      border: none;
      border-radius: 4px;
      font-size: 15px;
      margin-top: 10px;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 15px;
      font-size: 13px;
      color: #555;
      border-top: 1px solid #ddd;
    }
  </style>
</head>

<body>

<header>
  <h2>National Housing Portal</h2>
  <p>Official Property Listings</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="login.html">Login</a>
  <a href="signup.html">Register</a>
</nav>

<div class="container">

  <!-- House Card 1 -->
  <div class="house">
    <img src="https://images.pexels.com/photos/1571460/pexels-photo-1571460.jpeg" alt="House in Wakiso">
    <h3>3 Bedroom House – Wakiso</h3>
    <p>Price: UGX 180,000,000</p>
    <p>Status: Available</p>
    <button class="apply-btn">Apply</button>
  </div>

  <!-- House Card 2 -->
  <div class="house">
    <img src="https://images.pexels.com/photos/279607/pexels-photo-279607.jpeg" alt="Modern House in Wakiso">
    <h3>2 Bedroom Apartment – Wakiso</h3>
    <p>Price: UGX 120,000,000</p>
    <p>Status: Available</p>
    <button class="apply-btn">Apply</button>
  </div>

</div>

<footer>
  © 2026 National Housing Authority. All rights reserved.
</footer>

</body>
</html>
