# Menjabo
Pàgina dedicada a recomenar menjar de qualitat
<!DOCTYPE html>
<html lang="ca">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recomanacions de Menjar</title>
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
        .opinions {
            width: 100%;
            margin-top: 30px;
            text-align: center;
        }
        .opinions h2 {
            font-size: 24px;
        }
        .opinions textarea {
            width: 80%;
            height: 100px;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .opinions button {
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
        <p>Gaudeix d'una autèntica pizza napolitana amb mozzarella i alfàbrega.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Tacos">
        <h2>Tacs Mexicans</h2>
        <p>Prova aquests deliciosos tacs al pastor amb pinya i ceba.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Mandonguilles">
        <h2>Mandonguilles Casolanes</h2>
        <p>Mandonguilles amb salsa de tomàquet, perfectes per acompanyar amb arròs o pasta.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Macarrons">
        <h2>Macarrons amb Formatge</h2>
        <p>Un plat clàssic amb una cremosa salsa de formatge cheddar.</p>
    </div>
    
    <div class="panel">
        <img src="https://via.placeholder.com/300" alt="Espinacs">
        <h2>Espinacs a la Crema</h2>
        <p>Deliciosos espinacs cuinats amb nata i un toc de nou moscada.</p>
    </div>
    
    <div class="opinions">
        <h2>Opinions dels Clients</h2>
        <textarea placeholder="Escriu la teva opinió sobre les nostres recomanacions..."></textarea><br>
        <button>Enviar Opinió</button>
    </div>
</body>
</html>

