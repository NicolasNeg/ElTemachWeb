# ElTemachWeb

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../css/index.css">
    <script src="../js/index.js"></script>
    <title>War Mode</title>
</head>
<body>
    <!---Navegacion menu--->
    <div class="container">
        <div class="navbar">
            <h1 class="logo">El Temach</h1>
            <marquee id="warmode" loop="infinite" truespeed scrolldelay="50" scrollamount="10"> <a href="https://eltemach.net/" id="warmode-text">MODO GUERRA MI COMPA</a></marquee>
            <ul>
                <li><a href="../html/acc.html">Account</a></li>
            </ul>
        </div>
        <h1 id="saludo">MI COMPA</h1>
        <section class="contenido">
            <p>Bienvenido a la pagina no-oficial del temach</p>
            <div class="button">
                <br><br><br><br><br><br><br><br>
                <button class="raise" onclick="Redirect()">Vamos</button>
            </div>
            <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br> <!---30 -->
            <p id="copy">Copyright © 2023 - Negrura coding</p>
      </section>
    </div>
        <script>
            function Redirect(){
                window.location.href = "C:/xampp/htdocs/Web/html/acc.html";
            }
            
        </script>
</body>
</html>
