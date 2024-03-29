<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>E-commerce Product Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>E-commerce Product Page</h1>
  </header>
  <main>
    <section class="product">
      <img src="product-image.jpg" alt="Product Image">
      <h2>Product Name</h2>
      <p>Description of the product goes here.</p>
      <p>Price: $XX.XX</p>
      <a href="#" class="btn">Add to Cart</a>
    </section>
  </main>
  <footer>
    <p>&copy; 2024 E-commerce Store. All rights reserved.</p>
  </footer>
</body>
</html>
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

main {
  max-width: 800px;
  margin: 20px auto;
  padding: 0 20px;
}

.product {
  background-color: #fff;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.product img {
  width: 100%;
  border-radius: 8px;
}

.product h2 {
  margin-top: 10px;
}

.btn {
  display: inline-block;
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.btn:hover {
  background-color: #555;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #333;
  color: #fff;
}
