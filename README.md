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
            background: #f8f9fa;
            color: #333;
        }
        header {
            background: #1a1a1a;
            color: #ffd700;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 24px;
            margin: 0;
        }
        header p {
            font-size: 14px;
            margin: 5px 0 15px;
        }
        header nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        header nav ul li {
            margin: 0 10px;
        }
        header nav ul li a {
            text-decoration: none;
            color: #ffd700;
            font-weight: bold;
            font-size: 14px;
        }
        header nav ul li a:hover {
            color: #fff;
        }
        .product-section, .offers, .contact-section {
            padding: 20px;
            text-align: center;
        }
        .product-section h2, .offers h2, .contact-section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 20px;
            margin-bottom: 15px;
            color: #1a1a1a;
        }
        .product, .offer-card {
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin: 15px auto;
            padding: 15px;
            width: 90%;
            max-width: 300px;
        }
        .product img, .offer-card img {
            max-width: 100%;
            border-radius: 8px;
        }
        .price {
            font-size: 18px;
            font-weight: bold;
            margin: 10px 0;
        }
        .button, .contact-button {
            background: #ffd700;
            color: #000;
            border: none;
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            display: inline-block;
            text-decoration: none;
            margin-top: 10px;
        }
        .button:hover, .contact-button:hover {
            background: #e6c200;
        }
        footer {
            background: #1a1a1a;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            font-size: 14px;
        }
        /* Media Queries */
        @media (min-width: 768px) {
            header h1 {
                font-size: 36px;
            }
            .product, .offer-card {
                width: 45%;
                margin: 15px;
                display: inline-block;
            }
        }
        @media (min-width: 1024px) {
            .product, .offer-card {
                width: 30%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Delivery Express</h1>
        <p>Vinos y licores a tu puerta, cuando más los necesitas.</p>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#vinos">Vinos</a></li>
                <li><a href="#ofertas">Ofertas</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="vinos" class="product-section">
        <h2>Explora Nuestra Selección de Vinos</h2>
        <div class="product">
            <img src="vino-tinto.jpg" alt="Vino Tinto">
            <h3>Vino Tinto Reserva</h3>
            <p>Un exquisito vino tinto con notas de frutas rojas.</p>
            <p class="price">$250.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="vino-blanco.jpg" alt="Vino Blanco">
            <h3>Vino Blanco Chardonnay</h3>
            <p>Un fresco vino blanco ideal para acompañar mariscos.</p>
            <p class="price">$180.00</p>
            <button class="button">Comprar</button>
        </div>
    </section>

    <section id="ofertas" class="offers">
        <h2>Ofertas Especiales</h2>
        <div class="offer-card">
            <img src="champagne.jpg" alt="Champagne">
            <h3>Champagne Brut</h3>
            <p>¡20% de descuento por tiempo limitado!</p>
            <p class="price">Antes: $650.00 Ahora: $520.00</p>
        </div>
    </section>

    <section id="contacto" class="contact-section">
        <h2>Contacto</h2>
        <p>Para pedidos o más información, contáctanos al:</p>
        <p><strong>Teléfono y WhatsApp: 3325905963</strong></p>
        <a href="https://wa.me/523325905963" class="contact-button" target="_blank">Escríbenos por WhatsApp</a>
    </section>

    <footer>
        <p>&copy; 2024 Delivery Express. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
