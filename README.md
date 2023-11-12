<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap" rel="stylesheet">
    <script src="scripts.js"></script>
    <title>Dev Previsão</title>
</head>

<body>

    <div class="caixa-maior">

        <input class="input-cidade" placeholder="Digite o nome da cidade">
        <button onclick="cliqueiNoBotao()">
            <img class="lupa" src="https://www.svgrepo.com/show/488200/find.svg">
        </button>

        <div class="caixa-media">
            <h2 class="cidade">Tempo em Rio de Janeiro</h2>
            <p class="temp">28°C</p>

            <div class="caixa-menor">
                <img class="icone" src="https://openweathermap.org/img/wn/04n.png">
                <p class="descricao">Nuvens Dispersas</p>
            </div>

            <p class="umidade">Umidade: 70%</p>
        </div>

    </div>

</body>

</html>
