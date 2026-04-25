# Index
My bakery 
<!DOCTYPE html>
<html>
<head>
    <title>Sweet Bakery</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body { font-family: Arial; margin: 0; background: #fff8f0; }

        header {
            background: #ff6f61;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background: #ff9a8b;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }

        section { padding: 20px; }

        h2 { text-align: center; }

        .items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .card {
            background: white;
            width: 250px;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 0 10px #ccc;
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        button {
            background: #ff6f61;
            color: white;
            border: none;
            padding: 10px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
        }

        footer {
            background: #ff6f61;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>

<body>

<header>
    <h1>Sweet Bakery 🍰</h1>
    <p>Fresh | Tasty | Homemade</p>
</header>

<nav>
    <a href="#menu">Menu</a>
</nav>

<section id="menu">
    <h2>Our Delicious Menu</h2>

    <div class="items">

        <!-- Cakes -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?chocolate-cake">
            <h3>Chocolate Cake 🎂</h3>
            <p>₹500</p>
        </div>

        <div class="card">
            <img src="https://source.unsplash.com/250x200/?vanilla-cake">
            <h3>Vanilla Cake 🎂</h3>
            <p>₹450</p>
        </div>

        <div class="card">
            <img src="https://source.unsplash.com/250x200/?blueberry-cake">
            <h3>Blueberry Cake 🎂</h3>
            <p>₹550</p>
        </div>

        <div class="card">
            <img src="https://source.unsplash.com/250x200/?lemon-cake">
            <h3>Lemon Cake 🎂</h3>
            <p>₹480</p>
        </div>

        <!-- Cheesecake -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?cheesecake">
            <h3>New York Cheesecake 🧀</h3>
            <p>₹600</p>
        </div>

        <!-- Cookies -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?cookies">
            <h3>Cookies 🍪</h3>
            <p>₹120</p>
        </div>

        <!-- Burger -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?burger">
            <h3>Burger 🍔</h3>
            <p>₹150</p>
        </div>

        <!-- Sandwich -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?sandwich">
            <h3>Sandwich 🥪</h3>
            <p>₹120</p>
        </div>

        <!-- Croissant -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?croissant">
            <h3>Croissant 🥐</h3>
            <p>₹90</p>
        </div>

        <!-- Puffs -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?puff-pastry">
            <h3>Puffs 🥐</h3>
            <p>₹80</p>
        </div>

        <!-- Chocolate -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?chocolate">
            <h3>Homemade Chocolates 🍫</h3>
            <p>₹200</p>
        </div>

        <!-- Tiramisu -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?tiramisu">
            <h3>Tiramisu ☕</h3>
            <p>₹300</p>
        </div>

        <!-- Baklava -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?baklava">
            <h3>Baklava 🍯</h3>
            <p>₹350</p>
        </div>

        <!-- Kunafa -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?kunafa">
            <h3>Kunafa Rolls 🧀</h3>
            <p>₹400</p>
        </div>

        <!-- Bread -->
        <div class="card">
            <img src="https://source.unsplash.com/250x200/?bread">
            <h3>Fresh Bread 🍞</h3>
            <p>₹60</p>
        </div>

    </div>
</section>

<footer>
    <p>📍 Panvel | 🕒 9AM - 9PM</p>
    <p>© 2026 Sweet Bakery</p>
</footer>

</body>
</html>
