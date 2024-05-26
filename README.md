<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Virtual - Ivan Bambo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #fff;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 15px;
            text-align: center;
            width: 30%;
        }
        .product img {
            width: 300px;
            height: 300px;
            border-bottom: 1px solid #ddd;
            margin-bottom: 15px;
            object-fit: cover; /* This property helps to cover the image area properly */
        }
        .product h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .product p {
            color: #666;
            margin: 0 0 10px;
        }
        .product .price {
            color: #e74c3c;
            font-size: 1.2em;
            margin-bottom: 15px;
        }
        .product button {
            background-color: #5cb85c;
            border: none;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            display: inline-block;
            font-size: 1em;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #4cae4c;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Loja Virtual - Ivan Bambo</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Produtos</a>
        <a href="#">Sobre</a>
        <a href="#">Contato</a>
    </nav>
    <div class="content">
        <h2>Produtos em Destaque</h2>
        <div class="products">
            <div class="product">
                <img src="produto1.jpg" alt="ThinkPad Laptop">
                <h2>ThinkPad Laptop</h2>
                <p>Descrição breve do ThinkPad Laptop.</p>
                <p class="price">MT 32.500</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="produto2.jpg" alt="Lenovo Laptop">
                <h2>Lenovo Laptop</h2>
                <p>Descrição breve do Lenovo Laptop.</p>
                <p class="price">Mt 27.500</p>
                <button>Comprar</button>
            </div>
            <div class="product">
                <img src="produto3.jpg" alt="HP Laptop">
                <h2>HP Laptop</h2>
                <p>Descrição breve do HP Laptop.</p>
                <p class="price">Mt 26.500</p>
                <button>Comprar</button>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Ivan Bambo. Todos os direitos reservados.</p>
    </footer>
</body>
</html>



# IvanService-
Nosso notebook de última geração oferece desempenho excepcional e design elegante, perfeito para estudos, trabalho e entretenimento. Adquira já o seu!
