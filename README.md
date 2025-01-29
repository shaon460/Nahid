<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Marketplace - Buy Various Items</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        nav {
            background-color: #444;
            padding: 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        .products-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 2rem;
        }

        .product-card {
            background: white;
            border-radius: 10px;
            padding: 1rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }

        .product-price {
            color: #e91e63;
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }

        .buy-button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        @media (max-width: 768px) {
            .products-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>MarketPlace Pro</h1>
        <p>Your One-Stop Shop for Various Items</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#electronics">Electronics</a></li>
            <li><a href="#fashion">Fashion</a></li>
            <li><a href="#home-decor">Home & Decor</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="products-container">
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 1" class="product-image">
            <h3>Wireless Headphones</h3>
            <p class="product-description">High-quality noise-canceling wireless headphones</p>
            <p class="product-price">$199.99</p>
            <button class="buy-button">Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 2" class="product-image">
            <h3>Designer Watch</h3>
            <p class="product-description">Luxury stainless steel wristwatch</p>
            <p class="product-price">$349.99</p>
            <button class="buy-button">Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 3" class="product-image">
            <h3>Smart Speaker</h3>
            <p class="product-description">Voice-controlled smart home assistant</p>
            <p class="product-price">$129.99</p>
            <button class="buy-button">Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 4" class="product-image">
            <h3>Modern Lamp</h3>
            <p class="product-description">Contemporary LED desk lamp</p>
            <p class="product-price">$89.99</p>
            <button class="buy-button">Add to Cart</button>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 MarketPlace Pro. All rights reserved. | <a href="#privacy" style="color: #fff;">Privacy Policy</a> | <a href="#terms" style="color: #fff;">Terms of Service</a></p>
    </footer>
</body>
</html>
