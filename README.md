<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinatería Digital</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #4a90e2;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        section {
            padding: 20px;
        }
        .product-section {
            background-color: #e3f2fd;
        }
        .offers {
            background-color: #ffe0b2;
        }
        h2 {
            text-align: center;
            color: #333;
        }
        .product, .offer-card {
            border: 1px solid #ccc;
            margin: 10px;
            padding: 15px;
            border-radius: 8px;
            background: white;
        }
        .product img, .offer-card img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .price {
            font-size: 18px;
            font-weight: bold;
            color: #007b5e;
        }
        .button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #4caf50;
            color: white;
            border: none;
            border-radius: 5px;
            text-align: center;
            cursor: pointer;
            text-decoration: none;
        }
        .button:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .footer-contact {
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <h1>Vinatería Digital</h1>
    <p>Tu mejor opción para pedidos de última hora</p>
</header>

<nav>
    <a href="#vinos">Vinos</a>
    <a href="#ofertas">Ofertas</a>
    <a href="#licores">Licores</a>
    <a href="#contacto">Contacto</a>
</nav>

<section id="vinos" class="product-section">
    <h2>Explora Nuestra Selección de Vinos</h2>
    <div class="product">
        <img src="vino-tinto.jpg" alt="Vino Tinto">
        <h2>Vino Tinto Reserva</h2>
        <p>Un exquisito vino tinto con notas de frutas rojas.</p>
        <p class="price">$250.00</p>
        <button class="button">Comprar</button>
    </div>
    <div class="product">
        <img src="vino-blanco.jpg" alt="Vino Blanco">
        <h2>Vino Blanco Chardonnay</h2>
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

<section id="licores" class="product-section">
    <h2>Nuestros Licores</h2>

    <h3>Brandy</h3>
    <div class="product">
        <img src="brandy-torres10.jpg" alt="Torres 10">
        <h2>Torres 10</h2>
        <p>Un brandy añejo con carácter y sabor intenso.</p>
        <p class="price">$470.00</p>
        <button class="button">Comprar</button>
    </div>

    <h3>Ron</h3>
    <div class="product">
        <img src="bacardi-blanco.jpg" alt="Bacardi Blanco">
        <h2>Bacardi Blanco</h2>
        <p>Ron clásico ideal para cocteles.</p>
        <p class="price">$390.00</p>
        <button class="button">Comprar</button>
    </div>
    <div class="product">
        <img src="matusalem-platino.jpg" alt="Matusalem Platino">
        <h2>Matusalem Platino</h2>
        <p>Ron premium con acabado refinado.</p>
        <p class="price">$1,550.00</p>
        <button class="button">Comprar</button>
    </div>

    <h3>Tequila</h3>
    <div class="product">
        <img src="centenario-reposado.jpg" alt="Centenario Reposado">
        <h2>Centenario Reposado (750 ml)</h2>
        <p>Tequila suave y balanceado.</p>
        <p class="price">$360.00</p>
        <button class="button">Comprar</button>
    </div>
    <!-- Resto de productos de tequila -->
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p>Teléfono y WhatsApp: <a href="tel:+523325905963">3325905963</a></p>
    <p>¡Haz tu pedido ahora y recibe en la comodidad de tu hogar!</p>
</section>

<footer>
    <p>&copy; 2024 Vinatería Digital - Todos los derechos reservados.</p>
    <p class="footer-contact">Contacto: 3325905963 | vinateria@digital.com</p>
</footer>

</body>
</html>
