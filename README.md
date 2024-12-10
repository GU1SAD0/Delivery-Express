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
        <div class="product">
            <img src="centenario-plata.jpg" alt="Centenario Plata">
            <h2>Centenario Plata (750 ml)</h2>
            <p>Tequila joven y fresco.</p>
            <p class="price">$300.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="tradicional.jpg" alt="Tradicional">
            <h2>Tradicional (750 ml)</h2>
            <p>Un clásico tequila reposado.</p>
            <p class="price">$270.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="don-julio-70.jpg" alt="Don Julio 70">
            <h2>Don Julio 70</h2>
            <p>Tequila premium cristalino.</p>
            <p class="price">$1,900.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="dobel.jpg" alt="Dobel">
            <h2>Dobel</h2>
            <p>Tequila ultra premium.</p>
            <p class="price">$1,200.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="herradura.jpg" alt="Herradura">
            <h2>Herradura</h2>
            <p>Un tequila artesanal con tradición.</p>
            <p class="price">$730.00</p>
            <button class="button">Comprar</button>
        </div>
    
        <h3>Whisky</h3>
        <div class="product">
            <img src="johnnie-red.jpg" alt="Etiqueta Roja">
            <h2>Etiqueta Roja (Johnnie Walker)</h2>
            <p>Un whisky con carácter.</p>
            <p class="price">$530.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="buchanans.jpg" alt="Buchanan’s">
            <h2>Buchanan’s</h2>
            <p>Whisky premium con sabor suave.</p>
            <p class="price">$650.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="black-white.jpg" alt="Black & White">
            <h2>Black & White</h2>
            <p>Un whisky ideal para compartir.</p>
            <p class="price">$450.00</p>
            <button class="button">Comprar</button>
        </div>
    
        <h3>Vodka</h3>
        <div class="product">
            <img src="smirnoff.jpg" alt="Smirnoff">
            <h2>Smirnoff</h2>
            <p>Vodka versátil para cocteles.</p>
            <p class="price">$260.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="absolut.jpg" alt="Absolut">
            <h2>Absolut</h2>
            <p>Vodka premium sueco.</p>
            <p class="price">$350.00</p>
            <button class="button">Comprar</button>
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
