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
            background-color: #f5f5dc;
            color: #333;
        }

        header {
            background-color: #fff8dc;
            color: #6b4226;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid #6b4226;
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 24px;
            margin: 0;
        }

        nav {
            display: none;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            margin: 10px 0;
        }

        nav ul li a {
            text-decoration: none;
            color: #6b4226;
            font-weight: bold;
            display: block;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav ul li a:hover {
            background-color: #6b4226;
            color: #fff;
        }

        .menu-btn {
            font-size: 24px;
            cursor: pointer;
            background: none;
            border: none;
        }

        .menu-btn:focus {
            outline: none;
        }

        .menu-open nav {
            display: block;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            height: 100%;
            z-index: 1000;
            padding-top: 50px;
            box-sizing: border-box;
            text-align: center;
        }

        main {
            padding: 20px;
        }

        .product-slider {
            display: flex;
            overflow: hidden;
            width: 100%;
            position: relative;
        }

        .product-slide {
            flex: 0 0 100%;
            box-sizing: border-box;
            padding: 20px;
            text-align: center;
        }

        .product-slide img {
            width: 100%;
            border-radius: 10px;
        }

        .prev, .next {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background: #6b4226;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 50%;
        }

        .prev { left: 10px; }
        .next { right: 10px; }

        .button {
            background-color: #6b4226;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            text-transform: uppercase;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #333;
        }

        footer {
            background-color: #fff8dc;
            text-align: center;
            padding: 10px 0;
            border-top: 2px solid #6b4226;
            color: #6b4226;
        }

        footer a {
            color: #6b4226;
            text-decoration: none;
            font-weight: bold;
        }

        @media (min-width: 768px) {
            header nav {
                display: flex;
                justify-content: flex-end;
            }

            nav ul {
                display: flex;
                gap: 15px;
            }

            nav ul li {
                margin: 0;
            }

            nav ul li a {
                padding: 0;
                margin: 0;
            }

            .menu-btn {
                display: none;
            }

            .menu-open nav {
                display: none;
            }

            .product-slider {
                grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Delivery Express</h1>
        <button class="menu-btn" onclick="document.body.classList.toggle('menu-open')">☰</button>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#vinos">Vinos</a></li>
                <li><a href="#ofertas">Ofertas</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="vinos" class="product-slider">
            <div class="product-slide">
                <img src="https://oasisvinosylicores.com/wp-content/uploads/2024/06/Img-W-15.png" alt="Vino Tinto">
                <h2>Vino Tinto Syrah Viña Maipo</h2>
                <p>Delicioso sabor suave, de color rubí y tonos violeta.</p>
                <p class="price">$150.00</p>
                <a href="https://wa.me/523325905963?text=Hola,%20quiero%20comprar%20el%20Vino%20Tinto." class="button">Comprar</a>
            </div>
            <div class="product-slide">
                <img src="https://i5-mx.walmartimages.com/mg/gm/1p/images/product-images/img_large/00329711001413l.jpg" alt="Champagne Brut">
                <h2>Champagne Brut</h2>
                <p>¡20% de descuento por tiempo limitado!</p>
                <p class="price">Antes: $650.00 Ahora: $520.00</p>
                <a href="https://wa.me/523325905963?text=Hola,%20quiero%20comprar%20Champagne%20Brut." class="button">Comprar</a>
            </div>
            <div class="product-slide">
                <img src="https://vinotecamx.vtexassets.com/arquivos/ids/1346873/B4017-Vinoteca-Brandy-Torres-10-Anos-700Ml-003.jpg?v=638646768118670000" alt="Brandy Torres 10">
                <h2>Brandy Torres 10</h2>
                <p>Un brandy añejo con carácter y sabor intenso.</p>
                <p class="price">$359.00</p>
                <a href="https://wa.me/523325905963?text=Hola,%20quiero%20comprar%20Brandy%20Torres%2010." class="button">Comprar</a>
            </div>
        </section>

        <button class="prev">❮</button>
        <button class="next">❯</button>
    </main>

    <footer>
        <p>© 2024 Delivery Express. Todos los derechos reservados.</p>
    </footer>

    <script>
        const slides = document.querySelectorAll('.product-slide');
        let currentIndex = 0;

        document.querySelector('.next').addEventListener('click', () => {
            slides[currentIndex].style.display = 'none';
            currentIndex = (currentIndex + 1) % slides.length;
            slides[currentIndex].style.display = 'block';
        });

        document.querySelector('.prev').addEventListener('click', () => {
            slides[currentIndex].style.display = 'none';
            currentIndex = (currentIndex - 1 + slides.length) % slides.length;
            slides[currentIndex].style.display = 'block';
        });

        slides.forEach((slide, index) => slide.style.display = index === 0 ? 'block' : 'none');
    </script>
</body>
</html>
