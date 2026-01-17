<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soil & Soul | Handcrafted Clay</title>
    <style>
        /* CSS: Setting the Earthy Theme */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #fdf5e6; /* Cream/Sand background */
            color: #3e2723; /* Dark earthy brown text */
            margin: 0;
            padding: 0;
        }

        /* Navigation Bar */
        header {
            background-color: #a0522d; /* Sienna/Clay color */
            color: white;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        /* Category Filter Section */
        .filter-section {
            text-align: center;
            padding: 20px;
        }

        .filter-btn {
            background: white;
            border: 1px solid #a0522d;
            padding: 8px 15px;
            margin: 5px;
            cursor: pointer;
            border-radius: 20px;
            transition: 0.3s;
        }

        .filter-btn:hover {
            background: #a0522d;
            color: white;
        }

        /* The Grid Layout with White Space */
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px; /* The 'White Space' you requested */
            padding: 40px 5%;
        }

        /* Individual Product Card */
        .product-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            text-align: center;
            padding-bottom: 20px;
            transition: transform 0.2s;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-image {
            width: 100%;
            height: 200px;
            background-color: #e0e0e0; /* Placeholder for images */
            display: flex;
            align-items: center;
            justify-content: center;
            color: #888;
        }

        .product-name {
            margin: 15px 0 5px;
            font-size: 1.2rem;
        }

        .price {
            color: #a0522d;
            font-weight: bold;
            font-size: 1.1rem;
        }

        .buy-btn {
            background-color: #2e7d32; /* Green 'Buy' button */
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Soil & Soul</h1>
        <nav>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>

    <div class="filter-section">
        <h3>Filter by Category</h3>
        <button class="filter-btn">Kitchenware</button>
        <button class="filter-btn">Home Decor</button>
        <button class="filter-btn">Gifts</button>
    </div>

    <main class="product-grid">
        
        <div class="product-card">
            <div class="product-image">IMAGE OF POT</div>
            <h2 class="product-name">Artisan Soil Pot</h2>
            <p class="price">₹450</p>
            <button class="buy-btn">Add to Cart</button>
        </div>

        <div class="product-card">
            <div class="product-image">IMAGE OF PLATE</div>
            <h2 class="product-name">Traditional Soil Plate</h2>
            <p class="price">₹300</p>
            <button class="buy-btn">Add to Cart</button>
        </div>

        <div class="product-card">
            <div class="product-image">IMAGE OF PIGGY BANK</div>
            <h2 class="product-name">Clay Piggy Bank</h2>
            <p class="price">₹150</p>
            <button class="buy-btn">Add to Cart</button>
        </div>

    </main>

</body>
</html>
