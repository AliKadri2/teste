<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercicio 3</title>
</head>
<body>
<h1>Exercicio 3</h1>
<hr>
    Vamos ver uma tabuada? <br>
    Inserir número da tabuada: 0 a 9 <input type="text " id="input_tabuada">
    <button onclick="Tabuada()">Ver Tabuada</button> <br>

    <div id="div_tabuada"></div>
</body>
</html>

<script>
    function Tabuada(){
        var NumeroTabuada = Number(input_tabuada.value);

        div_tabuada.innerHTML = `
        <br>tabuada do ${NumeroTabuada}:<br>
        ${NumeroTabuada} x 1 = ${NumeroTabuada * 1} <br>
        ${NumeroTabuada} x 2 = ${NumeroTabuada * 2} <br>
        ${NumeroTabuada} x 3 = ${NumeroTabuada * 3} <br>
        ${NumeroTabuada} x 4 = ${NumeroTabuada * 4} <br>
        ${NumeroTabuada} x 5 = ${NumeroTabuada * 5} <br>
        ${NumeroTabuada} x 6 = ${NumeroTabuada * 6} <br>
        ${NumeroTabuada} x 7 = ${NumeroTabuada * 7} <br>
        ${NumeroTabuada} x 8 = ${NumeroTabuada * 8} <br>
        ${NumeroTabuada} x 9 = ${NumeroTabuada * 9} <br>

        ` 
    
    }

</script>
