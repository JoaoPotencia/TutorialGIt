# Aula-Monte-Fuji
Código de Exemplo

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> IFPR VIAGENS </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!--Comentario de códigos HTML-->
    <header>
        <nav>
         <p1>PotenciasViagens</p1>
         <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#pacotes">Pacotes</a></li>
            <li><a href="#serviços">Serviços</a></li>
            <li><a href="#contato">Contato</a></li>
         </ul>
        </nav>
        <div id="home" class="header-content">
            <h1>Monte Fuji</h1>
            <!--<h2>Monte Fuji</h2>
            <h3>Monte Arabia</h3>
            <h6>Samba Canção</h6>-->
            <p>Conheça o monte fuji, veja as belezas naturais desse lugar!</p>
            <button>Saiba mais</button>
        </div>

    </header>
</body>
</html>

--------------------------------------------------------------------------------------------------------------------------------------------
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

* {
    box-sizing: border-box;
}

/*Comentário Css*/

body {
    margin: 0;
    font-family: 'Montserrat', sans-serif;
    background-color: #c87ce6;
}

ul {

    list-style: none;
    font-weight: bold;
}

a{
    text-decoration: none ;
    color: #ffffff;

}

h1  {
    color: #461be0;
    font-size: 3rem;
}

header{
    background: url('monte-fuji.jpg');
    height: calc(120vh - 150px);
}

button{
    padding: 10px 15px;
    border-radius: 8px;
    font-weight: bold;
    background-color: rgb(110, 180, 226);
    color: white;
    font-family: 'Montserrat',sans-serif
    ;
}

p1{
    font-size: 4rem;
    color: #063847;
    font-weight: bold ;
}

header nav {
    display: flex;
    justify-content: space-between;
    margin: auto 90px;
}

