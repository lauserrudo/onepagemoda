<!DOCTYPE html>
<html lang="es"> 
<head>
     <meta charset="UTF-8">
     <meta http-equiv="X-UA-Compatibel" content="IE=edge">
     <meta name="viewport" content="width-device-width,  initial-scale=1.0">
     <title>Rosé Store</title> 
     <link rel="shortcut icon" href="img/logo-laura3.png" type="image/x-icon">
     <link rel="stylesheet" href="./estilosscss.css">
</head>
<body bgcolor="F9DBEF" text="000000">

    <header>
        <nav>
            <a href="#">Inicio</a>
            <a href="#">Historia de Rosé</a> 
            <a href="#">Tendencia del 2022</a>   
            <a href="#">Damas</a> 
            <a href="#">Contactanos</a>  

        </nav>
         <section class="textos-header">
             <h1>En Rosé Store te acompañamos en tus momentos especiales</h1>

         </section>
    </header>
<main>
<section class="contenedor historia de rosé">
    <h2 class="titulo">Historia de Rosé</h2>
    <div class="contenedor-historia-de-rosé">
        <img src="./compras-rose.jpeg" width="600" height="350" alt="" class="imagen-historia-de-rosé">
        <div class="contenido-texto">
            <h3>La importancia del producto</h3>
            <p> En Rosé Store la idea siempre ha sido tener un producto con buen diseño y un precio muy accesible: “La moda no es riqueza sino belleza”, repetimos como mantra.  </p>
            <h3>Apostamos por una mujer real y por la diversidad</h3>
            <p> Quizás gran parte de nuestro éxito es que nuestra ropa es fiel a la filosofía de crear y vender moda para una mujer real que evidentemente presenta diversidad de tallas.  </p>
        </div>

    </div>

</section>
<section class="tendencia-del-2022">
    <div class="contenedor">
        <h2 class="titulo">Tendencias del 2022</h2>
        <div class="galeria-tendencia">
          <div class="imagen-tendencia">
              <img src="./tende-2022-1.jpg " width="400" height="550" alt="">

          </div>  
        </div>
        <div class="galeria-tendencia">
            <div class="imagen-tendencia">
                <img src="./tende-2022-2.jpg" width="400" height="550" alt="">
            </div>
        </div>
        <div class="galeria-tendencia">
            <div class="imagen-tendencia">
                <img src="./tende-2022-3.jpg" width="400" height="550" alt="">
            </div>
        </div>
        <div class="galeria-tendencia">
            <div class="imagen-tendencia">
                <img src="./tende-2022-4.jpg" width="400" height="550" alt="">
            </div>
        </div>
        <div class="galeria-tendencia">
            <div class="imagen-tendencia">
                <img src="./tende-2022-5.jpg" width="400" height="550" alt="">
            </div>
        </div>
        <div class="galeria-tendencia">
            <div class="imagen-tendencia">
                <img src="./tende-2022-6.jpg" width="400" height="550" alt="">
            </div>
        </div>
    </div>
</section>
<section>
    <div class="secciond-contenedor">
        <h2 class="titulo">Damas</h2> 
        <ul>
            <li><img src="./sheinrose.webp" width="200" height="250" alt="" class="img-slider"></li>
            <li><img src="./DAMA-2.jpg" width="200" height="250" alt="" class="img-slider"></li>
            <li><img src="./roseshein.webp" width="200" height="250" alt="" class="img-slider"></li>
            <li><img src="./DAMA-4.jpeg" width="200" height="250" alt="" class="img-slider"></li>
            <li><img src="./verdemujer.webp" width="200" height="250" alt="" class="img-slider"></li> 
            <li><img src="./negromujer.webp" width="200" height="250" alt="" class="img-slider"></li>                                                                   
        
        </ul> 

    </div>
</section>
<section id="contacto">
    <h1>Contactanos</h1>
    
    <form>
          
         <label for="nombre">Nombre:</label>
         <input type="text" id="nombre" placeholder="Ingrese su nombre">

         <label for="correo">Correo:</label>
         <input type="text" id="nombre" placeholder="Ingrese su correo electronico">

         <label for="mensaje">Mensaje:</label>
         <textarea id="mensaje" placeholder="Deje su mensaje aquí"></textarea>

         <input type="submit" name="" value="Enviar">

    </form>

</section>
<footer>
    <div class="contenedor-footer">
        <div class="content-foo"></div>
        <h2 class="Titulo-final">&copy; ROSÉ STORE 2022 | Laura Serrudo </h2>
    </div>
</footer>
</main>
<script>
        $(document).ready(function() {
            $('.slider1').bxSlider({
                mode: 'fade',
            });
            $('.slider2').bxSlider({
                mode: 'fade',
            });
            $('.slider3').bxSlider({
                mode: 'fade',
            });
        });
    </script>

</body>
</html>
