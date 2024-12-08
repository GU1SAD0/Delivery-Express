<!DOCTYPE html>
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
        }
        header {
            background: #1a1a1a;
            color: #ffd700;
            padding: 20px 0;
            text-align: center;
            border-bottom: 2px solid #ffd700;
        }
        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 36px;
        }
        header nav ul {
            list-style: none;
            padding: 0;
        }
        header nav ul li {
            display: inline;
            margin: 0 15px;
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
        .slogan {
            margin: 10px 0;
            font-style: italic;
        }
        .product-section {
            background: #2a2a2a;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }
        .product-section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            color: #ffd700;
            margin-bottom: 20px;
        }
        .offers {
            background: #f5f5f5;
            color: #333;
            padding: 40px 20px;
            text-align: center;
        }
        .offers h2 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            color: #333;
            margin-bottom: 20px;
        }
        .contact-section {
            background: #333;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }
        .contact-section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            color: #ffd700;
            margin-bottom: 20px;
        }
        .product, .offer-card {
            background: #fff;
            margin: 15px auto;
            padding: 20px;
            border-radius: 10px;
            width: 250px;
            display: inline-block;
            color: #333;
        }
        .product img, .offer-card img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        .price {
            font-size: 20px;
            color: #333;
            margin: 10px 0;
        }
        .button, .contact-button {
            background: #ffd700;
            color: #000;
            border: none;
            padding: 10px 20px;
            text-transform: uppercase;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s ease;
            text-decoration: none;
        }
        .button:hover, .contact-button:hover {
            background: #fff;
        }
        footer {
            background: #1a1a1a;
            text-align: center;
            padding: 10px 0;
            border-top: 2px solid #ffd700;
            color: #fff;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Delivery Express</h1>
        <p class="slogan">Vinos y licores a tu puerta, cuando más los necesitas.</p>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#vinos">Vinos</a></li>
                <li><a href="#ofertas">Ofertas</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="product-section">
        <h2>Bienvenido a Delivery Express</h2>
        <p>¡Servicio rápido para pedidos de última hora! Entregamos a domicilio en Zapopan y Guadalajara.</p>
        <div class="product">
            <img src="vino-tinto.jpg" alt="Vino Tinto">
            <h2>Vino Tinto Reserva</h2>
            <p>Un exquisito vino tinto con notas de frutas rojas.</p>
            <p class="price">$250.00</p>
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
        <p class="highlight">Teléfono y WhatsApp: 3325905963</p>
        <a href="https://wa.me/523325905963" class="contact-button" target="_blank">Escríbenos por WhatsApp</a>
    </section>

    <footer>
        <p>&copy; 2024 Delivery Express. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
