<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Women's Clothing Sale</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #fdfdfd;
      color: #333;
    }

    header {
      background-color: #ff6f61;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: 36px;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    h2 {
      text-align: center;
      color: #ff6f61;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    label {
      font-weight: 600;
    }

    input, select, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }

    button {
      padding: 12px;
      background-color: #ff6f61;
      color: #fff;
      border: none;
      border-radius: 30px;
      font-size: 16px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #e65c50;
    }
  </style>
</head>
<body>

  <header>
    <h1>Women's Clothing Sale</h1>
  </header>

  <div class="container">
    <h2>Order Form</h2>
    <form action="#" method="POST">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required>

      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required>

      <label for="product">Select Product:</label>
      <select id="product" name="product" required>
        <option value="">-- Select a Product --</option>
        <option value="dress">Floral Summer Dress</option>
        <option value="top">Casual Cotton Top</option>
        <option value="jeans">High-Waist Jeans</option>
        <option value="scarf">Silk Scarf</option>
      </select>

      <label for="size">Size:</label>
      <select id="size" name="size" required>
        <option value="">-- Select Size --</option>
        <option value="S">Small (S)</option>
        <option value="M">Medium (M)</option>
        <option value="L">Large (L)</option>
        <option value="XL">Extra Large (XL)</option>
      </select>

      <label for="address">Shipping Address:</label>
      <textarea id="address" name="address" rows="4" placeholder="Enter your full address" required></textarea>

      <button type="submit">Place Order</button>
    </form>
  </div>

</body>
</html>
