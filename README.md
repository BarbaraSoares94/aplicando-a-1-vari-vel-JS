<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
body{

    font: normal 20px arial;
}
    
</style>

<body>

    <script>
var nome = window.prompt('Digite o seu nome:')
document.write(` Olá, <strong> ${nome}</strong>, seu nome tem ${nome.length} letras! </br>`) 
document.write(` Seu nome em maiúsculo fica assim: ${nome.toUpperCase()}. </br>`)
document.write(` E em minúsculo fica assim: ${nome.toLowerCase ()}.`)

    </script>
    
</body>
</html>
