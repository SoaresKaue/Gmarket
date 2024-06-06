# Gmarket
teste de desenvolvimento de site empresarial e landing page Gmarket
<!-- landing page -->
<!DOCTYPE html>
<html lang="pt-BR  ">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/teste de pagina/css/navbar.css">
    <link rel="stylesheet" href="/teste de pagina/css/testepg.css">
    <link rel="icon" href="/teste de pagina/imgs/icone gmarket.png">
    <title>GMarket</title>
</head>

<body>

    <!--Navbar responsivo-->
    <div class="header" id="navbar">
        <div class="logo">
            <img src="/teste de pagina/imgs/icone gmarket.png" alt="logomark" class="logomark">
            <h1 class="logotxt">GMarket</h1>
        </div>
        <div class="hamburger" id="menuBtn" onclick="navbar()">
            <div class="line"></div>
            <div class="line"></div>
            <div class="line"></div>
        </div>
        <nav class="nav-bar">
            <ul>
                <li><a href="" class="active">Home</a></li>
                <li><a href="">features</a></li>
                <li><a href="">Pricing</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Contact</a></li>
            </ul>
        </nav>
    </div>

    <!--banner principal-->
    <div class="main-banner">
        <div class="txt">
            <h1>Bem vindos a GMarket!</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, ipsum, atque nostrum eos
                consectetur placeat obcaecati facilis earum dolor rem itaque ullam odio ipsam voluptatibus dolore
                ducimus veritatis nisi maiores.</p>
        </div>

        <div class="imagem">
            <img class="imgalt" src="/teste de pagina/imgs/icone gmarket.png" alt="logo gmarket">
        </div>
    </div>
</body>
<script src="testepg.js"></script>

</html>
