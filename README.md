# index.html<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Conversor de Moedas</title>
</head>
<body>
    <script>
        let valor = prompt("Digite o valor em reais (R$):");
        valor = parseFloat(valor);
        let dolar = valor / 5.30; //[cite: 1]
        
        document.write("<h1>Resultado da Conversão</h1>");
        document.write("O valor em dólares é: US$ " + dolar.toFixed(2)); //[cite: 1]
    </script>
</body>
</html>
