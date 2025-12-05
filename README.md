<!DOCTYPE html>
<html lang="en">

<head>
     
    <meta charset="UTF-8" />
     
    <meta name="viewport" content="width=device-width, initial-scale=1" />
      <title>Simple eCommerce</title>
      <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f4f8;
            /* light background color */
            color: #333;
        }

        /* Navbar */
        .navbar {
            background-color: #0077cc;
            padding: 15px 20px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            margin-left: 15px;
            font-weight: bold;
        }

        .navbar a:hover {
            text-decoration: underline;
        }

        /* Main content */
        .container {
            max-width: 1000px;
            margin: 30px auto;
            padding: 0 20px;
        }

        .products {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .product {
            background: white;
            border-radius: 5px;
            box-shadow: 0 0 5px #ccc;
            width: 250px;
            padding: 15px;
            text-align: center;
        }

        .product img {
            width: 100%;
            height: 150px;
            object-fit: contain;
            margin-bottom: 10px;
        }

        .product h3 {
            margin: 10px 0 5px;
        }

        .product p {
            color: #666;
            font-size: 14px;
            margin-bottom: 10px;
        }

        .product .price {
            font-weight: bold;
            margin-bottom: 10px;
            color: #0077cc;
        }

        .product button {
            background-color: #0077cc;
            border: none;
            color: white;
            padding: 10px 15px;
            border-radius: 3px;
            cursor: pointer;
            font-weight: bold;
        }

        .product button:hover {
            background-color: #005fa3;
        }

        /* Footer */
        footer {
            background-color: #0077cc;
            color: white;
            text-align: center;
            padding: 15px 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            font-size: 14px;
        }
    </style>
</head>

<body>
    <nav class="navbar">
        <div class="logo">OnlineMart</div>
        <div>
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </div>
    </nav>

    <div class="container">
        <h1>Welcome to onlineMart!</h1>
        <div class="products">
            <div class="product">
                <img src="https://i.ibb.co/7JC5mgyf/image.png" alt="Product 1" />
                <h3>Product 1</h3>
                <p>High quality item for your needs.</p>
                <div class="price">$19.99</div>
                <button>Add to Cart</button>
            </div>

            <div class="product">
                <img src="https://i.ibb.co/8nCV7wmW/image.png" alt="Product 2" />
                <h3>Product 2</h3>
                <p>Comfortable and stylish.</p>
                <div class="price">$29.99</div>
                <button>Add to Cart</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9" alt="Product 3" />
                <h3>Product 3</h3>
                <p>Perfect for everyday use.</p>
                <div class="price">$24.99</div>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2025 onlineMart. All rights reserved.
    </footer>
</body>

</html>
# educationn
