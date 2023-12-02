# aula_javascript
esse repositórios é para pratica 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saldo</title>
    <script>
        function verificarsaldo() {
            var saldo = + prompt("Digite seu saldo: ");
            if (saldo >= 5000) {
                alert("seu saldo é suficiente");
                alert("maldivas, estados unidos , barramas")
                alert("praias maldivas , santa monica , praias barramas")
            } else {
                if (saldo < 5000)
                alert ("seu saldo nao é o suficiente");
                var mes = 0;
                var poupanca = saldo ;
                while (poupanca < 5000 ) {
                    poupanca = poupanca + saldo;
                    mes++;
                }
               alert("voce vai precisar de: " + mes);
            }

        }

    </script>
</head>
<body>
    <button onclick="verificarsaldo()">consultar saldo</button>
</body>
</html>
