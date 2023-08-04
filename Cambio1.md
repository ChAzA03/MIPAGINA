<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GamesNet</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f0f0;
    }

    header {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px;
      position: relative;
    }

    h1 {
      margin: 0;
    }

    .search-box {
      position: absolute;
      top: 15px;
      right: 240px;
      display: flex;
      align-items: center;
      background-color: #fff;
      border-radius: 20px;
      padding: 5px 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }

    .search-box input[type="text"] {
      border: none;
      outline: none;
      background: none;
      margin-left: 5px;
    }

    /* Estilos para los elementos en el header */
    .header-icons {
      position: absolute;
      top: 18px;
      right: 15px;
      display: flex;
      align-items: center;
    }

    .header-icons a {
      color: #fff;
      text-decoration: none;
      margin-left: 10px;
    }

    /* Estilos para el contenido */
    .container {
      max-width: 1200px;
      margin: 20px auto;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }

    .game {
      border: 1px solid #ddd;
      border-radius: 5px;
      padding: 10px;
      margin: 10px;
      background-color: #fff;
    }

    .game img {
      max-width: 100%;
      height: auto;
    }

    .game-title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .description {
      font-size: 14px;
      color: #666;
      margin-top: 10px;
    }

    .game-price {
      font-size: 16px;
      color: #007bff;
      margin-top: 5px;
    }

    .buy-button {
      display: inline-block;
      padding: 5px 10px;
      background-color: #007bff;
      color: #fff;
      text-decoration: none;
      border-radius: 3px;
      margin-top: 10px;
    }

    .buy-button:hover {
      background-color: #0056b3;
    }

    /* Estilos para el pie de página */
    footer {
      background-color: #333;
      color: #fff;
      text-align: right;
      padding: 10px;
      position: fixed;
      bottom: 0;
      right: 0;
      width: 100%;
    }

    footer a {
      color: #fff;
      text-decoration: none;
      margin-left: 15px;
    }

    .instagram-icon {
      color: #e1306c;
    }

    .contact-icon {
      color: #28a745;
    }
    
  </style>
</head>
<body>
  <header>
    <h1>GamesNet</h1>
    <div class="search-box">
      <i class="fas fa-search"></i>
      <input type="text" placeholder="Buscar juegos...">
    </div>
    <div class="header-icons">  
      <a href="https://example.com/login">Iniciar sesión</a>
      <a href="https://example.com/register">Registrarse</a>
      <a href="https://example.com/cart"><i class="fas fa-shopping-cart"></i></a>
    </div>
  </header>

  <div class="container">
    <div class="game">
      <a href="https://example.com/game1">
      <img src="https://image.api.playstation.com/vulcan/img/rnd/202010/2618/w48z6bzefZPrRcJHc7L8SO66.png" width="250"  
      alt="The Last Of Us Part II">
      </a>
      <div class="game-title">The Last Of Us Part II</div>
      <div class="description">The Last of Us: Parte II es un videojuego de género Drama, Survival Horror y Acción-Aventura en tercera persona desarrollado por Naughty Dog y publicado por Sony Interactive Entertainment. Esta segunda parte fue, al igual que su predecesor, escrito y dirigido por Neil Druckmann, esta vez acompañado por su coescritora Halley Gross. Fue lanzado el 19 de junio de 2020.</div>
      <div class="game-price">$19.99</div>
      <span class="rating">
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star-half-alt"></i> <!-- Media estrella -->
      </span>
      <a href="https://example.com/cart" class="buy-button">Comprar</a>
    </div>
    
    <div class="game">
      <a href="https://example.com/game2">
      <img src="https://image.api.playstation.com/cdn/UP1004/CUSA03041_00/Hpl5MtwQgOVF9vJqlfui6SDB5Jl4oBSq.png" width="250"  
      alt="Juego 2">
      </a>
      <div class="game-title">Red Dead Redemption 2</div>
      <div class="description">Red Dead Redemption 2 es un videojuego de acción-aventura western basado en el drama. Un juego bastante conocido también por sus cantidades de detalles realistas en un mundo abierto y en perspectiva de primera y tercera persona, ​ con componentes para un jugador y multijugador.​ Fue desarrollado por Rockstar Games.</div>
      <div class="game-price">$24.99</div>
      <span class="rating">
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star-half-alt"></i> <!-- Media estrella -->
      </span>
      <a href="https://example.com/cart" class="buy-button">Comprar</a>
    </div>

    <div class="game">
      <a href="https://example.com/game3">  
      <img src="https://image.api.playstation.com/vulcan/ap/rnd/202207/1210/4xJ8XB3bi888QTLZYdl7Oi0s.png" width="250"  
      alt="Juego 3">
      </a>
      <div class="game-title">God of War: Ragnarök</div>
      <div class="description">God of War Ragnarök es un videojuego de acción y aventuras desarrollado por Santa Monica Studio y publicado por Sony Interactive Entertainment. Se lanzó en todo el mundo el 9 de noviembre de 2022 para PlayStation 4 y PlayStation 5, lo que marca el primer lanzamiento entre generaciones de la serie.</div>
      <div class="game-price">$29.99</div>
      <span class="rating">
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
      </span>
      <a href="https://example.com/cart" class="buy-button">Comprar</a>
    </div>
    
    <div class="game">
      <a href="https://example.com/game3">   
      <img src="https://depor.com/resizer/ryjpVYp7gvye_0LgXZYRO_yL-B0=/1200x1200/smart/filters:format(jpeg):quality(75)/cloudfront-us-east-1.images.arcpublishing.com/elcomercio/MBJ5QO7YPRHIXI26D3OQM6KUZQ.JPG" width="250"  
      alt="Juego 3">
      </a>
      <div class="game-title">Fifa 23</div>
      <div class="description">FIFA 23 es un videojuego de simulación de fútbol publicado por Electronic Arts. Es la trigésima entrega de la serie FIFA desarrollada por EA Sports, y la última entrega bajo el estandarte de FIFA.</div>
      <div class="game-price">$39.99</div>
      <span class="rating">
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="far fa-star"></i> <!-- Estrella vacía -->
      </span>
      <a href="https://example.com/cart" class="buy-button">Comprar</a>
    </div>

    <!-- Agregar más juegos aquí -->
  </div>

  <footer>
    <center>Derechos de autor © 2023 - GamesNet</center> 
    <a href="https://instagram.com" target="_blank" class="instagram-icon"><i class="fab fa-instagram"></i> Instagram</a>
    <a href="mailto:contacto@example.com" class="contact-icon"><i class="fas fa-envelope"></i> Contacto</a>
  </footer>

</body>
</html>
