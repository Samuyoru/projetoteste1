<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sitedevendas2</title>
</head>
<link rel="stylesheet" href="inicio.css">
<body>
    <nav>
        <h1>Vendason.com</h1>
            <a href=inicio.html>Inicio</a></li>
            <a href="pesquisa.html">Pesquisa</a>
            <a href="ajuda.html">Ajuda</a>
</nav>
<img id="tenisnike" src="https://imgnike-a.akamaihd.net/1920x1920/027322ID.jpg" alt="Imagem não encontrada" width="300px" height="300px">
<img id="alexa" src="https://fastshopbr.vtexassets.com/arquivos/ids/496762/1_A6ECHODOT5PTO_PRD_1500_2.jpg?v=638681755622000000" alt="Imagem não encontrada" width="300px" height="300px">
<h2 id="nome1" >Tênis Nike Air Max Excee Masculino</h2>
<h3 id="preço1" >77,86US$</h3>
<h2 id="nome2" >Echo Dot (5ª geração) Smart Speaker com Alexa Amazon Preto</h2>
<h3 id="preço2" >75,24US$</h3>
    <script src="inicio.js"></script>
</body>
</html>

nav{
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
    text-decoration: none;
}
a{
    color: white;
    text-decoration: none;
    font-size: 20px;
}
h1{
    text-align: center;
        font-size: 50px;
}
#tenisnike{
    border: #ffffff00;
    border: 1px solid;
    border-radius: 10px;
    transition: 1s;
    position: absolute;
    top: 25%;
    left: 2%;
    z-index: 2;
    cursor: pointer;
}
.produto1{
   width: 550px;
    height: 490px;
    transition: 0.5s;
    transition: 1s;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(119.5%, 05%);
    z-index: 2;
}
#nome1{
    font-size: 20px;
    position: absolute;
    top: 55%;
    left: 1.5%;
    z-index: -1;
}
#preço1{
    font-size: 30px;
    position: absolute;
    top: 57%;
    left: 6%;
    transition: 10ms;
    z-index: -1;
}
#alexa{
    border: #ffffff00;
    border: 1px solid;
    border-radius: 10px;
    transition: 1s;
    position: absolute;
    top: 25%;
    left: 30%;
    cursor: pointer;
    z-index: 1;
}
.produto2{
    width: 540px;
    height: 490px;
    transition: 0.5s;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(22.5%, 4.9%);
    z-index: 2;
}
#nome2{
    font-size: 20px;
    position: absolute;
    top: 55%;
    left: 25%;
    z-index: -1;
}
#preço2{
    font-size: 30px;
    position: absolute;
    top: 57%;
    left: 34.7%;
    transition: 10ms;
    z-index: -1;
    const produto1 = document.getElementById('tenisnike');
produto1.addEventListener('click', () => {
    produto1.classList.toggle('produto1');
}); 

const produto2 = document.getElementById('alexa');
produto2.addEventListener('click', () => {
  produto2.classList.toggle('produto2');
}); 
