<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinos y Licores - Delivery Express</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background: #1a1a1a;
            color: #ffd700;
            text-align: center;
            padding: 20px;
            border-bottom: 2px solid #ffd700;
        }
        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
        }
        header nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 15px;
        }
        header nav ul li a {
            text-decoration: none;
            color: #ffd700;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        header nav ul li a:hover {
            color: #fff;
        }
        section {
            padding: 20px;
        }
        .product-section h2, .offers h2, .contact-section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 24px;
            color: #333;
            text-align: center;
            margin-bottom: 15px;
        }
        .product-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            max-width: 200px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .product h3 {
            font-size: 18px;
            color: #333;
            margin-bottom: 10px;
        }
        .product p {
            font-size: 14px;
            margin: 5px 0;
        }
        .price {
            font-size: 16px;
            color: #ff5722;
            font-weight: bold;
        }
        .button {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 12px;
            background: #ffd700;
            color: #000;
            border: none;
            border-radius: 5px;
            font-size: 14px;
            font-weight: bold;
            text-decoration: none;
            transition: background 0.3s ease;
        }
        .button:hover {
            background: #ffcc33;
        }
        footer {
            background: #1a1a1a;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <h1>Delivery Express</h1>
    <nav>
        <ul>
            <li><a href="#vinos">Vinos</a></li>
            <li><a href="#licores">Licores</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
</header>

<section id="licores" class="product-section">
    <h2>Nuestros Licores</h2>
    <div class="product-container">
        <div class="product">
            <img src="brandy-torres10.jpg" alt="Torres 10">
            <h3>Torres 10</h3>
            <p>Brandy añejo</p>
            <p class="price">$470.00</p>
        </div>
        <div class="product">
            <img src="bacardi-blanco.jpg" alt="Bacardi Blanco">
            <h3>Bacardi Blanco</h3>
            <p>Ron clásico</p>
            <p class="price">$390.00</p>
        </div>
        <div class="product">
            <img src="matusalem-platino.jpg" alt="Matusalem Platino">
            <h3>Matusalem Platino</h3>
            <p>Ron premium</p>
            <p class="price">$1,550.00</p>
        </div>
        <!-- Agregar más productos siguiendo el mismo patrón -->
    </div>
</section>

<section id="contacto" class="contact-section">
    <h2>Contacto</h2>
    <p>Para pedidos o más información, contáctanos al:</p>
    <p>Teléfono y WhatsApp: <a href="https://wa.me/523325905963" class="button">3325905963</a></p>
</section>

<footer>
    <p>&copy; 2024 Delivery Express. Todos los derechos reservados.</p>
</footer>

</body>
</html>
