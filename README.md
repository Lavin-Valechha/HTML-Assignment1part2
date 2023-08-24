<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>T-Shirt Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #35424a;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 1rem;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            border-radius: 5px;
        }

        .product {
            display: flex;
            align-items: center;
            margin-bottom: 1rem;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .product img {
            max-width: 100px;
            margin-right: 1rem;
        }
    </style>
</head>

<body>
    <header>
        <h1>T-Shirt Store</h1>
    </header>

    <div class="container">
        <div class="product">
            <img src="tshirt1.jpg" alt="T-Shirt 1">
            <div>
                <h2>T-Shirt Model 1</h2>
                <p>High-quality cotton T-shirt.</p>
                <p>Price: $19.99</p>
                <button>Add to Cart</button>
            </div>
        </div>

        <div class="product">
            <img src="tshirt2.jpg" alt="T-Shirt 2">
            <div>
                <h2>T-Shirt Model 2</h2>
                <p>Soft and comfortable fit.</p>
                <p>Price: $24.99</p>
                <button>Add to Cart</button>
            </div>
        </div>

        <!-- Add more products as needed -->
    </div>
</body>

</html>
