<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plantilla de Caso de Uso</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .container {
            width: 80%;
            margin: auto;
            border: 1px solid #000;
            padding: 20px;
        }
        .input-group {
            margin-bottom: 10px;
        }
        label {
            font-weight: bold;
        }
        button {
            margin-top: 10px;
            padding: 10px;
            background-color: blue;
            color: white;
            border: none;
            cursor: pointer;
        }
        @media print {
            button {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="container" id="casoUso">
        <h2>Plantilla de Caso de Uso</h2>
        <div class="input-group">
            <label>Nombre del Caso de Uso:</label>
            <input type="text" id="nombreCaso" placeholder="Ingrese el nombre">
        </div>
        <div class="input-group">
            <label>Actor(es):</label>
            <input type="text" id="actores" placeholder="Ingrese los actores">
        </div>
        <div class="input-group">
            <label>Descripción:</label>
            <textarea id="descripcion" placeholder="Describa el caso de uso"></textarea>
        </div>
        <div class="input-group">
            <label>Flujo Principal:</label>
            <textarea id="flujoPrincipal" placeholder="Describa el flujo principal"></textarea>
        </div>
        <div class="input-group">
            <label>Flujo Alternativo:</label>
            <textarea id="flujoAlternativo" placeholder="Describa el flujo alternativo"></textarea>
        </div>
    </div>
    <button onclick="window.print()">Imprimir en PDF</button>
</body>
</html>

