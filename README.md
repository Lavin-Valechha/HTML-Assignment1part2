<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Customized T-shirt Order Form</title>
</head>
<body>
    <h1>Customized T-shirt Order Form</h1>
    <form action="process_order.php" method="POST">
        <div>
            <label for="tagline">Tagline on the Shirt:</label>
            <input type="text" id="tagline" name="tagline" required>
        </div>

        <div>
            <label for="color">Shirt Color:</label>
            <select id="color" name="color">
                <option value="red">Red</option>
                <option value="blue">Blue</option>
                <option value="green">Green</option>
                <option value="black">Black</option>
                <option value="white">White</option>
            </select>
        </div>

        <div>
            <label>Shirt Size:</label>
            <input type="radio" id="size-s" name="size" value="S" required>
            <label for="size-s">S</label>
            <input type="radio" id="size-m" name="size" value="M">
            <label for="size-m">M</label>
            <input type="radio" id="size-l" name="size" value="L">
            <label for="size-l">L</label>
        </div>

        <div>
            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" name="quantity" min="1" required>
        </div>

        <div>
            <label for="delivery-date">Delivery Date:</label>
            <input type="date" id="delivery-date" name="delivery-date" required>
        </div>

        <div>
            <label for="delivery-details">Other Delivery Details:</label>
            <textarea id="delivery-details" name="delivery-details" rows="4"></textarea>
        </div>

        <div>
            <button type="submit">Place Order</button>
        </div>
    </form>
</body>
</html>
