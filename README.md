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
            <img src="https://vinotecamx.vtexassets.com/arquivos/ids/1346873/B4017-Vinoteca-Brandy-Torres-10-Anos-700Ml-003.jpg?v=638646768118670000" alt="Torres 10">
            <h2>Torres 10</h2>
            <p>Un brandy añejo con carácter y sabor intenso.</p>
            <p class="price">$470.00</p>
            <button class="button">Comprar</button>
        </div>
    
        <h3>Ron</h3>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Bacardi Blanco">
            <h2>Bacardi Blanco</h2>
            <p>Ron clásico ideal para cocteles.</p>
            <p class="price">$390.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Matusalem Platino">
            <h2>Matusalem Platino</h2>
            <p>Ron premium con acabado refinado.</p>
            <p class="price">$1,550.00</p>
            <button class="button">Comprar</button>
        </div>
    
        <h3>Tequila</h3>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Centenario Reposado">
            <h2>Centenario Reposado (750 ml)</h2>
            <p>Tequila suave y balanceado.</p>
            <p class="price">$360.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMSBhITEhMVEhUXFRgTFhcSEhYVEhUWFxoYGBUVFRUYHighGBolGxkaIjEhJSkrLi4uFx8zODMsNygtLisBCgoKDg0OGxAQGy4fHSUvMC0tLS0tLS0tLS0tKy0tLS0tLS0tLS0tLSsrLS0tNS0tLTctLS0tLS0tLS0tMS0tN//AABEIAOEA4QMBIgACEQEDEQH/xAAbAAEAAwEBAQEAAAAAAAAAAAAAAwQFBgIBB//EAEsQAAIBAgMCCAgKCAMJAAAAAAABAgMRBAUhEjEGQVFhcpGhsRMiIyQyNHGyFCU1YnOBg7PB0RVCUmOCoqPwdMLxM0NTZISSk9Lh/8QAGAEBAAMBAAAAAAAAAAAAAAAAAAEDBAL/xAAlEQEAAgICAgEDBQAAAAAAAAAAAQIRMRJBAyETUWGBIjKhwdH/2gAMAwEAAhEDEQA/AP3EAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAw6nCekptKNSVna6UbdsjcPzSlPapOfO9FCTW/lsRMjrlwopfsVOqP/sbGGrxqUIzjqmrriPzyOtFvXT5sn/odrwaqbWR0nzP3mIGmACQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAB8e4/PMBH4rP0Kb8R+w/M8FiZ/olWi/8AxvT+YiRfwcfNZnUcFPkCl/F78jjcuxE3QneLXtpS0/mOw4HzvwepPdrPitunJbhCGyACUgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAZfCLPKeDy2VWo7tLxYJ+NOT3JL8RM4F3HVlDBVJvdGEpP+FNnAcFMJVq0ZeU2W1fRQaV9dFOMkj1mmb42plU4TgrzlseKl4PYqXUYyj6SsrNtS493JU4OZlWoeDpxw7qSqQjUV6qj5NtR8XSzlfnRX8lXfCWvn+XVKeBk/COX1Uov+nSi+02+BOI2+DVF6XW1B25Yyab9r3/AFnO5vn9Svj5YSlhpymvS2pxi4ys5LTVNWT40ZuSZliqOVy+DRm4upKMFVVOUfCfrppWkk3F216riPJXpHCX6iDn+CHCL4XgE5qMKqu3GL8WUdqUVOHNeLXM17DoDuJiYzCJjAACUAAAAAAAAAAAAAAAAAAAAAAAAAAAp47MqdKSUm9qXoxim2/wX1tHA5hOVaMYW2pYi9WSbuozpzcVbkWy0vqRu43FqvmDlT9HY2U3xuM9Xb2p/wBsiyzCxVSlXk9mKTivtLW7e8y+S03nHS+kcYyw/D1IxqSfoqSir8b2pRXfHqIqFSrGtRX/AA8PFx9jnDusb/CLCpYeikvSxFupv8j1Xwq+G01bfhF2TjbvOeKcxhj5ZVmuG1aq1q5xi/rhJKxFlyqfoColpadWr/Epy/8Apu06CXCqurfr0H1qxPkVOLyutp6M68f55vuaO4iXOYc3luUxqUsLR2pQjC72otxmpK1SpZrVXlfrO1yHPadXD0oOflXH0Zek9nRvke6/WcvTwkvhUJRTa8HNtrlk3a/tYweM8HjpOUfRrKd0tVFJSkl9Un1kUvxTauX6EDxRqqdGMo6ppNexns1KAAAAAAAAAAAAAAAAAAAAAAAAAjru1CXsfcSEeJ9Xl0X3CRzHB+glUSXFTi+tzf4FXEVb8FbrTVNLkSqadiNDIfWfsqXdUMjDQcuDaik29laLV6TZkj1Vo7W80lfA4F771rv67lnHxtntBfuNntv+CKGMxKllWH2VJulO8oyWxJ210UrXvzH3MMzTxtGtGDdobEotxUk29eO27nO8/wBOF/DK/CzEacdHsTIuDj8zxv01buK1PM1HhBOsk5QqbG5x2oqMdbq+ur4jzlGOjSeJhNO1WdScZKzj42kYvjT+qxOUNHKatuDm097cY39slGPazOxeC2cRXk1xtp8q8HG/amT4PGReQSpaqcHF2lFrRzi04t6StzF/Ndz9kvdKrRH8f6srLTySns5TSjyRS6i8VMq+TqfsLZrrqFE7AASgAAAAAAAAAAAAAAAAAAAAACLFerT6L7iUjxHq8ui+4SObyLTFW/dUu6oUMm+SI/RvvmX8oVsw+ypd9QpZGviyP0b96ojLXpfPbmcdwg8HXqxVOPiRnPxqkrtQqeCvsKFtZ3stq58xGPquuoPwGskotUZ1I76seOrGzTpSVrb9DbhlFFuUpKbcpTbXhqqhrOW1aClazetrHqWQ0PF2KOH42/CUYzbe9avdq3d85flk5e8ObweJrS2ZR+DwvZPaw8oTg5aKMk6yt+px8dtWtfX6WrKlGU1Rs1FyXjxcdqLlxSnxq2qT5rb+ifB6n4W8qOEcbptRw0E7Xk7XtxXjr8x7r6ev0DhdvSnsPf5Kc6b5L3g1xaEZJzCDJ8Vt5HUqbOw5KzipbVtmbjbasr6q+43s0/yVH3GFClCjldaEE1GKdk22/wDaNu7er1udBmC8lLmpz70VeTbT4tNfKPk2n0S4U8o+TKXRRcL66hXOwAHSAAAAAAAAAAAAAAAAAAAAAAI8R6vLovuJCLE+rT6L7iJ0mHO5b8pP6Kl71QpZJ6ml+6fv1CzlUvjD7Cj71QqZE/JL6KXv1DLXpfbtNh15utbeNP3pEVZ7NRNbT42krprjS5yzg6DeDT36yf8AMyLGbUaUnx27Cy0T0x+o3ChUjJUtuDspLYklPVS2l43tt1NlvCbrJfj1szMHOawaT1Tftaje9r/WbmFgot2/1RXT1KbW+T2y8VHzHEL6uuozfzL1ep9HL3kYWMl5DE+2Pvm3mT82q9CfvI6vv8NHj1DYyn5MpdBFsp5P8l0ugi4X1/bCudgAOkAAAAAAAAAAAAAAAAAAAAAARYr1WfRfcSkeJ9Xl0X3ETohymXytmP2NHtlUK+QLxI/RS9+oT5ar4tfQ4d/z1CvwdfkKXPTqdlR/mZa9L7drVO7y6Mdna1fGtPGfE9/GeK68xnG2y1FpWa1dt6S3a8R8weISopXS38fOSSavvT5ky6WSZY9ep40LRaUpqKVtVGFr+3Xezbp0G46XRWxFVLxrN7P7Ku9Xd2XtbJ8NmkW7Wnyeg7b7f37Cqtfqn9MWxDKxUWqeIj86HbK5uZg/NK3Rl3oycdriMR0qPfE08Y/Na/Rl+BN9/ho8em9lHyZS6KLZUyr5Np9FFsvrqFc7AAdIAAAAAAAAAAAAAAAAAAAAAAjxPq8ui+4kI8R6vLovuIkctlKtjbfuaHZUqFXg6vNaPQqfeMs5a/jB/RUfvKhmZfiHDKqco2uoz37v9qzLn1DRMPMatnrSjLnlG76yWOMtK6o00+VQsy1Xxk4xh43pV/Au+tk4748ju+cYjEzUYraeuH8K3ptXUkrXtbVPkLucKvjlUljZN+gup2PMMW1LSnFfwmrGcnmU4bTtGrCGnGpwUnd+258wtRzwc5tvxVWas9PJzcY3+ruHKPo5+OGXCbm6jas5Spez0kjVxL80r+yX+U81Up4CMnvcsO97t484X0Z8rPzOv7H7sSq85ldSMQ6XKl8XU+ii0Vst9Qp9FFk011CmdgAJQAAAAAAAAAAAAAAAAAAAAABHifV5dF9xIR4j1eXRfcJHI5V64/oaH3lUyKU/ieHQl97I1cp9a+ww/vVTFi/iePQf3kjH009tDFy1prkxke2J6rSvCD/5SS6ppEGJl5yv8VB9cZfkeoyvh1/han3qOkNOg/jWpLlxFJf0l+YwC+K588MS+urIU/WW+XFUvuqZ9w7tgX9FiPvCXL5SfxdBc+E9+JFWfmWI9j91EkF5lFfOwvvxK+IfmOI/viic2dQ67LfUKfRRZKmUv4tp9EtmquoUTsABKAAAAAAAAAAAAAAAAAAAAAAIsT6vPovuJSLFerT6L7gOPyuS+FX5aFHslVMJytlkV8yXvzNnKYPwkb7/AAFNdTrdljKxlBrDRjb9TvqPTtMmPTRlZxPrv/U0vdmMNd4KT5MPU+9Rbjh9rPHHkxEX/wBtOrL8DzgoL9D1bv8A3E1v/ey/I7w55LMJeTUuXFUe2lRPtN+Zv6HE9lQjbtlCd1pXoP8ApUSeurQgv2qeLj1OT/AYMvcV5JL52G7JJ/gZ9Z+YYj+HtRp21nzfB32y/IyYX/RNd8vg/rvTv+JzMe0xLs8oXxbT6KfXqXCtlqtl9NckEupWLJprqFM7AASgAAAAAAAAAAAAAAAAAAAAACPEery6L7iQ+NXQHDZN4WdR2lFtUabvK6Wu2rcdzJxWIq3Tstz0b+enbd+1JHWUOCUKeKcqdScY71BTmlf5zUk5LmK0uBa8HpWltbOztSTate9tna3bupFXB1yc/XrTjiZvxW3WjFqV5RvKM7yV3uST3kdK/wACtdbLo1JbldOFRWS9t+w6KpwLb2vOGnKSk/J3SsrKy2t+rI6nAeWlsVKKs00qa1u7vj3cxPH7GWRTpXqbF7R8Jh7S2VtXqwhtK/IrvQmhScqEWpJJRxNkk90JzXLZN79LWuatPgXJVn53U2bqSjspWaVk733pW6iejwVmqGzLEyktmUV5KCVpavdr23HH7Gfuw/htXwdWa4oU/wBdOWzdqLts2fLzEtXEVFltWE4Ws1HTYesYpK9mbEeCS+BuHhbJ7N1BShHxdbWUrpX5zzW4H7UWnXnq2+u2+71em/nI4J5NrIq7qZRSnLfKN31svlfL8HGjgoUoX2YRUVd3dlyssFrgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAf/Z" alt="Centenario Plata">
            <h2>Centenario Plata (750 ml)</h2>
            <p>Tequila joven y fresco.</p>
            <p class="price">$300.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Tradicional">
            <h2>Tradicional (750 ml)</h2>
            <p>Un clásico tequila reposado.</p>
            <p class="price">$270.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Don Julio 70">
            <h2>Don Julio 70</h2>
            <p>Tequila premium cristalino.</p>
            <p class="price">$1,900.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Dobel">
            <h2>Dobel</h2>
            <p>Tequila ultra premium.</p>
            <p class="price">$1,200.00</p>
            <button class="button">Comprar</button>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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gr9aWsxI3IUJObXK8lvsBtckz31HFHqKb6ipUChiql0C7m6wvZUFhuJW4Azm9zMd1TdZRUKMCVJNwoOABYZPPv7oEzwfT0Fphauoos7CibstcshqNUFVDaoNxpqyN3BtuDjPStRpWJGop03WojItM1r1NtWqAlzUIW6BWODzXPZNz6gkWFiMLfdc2ckMeWdoN/aJ4JUq229WhTcbEsS2cEgFbXyTz74G4uDsDxFF8Fqsf3gAf4WmwJr7o5QB11N7ZHWpfxBDGx9BH+rzYMBERAREQEREBERAREQEREBERAREQEREBMTiqE0agAuShxjOOUy5wygix5HBgan1WoKMesdaNMYDEgFiDy5XFrd1rX5zs2m09UdY1PrmRdtMM7HcLEgDa1zzvc5zLbquiRNwtVSpN7VULH1m+fZOdN0TdOVamva3dmkQb95uH98gqT9GqApdYaFJGJwCKt/e3Zz5TpS4HQ6vc9JFJOMZPnLrqOiu+26u2O6xt6wSbzlui5It85qW8NqWgVHhfCtIhs1CnWBP6QX5zD4pwyklU209A0ySdop0jt93Lzl80nRWnTNw9ze9zTo+/E9db0bp1Td2P7G5AfSFYCBrhuGafZvGk0hO7bmklgbXAIFrXsc+RkXradNCpGj0quT2N600AuMixw9vG/gRNot0OpFSvWMFPOw8M958Z1pdC6a/pnOb9paZ99r+MCF6EVazagdaqqbNstzIs+Tk9wX2zYUi+EcEp0CSGd2Pe20WHgAoA9fOSkoREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQERED/9k=" alt="Herradura">
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
