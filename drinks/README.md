<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Categories - Ramonelle</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #fff7f0;
        }

        h1 {
            text-align: center;
            margin-top: 30px;
            color: #ff7b4f;
        }

        .container {
            width: 90%;
            margin: auto;
            padding-top: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }

        .category-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            transition: 0.3s ease;
        }

        .category-card:hover {
            transform: scale(1.05);
            background: #ffe7db;
        }

        a {
            text-decoration: none;
            color: #ff5722;
        }
    </style>
</head>
<body>

    <h1>Recipe Categories</h1>

    <div class="container">

        <a href="breakfast/README.md">
            <div class="category-card">🍳 Breakfast</div>
        </a>

        <a href="lunch/README.md">
            <div class="category-card">🥗 Lunch</div>
        </a>

        <a href="dinner/README.md">
            <div class="category-card">🍽 Dinner</div>
        </a>

        <a href="snacks/README.md">
            <div class="category-card">🍪 Snacks</div>
        </a>

        <a href="desserts/README.md">
            <div class="category-card">🍰 Desserts</div>
        </a>

        <a href="drinks/README.md">
            <div class="category-card">🍹 Drinks</div>
        </a>

    </div>

</body>
</html>
