<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quer Comer?</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.jsdelivr.net/npm/fireworks-js/dist/index.min.js"></script>
</head>
<body>
    <div class="container">
        <h1>Quer comer?</h1>
        
        <div class="options">
            <button onclick="responder('sim')">Sim</button>
            <button onclick="responder('nao')">Não</button>
        </div>

        <div id="respostaContainer">
            <p id="resposta" class="resposta"></p>
            <div id="animacao"></div>
            <div id="gato"></div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
