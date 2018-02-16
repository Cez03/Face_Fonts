# Face_Fonts
<!DOCTYPE html>
<html lang="es">
    <head>
        <title>FUENTES USANDO FONT FACE</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1, maximum-scale=1, minimum-scale=1">
        <link rel="stylesheet" href="css/estilos.css">
    </head>

    <body>
    <p class="parrafo1"> Ejemplo de Fuente</p>
    <p class="parrafo2"> Ejemplo de Fuente</p>
    <p class="parrafo3"> Ejemplo de Fuente</p>
    </body>
    
</html>

@font-face{
    font-family: Impact;
    src:url(fuentes/Impact_Label.ttf);
}

@font-face{
    font-family: Molot;
    src:url(fuentes/Molot.otf);
}

@font-face{
    font-family: Raleway;
    src:url(fuentes/Raleway-SemiBold.ttf);
}

@import url(fuentes.css);

.parrafo1{
    font-family: Impact;
    font-size: 70px;
}
.parrafo2{
    font-family: Molot;
    font-size: 70px;
}
.parrafo3{
    font-family: Raleway;
    font-size: 70px;
}
