# Uniqueworld
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unique World</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f9;
        }
        header {
            background-color: #fff;
            padding: 20px 10%;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #333;
        }
        nav {
            float: right;
        }
        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 15px;
            font-size: 1rem;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .hero {
            text-align: center;
            margin-top: 20px;
        }
        .hero h1 {
            font-size: 2.5rem;
            color: #333;
        }
        .hero p {
            font-size: 1.2rem;
            color: #666;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 30px;
        }
        .product {
            background-color: #fff;
            width: 32%;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            border-radius: 5px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .product:hover {
            transform: translateY(-5px);
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product-info {
            padding: 15px;
            text-align: center;
        }
        .product-info h3 {
            font-size: 1.3rem;
            color: #333;
            margin: 10px 0;
        }
        .product-info p {
            font-size: 1rem;
            color: #777;
            margin-bottom: 15px;
        }
        .buy-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .buy-button:hover {
            background-color: #0056b3;
        }
        .about {
            margin: 50px 0;
            text-align: center;
        }
        .about h2 {
            font-size: 2rem;
            color: #333;
        }
        .about p {
            font-size: 1rem;
            color: #666;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        .contact {
            text-align: center;
            margin: 50px 0;
        }
        .contact h2 {
            font-size: 2rem;
            color: #333;
        }
        .contact form {
            max-width: 600px;
            margin: 0 auto;
        }
        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact button {
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .contact button:hover {
            background-color: #0056b3;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
            transition: color 0.3s;
        }
        footer a:hover {
            color: #007bff;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">Unique World</div>
            <nav>
                <a href="#home">Home</a>
                <a href="#products">Products</a>
                <a href="#about">About</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <div class="hero" id="home">
        <h1>Welcome to Unique World</h1>
        <p>Discover reviews of amazing products from Amazon.</p>
    </div>

    <div class="container">
        <div class="products" id="products">
            <div class="product">
                <img src="https://via.placeholder.com/400x300" alt="Product 1">
                <div class="product-info">
                    <h3>Product 1</h3>
                    <p>Great features and quality.</p>
                    <a href="https://www.amazon.com" class="buy-button" target="_blank">Buy Now</a>
                </div>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/400x300" alt="Product 2">
                <div class="product-info">
                    <h3>Product 2</h3>
                    <p>Best in class and affordable.</p>
                    <a href="https://www.amazon.com" class="buy-button" target="_blank">Buy Now</a>
                </div>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/400x300" alt="Product 3">
                <div class="product-info">
                    <h3>Product 3</h3>
                    <p>Innovative design and functionality.</p>
                    <a href="https://www.amazon.com" class="buy-button" target="_blank">Buy Now</a>
                </div>
            </div>
        </div>

        <div class="about" id="about">
            <h2>About Unique World</h2>
            <p>Welcome to Unique World, your ultimate destination for discovering and reviewing the best products available on Amazon. Our mission is to
