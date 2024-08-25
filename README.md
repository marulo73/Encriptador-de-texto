<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="http//fonts.googleapis.com/css2?family=Inter:wght@200;300;400&display=swap" rel="stylesheet">
    <title>Encriptador de texto</title>
</head>
<body>
    <header>
        <img class="logo" src="imagenes/Logo.png" alt="logo">
    </header>
    <main>
        <section class="seccion1">
            <div class="contenedorcajatexto">
                <textarea placeholder="Ingrese el texto aqui" class="cajatexto"></textarea>

            </div>
            <div class="alerta">
                <img src="imagenes/Logo.png" alt="alerta">
                <p>Solo letras minusculas y sin acentos</p>

            </div>
            <div class="contenedor-botones">
                <input type="button" class="btn-encriptar" value="Encriptar">
                <input type="button" class="btn-desencriptar" value="Desencriptar">
            </div>
        </section>
        <section class="seccion2">
            <div class="contenedormuñeco">
                <img src="imagenes/Muñeco.png" alt="muñeco">

            </div>
            <div class="contenedor-parrafo">
                <h3>Ningun mensaje fue <br> encontrado</h3>
                <p>Ingresa el texto que desees encriptar o <br> desencriptar.</p>

            </div> 
            <div class="contenedor-copiar">
                <input type="button" class="btn-copiar" value="Copiar">

            </div>
            <div class="contenedor-resultado">
                <p class="texto-resultado"></p>
            </div>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
