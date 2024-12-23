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
            background-color: #f5f5dc; /* Blanco crema */
            color: #333; /* Color oscuro para texto */
        }
         #age-dialog {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: 1000;
        }
        #age-dialog button {
            margin: 10px;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }
        #age-dialog button.yes {
            background-color: #28a745;
            color: #fff;
        }
        #age-dialog button.no {
            background-color: #dc3545;
            color: #fff;
        }
        header {
            background-color: #fff8dc; /* Crema claro */
            color: #6b4226; /* Café oscuro */
            padding: 20px 0;
            text-align: center;
            border-bottom: 2px solid #6b4226;
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
            color: #6b4226;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        header nav ul li a:hover {
            color: #333;
        }
        .slogan {
            margin: 10px 0;
            font-style: italic;
        }
        .product-section {
            padding: 20px;
            text-align: center;
        }
        .product-section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            color: #6b4226;
            margin-bottom: 20px;
        }

/* Diálogo de verificación */
#age-dialog {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.8);
    color: #fff;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    z-index: 1000;
}

#age-dialog h1 {
    margin-bottom: 20px;
}
/* Aviso de precios */
        .price-notice {
            background-color: #fff8dc;
            color: #6b4226;
            padding: 10px;
            text-align: center;
            border-top: 2px solid #6b4226;
            border-bottom: 2px solid #6b4226;
            font-size: 16px;
        }
#age-dialog button {
    margin: 10px;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 18px;
    cursor: pointer;
}

#age-dialog button.yes {
    background-color: #28a745;
    color: #fff;
}

#age-dialog button.no {
    background-color: #dc3545;
    color: #fff;
}
        .offers {
            background: #fff8dc; /* Fondo crema claro */
            color: #333;
            padding: 20px;
            text-align: center;
        }
        .offers h2 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            color: #6b4226;
            margin-bottom: 20px;
        }
        .product, .offer-card {
            background: #fff;
            margin: 15px auto;
            padding: 20px;
            border-radius: 10px;
            width: calc(100% - 40px);
            max-width: 300px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            color: #333;
        }
        .product img, .offer-card img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
            border-radius: 10px;
        }
        .price {
            font-size: 20px;
            color: #6b4226;
            margin: 10px 0;
        }
        .button, .contact-button {
            background: #6b4226; /* Café oscuro */
            color: #fff;
            border: none;
            padding: 10px 20px;
            text-transform: uppercase;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s ease;
            text-decoration: none;
            border-radius: 5px;
        }
        .button:hover, .contact-button:hover {
            background: #333;
        }
        footer {
            background-color: #fff8dc; /* Fondo crema claro */
            text-align: center;
            padding: 10px 0;
            border-top: 2px solid #6b4226;
            color: #6b4226;
        }
        footer p {
            margin: 0;
        }
        @media screen and (min-width: 768px) {
            .product-section, .offers {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                gap: 20px;
            }
            .product, .offer-card {
                max-width: 300px;
            }
        }
        
    </style>
</head>
<body>
    <html lang="es">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Página de Verificación</title>
            <style>
                #age-check {
                    position: fixed;
                    top: 50%;
                    left: 50%;
                    transform: translate(-50%, -50%);
                    background-color: rgba(0, 0, 0, 0.7);
                    color: white;
                    padding: 20px;
                    border-radius: 10px;
                    text-align: center;
                    font-size: 20px;
                    box-shadow: 0px 4px 6px rgba(0,0,0,0.3);
                    z-index: 9999;
                }
                .btn {
                    margin: 10px;
                    padding: 10px 20px;
                    font-size: 16px;
                    border: none;
                    cursor: pointer;
                    border-radius: 5px;
                }
                .btn-yes {
                    background-color: green;
                    color: white;
                }
                .btn-no {
                    background-color: red;
                    color: white;
                }
                        /* Estilos del overlay (bloquea toda la página) */
        #overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.8); /* Fondo oscuro */
            z-index: 9998; /* Asegura que esté encima de todo el contenido */
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Estilo del mensaje en pantalla */
        #age-check {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            font-size: 20px;
            box-shadow: 0px 4px 6px rgba(0,0,0,0.3);
        }

        .btn {
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        .btn-yes {
            background-color: green;
            color: white;
        }

        .btn-no {
            background-color: red;
            color: white;
        }

        /* Este estilo asegura que la página no sea accesible hasta que el usuario responda */
        body {
            overflow: hidden; /* Bloquea el desplazamiento de la página */
        }

    </style>
        </head>
        <body>
            <!-- El overlay con la pregunta -->
            <div id="overlay">
                <div id="age-check">
                    <p>¿Eres mayor de 18 años?</p>
                    <button class="btn btn-yes" onclick="checkAge(true)">Sí</button>
                    <button class="btn btn-no" onclick="checkAge(false)">No</button>
                </div>
            </div>
        
            <script>
                function checkAge(isAdult) {
                    if (isAdult) {
                        // Si es mayor de edad, cierra el aviso y desbloquea la página.
                        document.getElementById("overlay").style.display = "none"; // Ocultar el mensaje
                        document.body.style.overflow = "auto"; // Desbloquear el desplazamiento de la página
                    } else {
                        // Si no es mayor de edad, redirige a otro lugar (puedes cambiar la URL)
                        window.location.href = "https://www.google.com";  // Cambia este enlace a otro si lo prefieres
                    }
                }
            </script>
        
    <header>
        <h1>Delivery Express</h1>
        <p class="slogan">Vinos y licores a tu puerta, cuando más los necesitas.</p>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#vinos">Vinos</a></li>
                <li><a href="#ofertas">Ofertas</a></li>
            </ul>
            <a href="https://wa.me/523325905963?text=Hola,%20quisiera%20más%20información." class="contact-button">
                    Contacto
                </a>
        </nav>
    </header>
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const now = new Date(); // Fecha y hora actual
            const notice = document.querySelector('.price-notice');
            if (now.getHours() >= 23) { // Si la hora actual es después de las 11 PM
                notice.textContent = 'Pedidos realizados después de las 11 PM tendrán un aumento del 20% en los precios.';
            } else {
                notice.textContent = ''; // No mostrar mensaje fuera del horario
            }
        });
    </script>
    <div class="price-notice" style="text-align: center; margin: 20px; font-size: 16px; color: #333;"></div>
    <section id="vinos" class="product-section">
        <h2>Explora Nuestra Selección de Vinos</h2>
        <div class="product">
            <img src="https://oasisvinosylicores.com/wp-content/uploads/2024/06/Img-W-15.png">
            <h2>Vino Tinto Syrah Viña Maipo </h2>
            <p>Delicioso sabor suave, de color rubí y tonos violeta.</p>
            <p class="price">$150.00</p>
            <a href="https://wa.me/523325905963?text=Hola%2C%20buenas%20tardes%20quiero%20comprar%20Vino%20Tinto%20Reserva" class="button">Comprar</a>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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">
            <h2>Vino Blanco Viña Maipo </h2>
            <p>Delicioso, refrescante y perfecto para cocteles.</p>
            <p class="price">$150.00</p>
            <a href="https://wa.me/523325905963?text=Hola%2C%20buenas%20tardes%20quiero%20comprar%20Vino%20Blanco%20Maipo" class="button">Comprar</a>
        </div>

    </section>
    
    <section id="ofertas" class="offers">
        <h2>Ofertas Especiales</h2>
        <div class="offer-card">
            <img src="https://i5-mx.walmartimages.com/mg/gm/1p/images/product-images/img_large/00329711001413l.jpg?odnHeight=612&odnWidth=612&odnBg=FFFFFF" alt="Champagne">
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
            <p class="price">$359.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Torres%2010'">Comprar</button>
        </div>
    
        <h3>Ron</h3>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Bacardi Blanco">
            <h2>Bacardi Blanco</h2>
            <p>Ron clásico ideal para cocteles (980 ml).</p>
            <p class="price">$250.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Bacardi%20Blanco'">Comprar</button>
        </div>
    
        <h3>Tequila</h3>
        <div class="product">
            <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxATBhUSDxMQFRURGBkYFRUQFRUWFhATFhkfHRcaFhcZHikhGBolGxcYITEhJSkrLi4uFx80OjMtNygtLi0BCgoKDg0OGxAQGi0mICYxKysuLS0tLy0tLS0tNTAvLS0tLS0wLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAOEA4QMBEQACEQEDEQH/xAAbAAEAAgMBAQAAAAAAAAAAAAAABQYCAwQHAf/EAFcQAAEDAQUBBwsPBwsFAQAAAAEAAgMRBAUGEiExEyJBUWFxswcUIyYncnSRobGyJCUyMzU2UnN1gYKitMHRFjRCU4OjwhdEYmNkhZLD0tPhN1RVZZMV/8QAGgEBAAMBAQEAAAAAAAAAAAAAAAEDBQIEBv/EAD0RAQACAAIFCQYFAwQCAwAAAAABAgMRBCEycbEFEjEzQVFhgfATInKCkcEjNGKh0RRCQ1Ky4fEVJAaSov/aAAwDAQACEQMRAD8A9xQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEHBf9qdFcc8rDR0cT3NPE5rSR5VXizMUmY7pd4cZ2iHn9nv8AtZfXdXUP9JfOYmk43+uWp7DD7mU1+WvdPbX/ADOXFNJxu28/UnBw+5dsKWx8txMkkOZxLwTx5ZHNHkAX0ejWm2FWZ6WZixEXmIS6vViAgICAgICAgICAgICAgICAgICAgICAgIILHbqYKth4rPLs7wrm0ZxMO8Pah4thK95N3DdTr8Nw2a8vEsDS8KI1w1KW50a3fiy9JAcoJ112u4+dVaNSLa5TbVD0fqSy5sBwk1rmmrU113Z/kX0WFGVIhl4s53lcFYrEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQQGP8A3j23weX0ConodU2oeA4Zly2xvP8AcsXSozrLTwkhiies3zKrRK5Q7xcsnq/Uc94MPfz9M9buHswy8XaXZdqxAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEFf6oDScD20NBJNnloBtJyFRKa9LwK4rptbrQ0sgmI48rgK04wRos3F5sxP8T/AA99LZf9uq/rntu9LrPPSmpDXnn4Sq8CKx2T9P8AhN7es3rvUcY5uA4g9rmkSTaOFDQyuI861abMPDibS7LpwICAgICAgICAgICAgICAgICAgICAgICAg1WoAwEO2O3pr/S0+9BqFhiyAZGaU2gcGxcezr3J5097Z1uzMTlbV200FSdmvHop5sdxm03ZI02chpByOLDQjQt0IPEVMIdikEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBBVcYYrFneIICHWiRr3cYgYxpdmeOMkBoB4ydgovLpWkexpnHSvwML2ltfQ8+nvu3WnD75ZLRI5jB2RuWNrHOzHKN60GmjdhryrKtp+LGJFJ7Xv/psLPLJNWTqozluZ1kaI4WtMzhIavc6lNyBGnsq748BHKvfOn1rzYy6f+f4eaNDmZmM3Rauqe/O6SGyk2eMtYXTOyPke7U5cuYANBG2ta8Cm+n0raKxrzRTRJtGuckNfF72qOzQ2tsj4XW2QuMcTjka3Y3Q6EloBJO0k7K0WfOm4lsa0U1Rlm9OHg0y5tozyWHBWKZ2Sdb3tIC92+jmeGMBGwMfQAAngPDs20r79F06uLOX0eXH0fmxzq9D0AHTRaDyPqAgICAgICAgICAgICAgICAgICAgIK1iDE1nGeywzMNpOVu5sdV8Ye5rS409iQH1112Lz6Rixh4czmtw8OZmNWp55hPD4iw3bJnnO7KS17qlxa5hLiSdakuPiC+e0vH9raMuzLP6tHZtFe9ndtnA6j0zhtc41PH2QAeRTaM8bnd0xwTn+NEeEsLRZAzqTF49lIYyTzFoHmXEWz0iN8x+yed+Jl4GIrMGdS6Bw2yOY8nlcP8AhMLXpGfxR9Cs+/aPBux1FS4LtHeei1c4O3af0zxRh2ztZl1TLFumIooBp1xEWfOTvfLRdaNaMPnW/wBOU/sYM54c5u/qd4qs1juPra3TiPc5pGQukzUyB7hQupRoBa7bQUIX0GjaRF4ynwn6xDxY+DMTnEPUGkEVGw8XCvW8r6gICAgICAgICAgICAgICAgICAg02u1MisxkkOVrdp1PJsGpNdKKLWisZymImZyh5jabE0XpNaqDM4xOrxtknq089QV8lpekziXmleiZs1sKmVYifWpMCMC6LyYNjMwA4huIKpwY9zP4eMubTnfDlWbtB/kcl749KF7Z6y3xV4Jnro3N95M7jreaP02qukfjc79VuB/m8nzFje5RZv2XolThRljVnxuinW2hl1QW+sl287PQaow4ynP9P3Tg7V97rxu3t+sHOPTC4mMq4nlwRgdVPmiMRXM2WMuA1baZGCnCQ1x89Vxo+Pak5T3R9l+qdXhm9KwbeUc1wxBrqvijjZICCC1+Qce2vGF9VgYtcSmcbmRjUmltacV6oQEBAQEBAQEBAQEBAQEBAQEBBH3vJRrOVxHijefOAvDyhfm4MytwozlR7z9zpD/V2I+OZ6+WiuvPfwaddqI8bcHaHep71HFU+OEfgrcHVSY3f7pVz/iVq6X9x6YcTj0oXqnrLb68HVuurub7a7uQjk3IfWaVzXa+aeEn+fyY4idXqT2fnZ5CUpPv133TWPx7bjHb64bu08jPQCR2R+meJgR7996Rxse3ewcrh6bfxXNoznEy7q8EaP1NvNlCKvAP/knjxtcvLWuc+X8OrTlHypfBAAt0jQNsba8uV7wPv8a2uRrTM3jc82mx0SuK3HgEBAQEBAQEBAQEBAQEBAQEBAQRV/8AsYu/PRvWbyr+Xl6NG2lLt3uO/wCJsHTPWBl7vruaEdZ524Q6JJBmvVvC7Qcp3IfiubXis5d+X+5zFZmMOVYudx/ksmi/Te45W8LiH7AOPRejExYjSObPfE/ssnDmbxPhLptjiOpduRBznczlIo7QtqKbdMpVdMWPb83s50z+0nMmcTPwar8f3MoY/wBJuR2XhpXXTkqmFiZ6Rze6bfumKT7SbeEPmM5K4bsDeGPICBwVYNTxcSYF+diWjuiY/cpTK1pSOMJs2M7vI/WAeJ7KqNHvz4xLT3VcUrzcKY3u2ze3D5Vd6Lkwo1x67nN+j5Ungh3rk/4v/PkH3LS5HjK1/JTpuzHrshdFvM8QEBAQEBAQEBAQEBAQEBAQEBBE4hPYGHic4+KJ6zOVvy/nC/R9v13qVanVuJx47Pd/TPWJMe7Eb/u0I6zztwc1qtcbcS2xs2QMaWvc6QgMG9aNa6fOVFMKb0raIznoTW/NpXs1M/yksJjGV4kFQOwQyyip2CsbCOJeimgY09FcvpCu2NWO1zy4ohexphbay1w0cywzSBwLQ5paXMA9jvth0KupyfiRtVj6uPb17JaocVwm0tDmWx+bVresJASCKtIoKnQE1G0BdW5PxJjVWI80RjxHa3OxfdRja+WrM4qx81mma1zdNQ8spTUa1pqF555Nxo7I8pdRpHi6G3jYpJopoHRy1niYXRvDsrnuoCRWgI0Oyq899FvSJiYy1Z/Rb7bOuWecOiyns396n0SowZ113Qi/R8qRwIfXOT4s+S0zLU5J27+SrTdiN/2hd1uM4QEBAQEBAQEBAQEBAQEBAQEBBFYh/NB9PonrO5UjPA8/5X6Pteu+FHtHvePg13dM9Yk7P1aH+XztwhDYnsrpL4t8bAC54YxocQA5zjGACToASdqu0W0YcUm3REzM/RXbXSN33ZnDV4OtRkAa09cSTsM1rLnNdKxrMpy2cnK0N3oa8CtK1oF6L/8AyDQ41RMzuh5Y0e7hFge62uL57Hm37JGNhtWQk2cWd4FGb0Usz3CmmvFSvprp8zETGHOXTGuvblMdvjCJwsu1lDusUDWx2i7zuQjERe20diayNrGjVhqCInuFeGWvCK8/+Rtnrwrf/n+fH1lKYwfFvs1329tDHDZjHRmQWaYNc1gEGXV8TC4gQEipFN0p+iFV/wCc0WLTW2cT4x/Ey7nRr5ZuO6rHNDbQJ2yNc+1WH20sL35Q2IveWOcKucwu2nbtXGk4+HpHvYU5xzbOsOs0rrWyz+3f3r/CVn4Ue9C+/R8ruwEfXWT4t/2qZanJW3fy+yvTdiPXZC9LbZwgICAgICAgICAgICAgICAgICCLxB+aj6fQvWfyn1HruldgbX04woto97x8Gu7pnrDts/X7tL/L524NFqYfyutJ4N1hH1oiur5ezmPC3CXER7lZ8FvtDaNq068S+XrWna6pOc60U615Q4EsB01cNMrnZa6HWldRp56e3C0WLzHvTELLVjshHw3g/ryaKVrC6EgBzBQSOeTsrUCgoSQTtPz+vSNBph5WrecterPPoRhzE5akxFZ3CDQAE7acHIK7FlXxKzbV/wBu+dEzrVy+4qXnDtNJ7FX/AO5W7ybOeFPz8IU485y74fbz8q/wq3DnXDm3R8rrwD7sSd4/7XMtLkvbtujhCvTNiPXZC+LbZwgICAgICAgICAgICAgICAgICCLv/wDNR9PoXrP5S6n13SuwNr6cYUSY9rp8Gu7pnrCt0fVpf5fO3BtkiriG1O/r4x4hGV3bXWY8LcJcZ5YddyyWizuIdrodlBqNNQeA/wDK+cmsRWJiOjpKXiJVjEREFjLxvsgBymjGtroSXu26VIaOE8AotbRbRi2iZnXPZln+z1Yedpy7O/NvveaB1iszoxEXSGNrS0DO5oPseZrc5+blXr0ikez93ulzhRal7Rbo/ZNwF2ShC+XtVzfm55q7iAH/APXhHDu1lPzbsarf5M6ifm4Qqvrzbo/bz8qjzK2k5WhE9HyuvAXuxJ3kn2uVanJW3bdHCFembEeuyF8W4zhAQEBAQEBAQEBAQEBAQEBAQEEXf/5oPp9DIs/lLqZ9dkrsDa9d8KG/3unwa7ulesCNee+WlPW+dkgGevNqP9pZ0caviM5ynx+6q0/h13fdZbba2MOQiQ1FasY5w28JAoCvJi4POwZikxlvees+8quKbrdaBCxry3O8AjfAvaRmI2jgaagjj2LzckzMYtqZa+/uaWFauUzbojW5bws7RZ2mzg5mSsDa8D2HXLWoqG5hzE68WrjVrXDtMzqyn19XdZta2V9/ks8ZqATUcnEvlsW1ZmZh551akRe0db4j5DCdtNkjuQ14qcu0LZ5Nt/60/NwhX3uZh9Uv+VB5lbacr5eEup2Y+F24D92ZO8k+1yrV5J2rbo4Qq03Yj12Qva3WcICAgICAgICAgICAgICAgICAgjL/APzQfT6J6z+Uuon12SuwNr13woL/AHuu8Gu7pXL5+v8Advlpz1nnZKtHq+2HitLeiYvTOzM/F91Ftiu77pC2QudLmc9tGmrAWA7ns2Gu2oBWJh6fNK5Zb9fSRhRPQ4bzkeIg5pL5Iy5zTlFTUFoFARwOpX51ZoGJEYszGrOHqw6ZRlPROpzWeyTtt8bXAZIw5zqHTdpCc5JG0002U1Xq5Qxaxo84czr9djqL1tE37Z4Qs0MYcFi6PhVxIeO9prKNnhpfJ5I2nxF62tDpzcC0R+rhCOdnH0Qv86k+U2qcXrLbpW/2x8LuwL7tyd5L9rlWtyTtW3RwhVpmxHrshe1us4QEBAQEBAQEBAQEBAQEBAQEBBF4g/Mx9PonrO5U6iV2Bteu9QXnted4Nd3SuXz9f7t88GnOvE87cEwB6pttP+5HQMXptH4dp+LhZRM6q7vu2Nvazv0EsZrxHbrTzg+JfPToePH9kvRs62+yz2eQ5WvY8ka0Nd7oT5POvTo+DiYNs71mPFXe9miWXcpXSyP3hNTUbPENi894tpF8qxnK+ebNIq7rPfFnqeys0BJrpQNFXE8gArzL0aNomPX3ppLxX7iXW9nEfqf9xaGjZWwrZfr4Q57Por386f8AKbfuXOLGeLO6fu9H9kfC7sD+70neS/a5Vrclbdt0cIU6XsR5cIXtbjPEBAQEBAQEBAQEBAQEBAQEBAQRl/j1K0cZd0T1ncqRngecLcHaUCT3vO8Gu3pnrB5uX1ng04n8TztwTVnbW120a62kbKVHYGbKgjyL1R1OeWeufuonXFY8Pu625gfZSeKL/bXjrouDWc4rP1kmJntbd2fTa/xR/wChX2rSYy5v7ufZ+LRIwna5/wC7/wBC839HgZ7M/VZE2jtYxx5djjrrsj2/4VP9Ng90/wD2lExMttmb6pcSSSWOGtNA1riNgHwir8GlaVtSkdl56c+z/hzaMo+nFBfzl/ypH5aKmPetFu+Fs7MfDLuwT74pe9n+2SLX5MjLFtHhH2VaV1ceXCF7W0zxAQEBAQEBAQEBAQEBAQEBAQEEdfQ7EzvndE9eHlCM8LzhbhdLz2Y9rh8Fu3pnrFvHGeDRjrPO3CEzYmyOvK8WxyyRESNIdHlzA7k34QI4OJUXxsTCn3Z1RnPTPfPcrmK82mcZuK6LxtM2EZpeuJ2ujzHM0tLnZWg0Je00B5KLu2k49cTamY1ds9rvEwsOuJFcmuK9rW/AvXW7ytdGXEiMt7JR5ADi8OcBSmwhd/1ONGLNedOWqNcz2wj2VPac3KGy870tQwhDaxPM1xDKsYWhjy74RLS7bxOC5ppWNz5rNpmM5jpnPUmuFT2k1ybsRXlaorDZ52zy1lLWlm8EZqK1O9zE6fCAUYWl4+WVrT0TPjq9dyMPBw7WmuXQ6r/tksV7wDdpi20HKYyWZG8oo0OJNeFxHIonSsa1JpM9nFzhYdLRM5dCOI7NJ8qRfwpSuWXhl93czqj4ZdmCj2yy97aPtki1OTuuvuj7KtK6qPLhC+LZZ4gICAgICAgICAgICAgICAgICCOvn2DO+d0T14tO6rzhZhdLz2T3snwW7fJNIsXE1fvwaUdZ524QsFyj16vLv29E1UYkbfwzxlVfYw0Dgz3gWv6fRhTeNr5eK/H6+pYB3KZOd3SJl71p8Y4In8xXcXv/ANLoednnUUjon9VuElfzFtzZjZ3anYz/AEmdGVFa+7XdbjBo/W3dOO3Uvawcrx6TFOWv5a/dxo+zdhJ7fL8qQ/wqyOn1+pHZHwy68G++iTvLR9sd+K9/JvX33R9nGldVHlwXxbbPEBAQEBAQEBAQEBAQEBAQEBAQR18+wZ3x6J68Wn9V5wswulQsnaufBbD9WSQrCxJ1xvaUdZ524QnbmHr3ePK5vRgfcq7Trv8ADbjKq+xhq7go9z+2ftOiau7/AN3y8V2N11H27z3J5ed3SJ22314F/wAzG4vc9yqHnZ6RUU7Pit901/M23PuOXdpVi52dGVNOivzcUaP1t3X1QD66Xf349JiiOn5a/dxo2zd9tDaPkPHecJ+s38FFba59f6kxGqPhl2YTbTFb/i5/LaifvWhyZOeNf13K9K6qPLgvK3WcICAgICAgICAgICAgICAgICAgjb6PY2d+eievDyh1M744rcLpUmf3uO8Gsvke9fPTOuI3NH+/ztwhMXR7s2/nHolcTO3uni4vsYatYHPc/tn7Tomq/F6bfLxWY3XUfbuPcll53dIoz960fqrwLfmI3F7nuURc7PTKinTEfqtwkr+Ytu/gx2e0ixc7OiKmnTEfFxgwOtu6+qAfXS7/AIwelGuazrn4Y+7nRtm7bb3UY4/+wiP11VFtdvP7uqx0fC7MLHtqd8XN5ZwVo8k9dO7+FWl9VHlwXhfRM0QEBAQEBAQEBAQEBAQEBAQEBBFYhPqdnf8A+W9Z/Kf5ed8cV2BrspUvuO5v9ni+qXlfOa/aRvaM/wApS55PXW2n4Tmgcu8r968975Uz74njKL11UjuVjA0naHaxxmTyQtXr0qcsWI78uLvEjPErLK7pO5TIO/6RRe2Wkc3xjgi0Z40SXrJ3Koh8Wf3hSk/+xzfGZ/ZMR+NMvmOJO0iycm59CVGj2zxpjuz4wYUfiWduPJK3ld/JKB9aNc6Nbnc/d/LnBjKLM7zk9SV+Fa43fXH4qrDnp3TwWVjX5JDCTu2g/FyeWQFa/JPW+U/Z5tL6qN8L4vomaICAgICAgICAgICAgICAgICAgg8YTZLoz6nI6oDRUk5XaAfOvFp9edgzG5do+2qmZrp5GtOgjI1FBQRvI9ML5qNVozaNtjP12N12SDdn6jfya/M0j7l47xnWI7lloVnB8gGFrQwkAuEx/dMHnK92k0tbGrMR0ZcU3yziXy7Zu51K3XRrydDwyHbxexU4mDedJi0Rq1cHM2jnZlunDupw1orvRFwHhfm8xU0wb/1XOy1a+Bzo52eZiyYOwZDQirHRCnCOwa+dRo2HaNItMx38U0tEWSWMa9eWIn9ePEXMI8gXn0WMoxN38opMZS33kPU1nH6ySN3laowo1zul1E65SeDqflATp7Bw8ZBWvyVH4s7v4eXTJ9yIXxfQs0QEBAQEBAQEBAQEBAQEBAQEBBB4wlay6M7w4tY9rnZWlxAFeAAk600A4VVjbLumu2UKtDZbG9hAme2WMZntY0lwzjMwSVaRStd6eCq8s4GBNedMZeK2MXEicmFksjCTuVrIGdw3rI3EUzU1OmoaTs4V566NgR0z3+uhZfFxJ7FfgtFm3B7uuJGh+ZobBSJlS0akOaSQaNB1ofGuuZg1nKc5TE4loRNmt1jZh2Vlpmfu7mvDck8jI90zvLTkY4NcKEVqKbeMqyPZ9lZRMYnfDYbVYjhvcN0l66OQNb1xKGtIaMxczPl49CNNFxz8KIm3M88nUUxZtlExmk7fDZ3Yfa0TShxkADN0dIGgACSrXA1pR7gRoBRcxiaPNc8kRTG5ySv40mgEdokcWyxj1VAab5pyuzAtZJWld5t50vg4MRzs51ope/c533vHIyN1RkizlhEcziRG1xaWgM3wOSunNwFVRoVOiJ6fB37Wa5zPFNYHkjN/Dc8x7G4gmNzRQ5Qa5hUEObs00I21Xo0LBrhzq6Vek3tPS9DWm8ggICAgICAgICAgICAgICAgICDGRgcyjgCDtBFQfmUTGfSI5+H7KdNzoPgtc9rP8AOXyLn2de51zpclnwfYmOJa2ap2l1ptLjw7M0hptOzjUexp3J9pbvao8C3aGUELqEk03afaaV/T5B4lE4GHM5zCYxbxqzDga7dyy9bjLxbpLQ84zpGBhx2Htb97IYJu7JQWdoHI+QeZyTg4c9MQe1vE55t/5KWHJQwgitaFzyK8dC5PY4f+mETi3ntZPwvYiQTCDQ5hVz9HUpXbxGi6nCpOqYRz7d77+TFhprZ4TztrqdqnmR3I50u6x3fDEOwxRR6U7GxrdNvAONTERBnMulSgQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQEBAQf/Z" alt="Centenario Reposado">
            <h2>Centenario Reposado </h2>
            <p>Tequila suave y balanceado (950 ml).</p>
            <p class="price">$369.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Centenario%20Reposado'">Comprar</button>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Centenario Plata">
            <h2>Centenario Plata </h2>
            <p>Tequila joven y fresco (950 ml)</p>
            <p class="price">$369.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Centenario%20Plata'">Comprar</button>
        </div>
        <div class="product">
            <img src="https://www.costco.com.mx/medias/sys_master/products/h2d/h51/101564564766750.jpg">
            <h2>Dobel blanco</h2>
            <p>Tequila ultra premium (750 ml).</p>
            <p class="price">$750</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Dobel%20Blanco'">Comprar</button>
        </div>

        <h3>Whisky</h3>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Etiqueta Roja">
            <h2>Etiqueta Roja (Johnnie Walker)</h2>
            <p>Un whisky con carácter (700 ml).</p>
            <p class="price">$400.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Etiqueta%20Roja'">Comprar</button>
        </div>
        <div class="product">
            <img src="https://m.media-amazon.com/images/I/611raIcZHfL.jpg">
            <h2>Etiqueta Negra (Johnnie Walker)</h2>
            <p>Un whisky premium (700 ml).</p>
            <p class="price">$1100.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Etiqueta%20Negra'">Comprar</button>
        </div>
        <div class="product">
        <img src="![image](https://github.com/user-attachments/assets/a9c92fc7-c638-4013-b4a7-6640f114480c)"

            <h2>Jack Daniels </h2>
            <p>Un whisky premium ( 1 L).</p>
            <p class="price">$750.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Jack%20Daniels'">Comprar</button>
        </div>
       
        <h3>Vodka</h3>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Absolut">
            <h2>Absolut</h2>
            <p>Vodka premium sueco.</p>
            <p class="price">$350.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Absolut'">Comprar</button>
        </div>
    </section>

            <h3>Licores Especiales o Gourmet</h3>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Licor 43">
            <h2>Licor 43</h2>
            <p>Ideal para disfrutar solo o en cócteles.</p>
            <p class="price">$450.00</p>
            <button class="button" onclick="window.location.href='https://wa.me/523325905963?text=Hola,%20buenas%20tardes%20quiero%20comprar%20Licor%2043'">Comprar</button>
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
