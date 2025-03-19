<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Vende pan de masa madre en Buenos Aires y alrededores.">
    <title>Pan de Masa Madre - Buenos Aires</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #8b5e3c;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            background-color: white;
            padding: 15px;
            border-radius: 10px;
            width: calc(33% - 20px);
            box-sizing: border-box;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .product h3 {
            color: #8b5e3c;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #8b5e3c;
            color: white;
        }
        @media (max-width: 768px) {
            .product {
                width: calc(50% - 20px);
            }
        }
        @media (max-width: 480px) {
            .product {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Pan de Masa Madre - Buenos Aires</h1>
        <p>¡Deliciosos panes de masa madre, frescos y hechos con amor!</p>
    </header>

    <div class="container">
        <section>
            <h2>Nuestros Productos</h2>
            <div class="products">
                <div class="product">
                    <img src="https://via.placeholder.com/300" alt="Pan de masa madre clásico">
                    <h3>Pan de Masa Madre Clásico</h3>
                    <p>El clásico pan de masa madre, con una corteza crujiente y miga suave.</p>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/300" alt="Pan de masa madre con semillas">
                    <h3>Pan de Masa Madre con Semillas</h3>
                    <p>Una variante deliciosa con semillas de girasol y sésamo.</p>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/300" alt="Pan de masa madre integral">
                    <h3>Pan Integral de Masa Madre</h3>
                    <p>Pan saludable y lleno de fibra, ideal para quienes buscan un estilo de vida más sano.</p>
                </div>
            </div>
        </section>

        <section>
            <h2>¿Cómo Comprar?</h2>
            <p>Puedes contactarnos a través de las siguientes opciones:</p>
            <ul>
                <li>WhatsApp: <strong>+54 9 11 1234-5678</strong></li>
                <li>Email: <strong>panmasamadrebuenosaires@example.com</strong></li>
                <li>Visítanos en nuestras ubicaciones en Buenos Aires.</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>© 2025 Pan de Masa Madre - Todos los derechos reservados.</p>
    </footer>
</body>
</html>
