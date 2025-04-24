# RID-217766_desafio1
<!--CODIGO HTML-->
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>architecture_landpage</title>
    <link rel="stylesheet" href="link rel="preconnect href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!--titulo-->
    <div id="titulo">
    <h1 class="texto-titulo" id="title">Tradição em projetos de arquitetura</h1>
    <p class="texto-titulo" id="title-parag">Arquitetura residencial e comercial. </p>
</div>
<!--numbersinfo-->
<div id="numbers-info">
    <h1 class="number">850</h1>
    <p>empreendimentos construídos</p>
    <h1 class="number">40</h1>
    <p>anos de mercado e experiência</p>
    <h1 class="number">2,000,000 m²</h1>
    <p>em projetos construídos</p>
</div>
<!--info-->
<div id="info">
    <h1 id="info-title">Arquitetos com História e Experiência.</h1>
    <p id="info-parag">Nós realizamos desde 2002 projetos e gerenciamento de obras.<br>
    Com mais de 800 projetos e 2.000.000 de m² construídos, tendo<br> 
    como principal proposta transformar em realidade os sonhos de <br> seus clientes, criando projetos personalizados, unindo a tradição <br>
    e a modernidade em nossos projetos.</p>
    <img src="imagem/foto.svg" alt="error" id="img">
</div>
<!--form-->
<div id="form">
    <form action=https://api.sheetmonkey.io/form/jezoBDgedwxSWNDGELUyV6 method="post"> 
    <h1 id="form-title">Conheça mais sobre nossos serviços</h1>
    <input type="text" id="name" placeholder="nome" name="Name" required /><br>
    <input type="text" id="email" placeholder="email" name="Email" required /> <br>
    <input type="hidden" name="Created" value="x-sheetmonkey-current-date-time" /> 
    <button type="submit" id="submit">Fale Conosco</button>
</div>
</form>

</body>
</html>
<!--CODIGO CSS-->
*{
    margin: 0px;
    font-family: 'inter'; 
    padding: 0px;
}
#titulo{
    background-color: #303030;
    color: white; 
    padding-bottom: 50px;
    padding-top: 50px;
}
.texto-titulo{
    margin-left: 62px;
    
}
#title{
    margin-top: 160px;
    margin-left: 70px;
    margin-bottom: 25px;
    font-size: 45px;
    font-weight: semi-bold;
}
#title-parag{
    margin-bottom: 150px
}
#numbers-info{
    text-align: center;
    grid-column: auto;
    columns: 3;
    background-color: #F9F9F9;
    padding-top: 80px;
    padding-bottom: 50px;
}
#info{
    grid-column: auto;
    columns: 2;
    padding-bottom: 50px;
    padding-top: 50px;
}
#img{
    margin-left: 180px;
}
#info-title{
    margin-top: 220px;
    margin-left: 200px;
    font-size: 40px;
    font-weight: semi-bold;
    text-align: left;
    
}
#info-parag{
    margin-top: 50px;
    margin-left: 200px;
    font-size: 20px;
}
#form{
    background-color: #303030;
    padding-bottom: 250px;
    text-align: center;
}
#form-title{
    color: #FFFFFF;
    padding-top: 150px;
    margin-bottom: 50px;
    font-size: 40px;
}
#name{
    margin-top: 50px;
    width: 450px;
    margin: 15px;
    height: 65px;
    border: none;
    border-radius: 10px;
    background-color: #ffffff;
    
}
#email{
    margin-top: 50px;
    width: 450px;
    height: 65px;
    border-radius: 10px;
    border: none;
    background-color: #ffffff;
}
#submit{
    margin-top: 50px;
    width: 250px;
    height: 60px;
    border-radius: 10px;
    border: none;
    background-color: #C07212;
    color: #ffffff;
    font-size: 30px;
    font-weight: bolder;
}
input{
    padding-left: 10px;
}
button{
    cursor: pointer;
}
button:hover{
    transition-duration: 500ms;
    transform: translateY(-5px);
    box-shadow: 0px 15px 25px #834d0c;
