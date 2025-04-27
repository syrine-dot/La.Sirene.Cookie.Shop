<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>La Sirène Cookie Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #f8c8d4;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 2.5em;
            margin: 0;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 20px;
            overflow: hidden;
            width: 280px;
        }

        .product img {
            width: 100%;
            height: auto;
            border-bottom: 2px solid #f8c8d4;
        }

        .product-info {
            padding: 15px;
            text-align: center;
        }

        .product-info h2 {
            color: #f8c8d4;
            font-size: 1.8em;
        }

        .product-info p {
            font-size: 1.1em;
            margin: 10px 0;
        }

        .product-info .price {
            font-size: 1.5em;
            color: #ff6f61;
            margin-bottom: 15px;
        }

        .order-btn {
            background-color: #ff6f61;
            color: white;
            padding: 10px;
            font-size: 1.2em;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            transition: background-color 0.3s;
        }

        .order-btn:hover {
            background-color: #e45c53;
        }

        footer {
            background-color: #f8c8d4;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>La Sirène Cookie Shop</h1>
        <p>Your one-stop shop for delightful cookies, cupcakes, and chocolate treats!</p>
    </header>

    <div class="container">
        <div class="product">
            <img src="https://yourimageurl.com/sweetheart-bliss.jpg" alt="Sweetheart Bliss">
            <div class="product-info">
                <h2>Sweetheart Bliss</h2>
                <p>Fresh strawberries dipped in rich chocolate.</p>
                <div class="price">$15.99</div>
                <button class="order-btn">Order Now</button>
            </div>
        </div>

        <div class="product">
            <img src="https://yourimageurl.com/choco-berry-delight.jpg" alt="Choco-Berry Delight">
            <div class="product-info">
                <h2>Choco-Berry Delight</h2>
                <p>Strawberries and chocolate-filled cookies in one sweet bundle!</p>
                <div class="price">$18.99</div>
                <button class="order-btn">Order Now</button>
            </div>
        </div>

        <!-- Add more products as needed -->
    </div>

    <footer>
        <p>La Sirène Cookie Shop | <a href="mailto:syrinetouati25@gmail.com">Contact Us</a></p>
    </footer>
</body>
</html>
![La Sirene Cookie Shop](https://github.com/user-attachments/assets/53c440e3-45c5-4f7a-ba00-c7b0eac858f1)
