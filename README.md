<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин в Телеграм</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        header {
            background-color: #0078ff;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .product {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin: 10px 0;
            padding: 10px;
            display: flex;
            justify-content: space-between;
        }
        .product img {
            max-width: 100px;
            border-radius: 5px;
        }
        .product-info {
            flex-grow: 1;
            margin-left: 10px;
        }
        .button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать в наш магазин!</h1>
    </header>

    <div class="product">
        <img src="https://via.placeholder.com/100" alt="Продукт 1">
        <div class="product-info">
            <h2>Продукт 1</h2>
            <p>Описание продукта 1</p>
            <p>Цена: 100₽</p>
            <button class="button">Купить</button>
        </div>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/100" alt="Продукт 2">
        <div class="product-info">
            <h2>Продукт 2</h2>
            <p>Описание продукта 2</p>
            <p>Цена: 200₽</p>
            <button class="button">Купить</button>
        </div>
    </div>

</body>
</html>
