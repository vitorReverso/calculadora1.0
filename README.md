<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>estudar para a prova</title>
</head>
<body>

    <h1>jorge</h1>


    <script>

      let entrada = prompt("escolha um desses sinais: + - * / **")
      let operadores = ["+", "-", "*", "/", "**"]
      let sinalEscolhido
      let n1 = Number.parseInt(prompt("digite um numero"))
      let n2 = Number.parseInt(prompt("digite outro numero"))
      let resultado

      if(operadores.includes(entrada)) {
          sinalEscolhido = entrada
          switch (sinalEscolhido) {
            case "+":
              resultado = n1 + n2
            break
            case "-":
              resultado = n1 - n21
            break
            case "*":
              resultado = n1 * n2
            break
            case "/":
              resultado = n1 / n2
            break
            case "**":
              resultado = n1 ** n2
              break
          }
          alert(`seu sinal e ${entrada}`)
          alert(`seus numeros e: ${n1}, ${n2}`)
          document.write(`seu resultado e: ${resultado}`)
        }
    </script>
</body>
</html>
