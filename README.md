<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tentando criar pagina2</title>
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
        input{
            width: 60px;
        }
      
    </style>
</head>
<body>
   
    <h1>Soma de valores</h1>
    <input type="number" name="nn1" id="nn1">+
    <input type="number" name="nn2" id="nn2">
    <input type="button" value="Somar" onclick="somar()">
    <div id="res"></div>
    <p></p>
    <iframe width="500" height="400" src="https://www.youtube.com/embed/RFbt_VfaSdk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <script>
      function somar()
      {
          var n1 = document.querySelector('input#nn1')
          var n2 = document.querySelector('input#nn2')
          var s1 = Number(n1.value)
          var s2 = Number(n2.value)
          var som = (s1+s2)
          var x = document.getElementById('res')
          x.innerHTML = `O resultado da soma entre ${s1} e ${s2} é ${som}`
      }
      function page2()
      {

      }
    </script>
</body>
</html>
