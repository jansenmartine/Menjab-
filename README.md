# Menjabo
Pàgina dedicada a recomenar menjar de qualitat
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recomendaciones de Comida</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .panel {
            background: white;
            width: 300px;
            margin: 20px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .panel img {
            width: 100%;
            border-radius: 10px;
        }
        .panel h2 {
            font-size: 20px;
            margin: 10px 0;
        }
        .panel p {
            font-size: 16px;
            color: #555;
        }
        .opiniones {
            width: 100%;
            margin-top: 30px;
            text-align: center;
        }
        .opiniones h2 {
            font-size: 24px;
        }
        .opiniones textarea {
            width: 80%;
            height: 100px;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .opiniones button {
            padding: 10px 20px;
            border: none;
            background-color: #28a745;
            color: white;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Pizza">
        <h2>Pizza Italiana</h2>
        <p>Disfruta de una auténtica pizza napolitana con mozzarella y albahaca.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Tacos">
        <h2>Tacos Mexicanos</h2>
        <p>Prueba estos deliciosos tacos al pastor con piña y cebolla.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Albóndigas">
        <h2>Albóndigas Caseras</h2>
        <p>Albóndigas en salsa de tomate, perfectas para acompañar con arroz o pasta.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Macarrones">
        <h2>Macarrones con Queso</h2>
        <p>Un plato clásico con una cremosa salsa de queso cheddar.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Espinacas">
        <h2>Espinacas a la Crema</h2>
        <p>Deliciosas espinacas cocinadas con nata y un toque de nuez moscada.</p>
    </div>
    
    <div class="opiniones">
        <h2>Opiniones de los Clientes</h2>
        <textarea placeholder="Escribe tu opinión sobre nuestras recomendaciones..."></textarea><br>
        <button>Enviar Opinión</button>
    </div>
</body>
</html>


