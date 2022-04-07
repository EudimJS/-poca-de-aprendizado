<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula de JavaScript</title>
    <style>
        body {
            background-image: url(https://cupulatrovao.com.br/wp-content/uploads/2020/11/capa-guia-de-episodios-filler-naruto-classico.jpg);
            color: white;
            font: normal 20pt Arial;
        }
        h1 {
            color: rgb(15, 15, 14);
        }
        p {
            color: rgb(8, 9, 10);
        }
    </style>
</head>
<body>
    <h1>Soma de valores, dando o resultado em Real!!</h1>
    <p> 
        <strong>
            <u> 
                <br>Essa imagem do naruto aqui no fundo<br>
            </u>
                <br>
                <br>
                Eu que descobri sozinho como coloca<br>
                E eu coloquei mermo
       
        </strong> 
    </p>
        
    
    <script>
       // window.alert('O que você acha que vai acontecer?')
        //window.confirm('nem imagina?')
       var n1 = Number(window.prompt('Qual o primeiro número?'))
       var n2 = Number(window.prompt('Qual o segundo numero?'))
       var s1 = Number(n1 + n2)
       window.alert(s1.toLocaleString('pt-BR', {style: 'currency', currency:'BRL'})) /*tranforma o resultado em valor em dinheiro, 
                                                                                        lá em BRL vc troca pela moeda do país que quiser*/

    </script>
</body>
</html>
