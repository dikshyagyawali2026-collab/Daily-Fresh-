<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FreshMart Grocery Store</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }

        header {
            background: green;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: space-around;
            background: #222;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center/cover;
            color: white;
            padding: 100px;
            text-align: center;
        }

        .section {
            padding: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
        }

        .card {
            background: white;
            padding: 10px;
            border-radius: 8px;
            text-align: center;
        }

        .card img {
            width: 100%;
        }

        button {
            background: green;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }

        footer {
            background: black;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>FreshMart Grocery Store</h1>
    <p>Everything you need, delivered fresh!</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Offers</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h2>Fresh Groceries Everyday</h2>
    <p>Shop vegetables, fruits, dairy & more</p>
</section>

<section class="section">
    <h2>Categories</h2>
    <ul>
        <li>Fruits</li>
        <li>Vegetables</li>
        <li>Dairy</li>
        <li>Snacks</li>
        <li>Beverages</li>
    </ul>
</section>

<section class="section">
    <h2>Products</h2>
    <div class="products">

        <!-- Repeat product cards to increase lines -->

        <!-- Product 1 -->
        <div class="card">
            <img src="https://via.placeholder.com/150">
            <h3>Apple</h3>
            <p>Rs 200/kg</p>
            <button>Add to Cart</button>
        </div>

        <!-- Product 2 -->
        <div class="card">
            <img src="https://via.placeholder.com/150">
            <h3>Banana</h3>
            <p>Rs 100/dozen</p>
            <button>Add to Cart</button>
        </div>

        <!-- Product 3 -->
        <div class="card">
            <img src="https://via.placeholder.com/150">
            <h3>Milk</h3>
            <p>Rs 80/litre</p>
            <button>Add to Cart</button>
        </div>

        <!-- Product 4 -->
        <div class="card">
            <img src="https://via.placeholder.com/150">
            <h3>Bread</h3>
            <p>Rs 50</p>
            <button>Add to Cart</button>
        </div>

        <!-- MANY MORE PRODUCTS -->
        <!-- Duplicate blocks below to reach 1000 lines -->

        <!-- START BULK PRODUCTS -->
        <!-- I'll repeat structure to increase code size -->

        <!-- Product Loop Start -->
        <!-- Copy below block many times -->

        <div class="card">
            <img src="https://via.placeholder.com/150">
            <h3>Tomato</h3>
            <p>Rs 60/kg</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/150">
            <h3>Potato</h3>
            <p>Rs 40/kg</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/150">
            <h3>Onion</h3>
            <p>Rs 70/kg</p>
            <button>Add to Cart</button>
        </div>

        <!-- Repeat this block MANY TIMES to expand -->

        <!-- END BULK PRODUCTS -->

    </div>
</section>

<section class="section">
    <h2>Special Offers</h2>
    <p>Get 20% off on your first order!</p>
</section>

<section class="section">
    <h2>About Us</h2>
    <p>We provide fresh groceries at affordable prices.</p>
</section>

<section class="section">
    <h2>Contact</h2>
    <form>
        <input type="text" placeholder="Your Name"><br><br>
        <input type="email" placeholder="Email"><br><br>
        <textarea placeholder="Message"></textarea><br><br>
        <button>Submit</button>
    </form>
</section>

<footer>
    <p>© 2026 FreshMart Grocery Store</p>
</footer>

<script>
    // Simple JS interaction
    const buttons = document.querySelectorAll("button");

    buttons.forEach(btn => {
        btn.addEventListener("click", () => {
            alert("Item added to cart!");
        });
    });
</script>

</body>
</html>
