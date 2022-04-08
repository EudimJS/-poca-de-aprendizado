<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maior valor</title>
    <style>@import url('https://fonts.googleapis.com/css?family=Pacifico&display=swap');

        body { font: 12pt Arial; background-image: url(https://sm.ign.com/ign_br/screenshot/default/naruto-shippuden_f134.png);}
        h1, h2, h3 { font-family: 'Pacifico', cursive; font-weight: normal;}
        button { font-size: 12pt; padding: 30px; }</style>
</head>
<body>
    <h1>Maior valor</h1>
    <button onclick="maior()">Clique para começar</button>
    <div id='saida'>
        <br>
        O resultado vai aparecer aqui...
    </div>

    <script>
       function maior(){
            let n1 = Number(window.prompt('Digite um número: '))
            let n2 = Number(window.prompt('Digite outro número: '))

            let res = document.getElementById('saida')
            if (n1 > n2) {
                res.innerHTML = `<p>Analisando os valores <mark>${n1}</mark> e <mark>${n2}</mark>, o maior valor é <strong>${n1}</strong></p>`
            } else if (n1 < n2) {
                res.innerHTML = `<p>Analisando os valores <mark>${n1}</mark> e <mark>${n2}</mark>, o maior valor é <strong>${n2}</strong></p>`
            } else {
                res.innerHTML = `<p>Analisando os valores <mark>${n1}</mark> e <mark>${n2}</mark>, ambos são <strong>IGUAIS</strong></p>`
            }}
    </script>
</body>
</html>
