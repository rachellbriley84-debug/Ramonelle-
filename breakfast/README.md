<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breakfast - Ramonelle</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #fff7f0;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            margin-top: 25px;
            color: #ff7b4f;
        }

        .container {
            width: 90%;
            margin: auto;
            margin-top: 25px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: 0.3s ease;
        }

        .card:hover {
            transform: scale(1.03);
            background: #ffe7db;
        }

        .image-box {
            width: 100%;
            height: 150px;
            background: #ffe0d3;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #ff5722;
            font-weight: bold;
        }

        h3 {
            text-align: center;
            margin-top: 12px;
            color: #444;
        }

        p {
            text-align: center;
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>

    <h1>Kenyan Breakfast</h1>

    <div class="container">

        <!-- Mandazi -->
        <div class="card">
            <div class="image-box">Image Here</div>
            <h3>Mandazi</h3>
            <p>Soft, sweet snacks perfect with chai.</p>
        </div>

        <!-- Chai Tea -->
        <div class="card">
            <div class="image-box">Image Here</div>
            <h3>Chai (Tea)</h3>
            <p>Classic Kenyan breakfast tea brewed with milk & spices.</p>
        </div>

        <!-- Mahamri -->
        <div class="card">
            <div class="image-box">Image Here</div>
            <h3>Mahamri</h3>
            <p>Swahili breakfast made with coconut flavor.</p>
        </div>

        <!-- Chapati -->
        <div class="card">
            <div class="image-box">Image Here</div>
            <h3>Chapati</h3>
            <p>Golden, soft chapatis served with tea or stew.</p>
        </div>

        <!-- Eggs & Sausages -->
        <div class="card">
            <div class="image-box">Image Here</div>
            <h3>Eggs & Sausages</h3>
            <p>Common Kenyan breakfast plate with protein.</p>
        </div>

        <!-- Uji -->
        <div class="card">
            <div class="image-box">Image Here</div>
            <h3>Uji (Porridge)</h3>
            <p>Healthy millet/maize porridge served warm.</p>
        </div>

    </div>

</body>
</html>
