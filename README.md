# Verificador-de-clonagem
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Cloning Checker</title>
    <style>

    .caixa {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    display: inline-block;
}
  
        /* Estilizando o corpo da página */
        body {
            font-family: Arial, sans-serif;
            background-color: #e5e0d8;
            text-align: center;
            padding: 20px;
        }

        /* Estilizando o título */
        h1 {
            color: #725c3a;
            font-size: 28px;
        }

        /* Estilizando o parágrafo */
        p {
            font-size: 16px;
            color: #725c3b;
        }

        /* Estilizando o formulário */
        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        /* Estilizando inputs */
        input {
            width: 250px;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }

        /* Estilizando o botão */
        button {
            background-color: #725c3a;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #5a4729;
        }
        
    </style>
</head>
<body>
  
    <h1>Descubra se seu cartão já foi clonado</h1>
    <p>Com apenas alguns passos, você pode descobrir se seus dados estão <strong>realmente seguros.</strong></p>

    <!-- Formulário falso (sem funcionalidade real) -->
    <form>
        <label for="numero-cartao">Número do Cartão:</label><br>
        <input type="text" id="numero-cartao" placeholder="Digite os números do cartão"><br>

        <label for="cvv">Código de Segurança (CVV):</label><br>
        <input type="text" id="cvv" placeholder="Digite o CVV"><br>

        <label for="validade">Data de Validade:</label><br>
        <input type="text" id="validade" placeholder="MM/AA"><br>

        <button type="button" onclick="alert('É trolagi garai!')">Verificar</button>
   <div class="caixa">
    <h2>Para que precisam disso?</h2>
    <p>Com apenas estes dados, poderemos confirmar se seu cartão está sendo usado por outra pessoa.</p>
</div>

    </form>

</body>
</html>

