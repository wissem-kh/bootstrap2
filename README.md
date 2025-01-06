# bootstrap2

/* styles.css */

/* Global Styles */
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f8f9fa;
}

.navbar {
  background-color: #343a40;
}

.navbar .nav-link {
  color: #fff !important;
  font-size: 1rem;
}

.navbar .nav-link:hover {
  color: #ffc107 !important;
}

.hero {
  text-align: center;
  background-image: url('placeholder-hero.jpg'); /* Replace with actual image */
  background-size: cover;
  background-position: center;
  padding: 80px 20px;
  color: white;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.hero button {
  padding: 10px 20px;
  background-color: #ffc107;
  border: none;
  color: #343a40;
  font-size: 1rem;
  cursor: pointer;
  border-radius: 5px;
}

.hero button:hover {
  background-color: #e0a800;
}

.product-section {
  padding: 40px 20px;
  background-color: #fff;
}

.product-card {
  background: #f8f9fa;
  border: 1px solid #ddd;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.1);
}

.product-card img {
  width: 100%;
  height: auto;
}

.product-card h3 {
  font-size: 1.2rem;
  margin: 10px 0;
  padding: 0 10px;
}

.product-card p {
  font-size: 0.9rem;
  color: #666;
  padding: 0 10px;
}

.product-card button {
  width: 100%;
  background-color: #343a40;
  color: white;
  padding: 10px;
  border: none;
  border-radius: 0 0 10px 10px;
  font-size: 1rem;
  cursor: pointer;
}

.product-card button:hover {
  background-color: #495057;
}

.footer {
  padding: 20px;
  background-color: #343a40;
  color: #fff;
  text-align: center;
}

.footer a {
  color: #ffc107;
  text-decoration: none;
}

.footer a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .hero h1 {
    font-size: 2rem;
  }

  .hero p {
    font-size: 1rem;
  }

  .product-card {
    margin-bottom: 20px;
  }
}








<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Responsive Store Landing Page">
  <title>Online Store</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <a class="navbar-brand" href="#">StoreName</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Products</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Welcome to Our Online Store</h1>
      <p>Discover the best products curated just for you.</p>
      <button>Shop Now</button>
    </div>
  </section>

  <!-- Product Section -->
  <section class="product-section">
    <div class="container">
      <h2 class="text-center mb-4">Our Products</h2>
      <div class="row g-4">
        <!-- Product Card 1 -->
        <div class="col-md-3 col-sm-6">
          <div class="product-card">
            <img src="placeholder-product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>Brief description of the product.</p>
            <button>Shop Now</button>
          </div>
        </div>
        <!-- Product Card 2 -->
        <div class="col-md-3 col-sm-6">
          <div class="product-card">
            <img src="placeholder-product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>Brief description of the product.</p>
            <button>Shop Now</button>
          </div>
        </div>
        <!-- Product Card 3 -->
        <div class="col-md-3 col-sm-6">
          <div class="product-card">
            <img src="placeholder-product3.jpg" alt="Product 3">
            <h3>Product 3</h3>
            <p>Brief description of the product.</p>
            <button>Shop Now</button>
          </div>
        </div>
        <!-- Product Card 4 -->
        <div class="col-md-3 col-sm-6">
          <div class="product-card">
            <img src="placeholder-product4.jpg" alt="Product 4">
            <h3>Product 4</h3>
            <p>Brief description of the product.</p>
            <button>Shop Now</button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2025 Online Store. All rights reserved.</p>
    <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

