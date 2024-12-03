
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
    * {
        box-sizing: border-box;
    }

    body {
        font-family: Arial; 
        padding: 10px;
        background: #ffe333;
    }

    /* Header/Blog Title */
    .header {
        position: relative; /* Necesario para que la imagen se posicione dentro del contenedor */
        padding: 30px; 
        text-align: center; 
        background: white;
        border: 5px solid;
    }

    .header h1 { 
        font-size: 50px;
    }

    /* Primera imagen */
    .header img {
        position: absolute; /* Posicionamiento absoluto dentro del encabezado */
        left: 0;  /* Mueve la imagen al lado izquierdo del encabezado */
        top: 50%;  /* La centra verticalmente */
        transform: translateY(-50%); /* Ajusta la posición vertical de la imagen */
    }

    /* Estilo para el resto del contenido */
    .topnav {
        overflow: hidden; 
        background-color: #333;
    }

    .topnav a {
        float: left;
        display: block; 
        color: #f2f2f2; 
        text-align: center;
        padding: 14px 16px; 
        text-decoration: none;
    }

    .topnav a:hover {
        background-color: #ddd; 
        color: black;
    }

    /* Columnas */
    .leftcolumn {
        float: left; 
        width: 75%;
        
    }

    .rightcolumn {
        float: left; 
        width: 25%;
        background-color: #f1f1f1; 
        padding-left: 20px;
        border: 5px solid;
    }
    
/* Fake image */ 
	.fakeimg {
		background-color: #aaa; 
		width: 100%; 
		padding: 20px;
	}

       /* Add a card effect for articles */ 
	.card {
		background-color: white;
		padding: 10px; 
		margin-top: 10px;
        }

        /* Clear floats after the columns */ 
	.row::after{
		content: ""; 
		display: table; 
		clear: both;
	}

    .footer {
        padding: 20px; 
        text-align: center; 
        background: #ddd; 
        margin-top: 20px;
        border: 5px solid;
    }

    /* Responsive layout */
    @media screen and (max-width: 800px) {
        .leftcolumn, .rightcolumn {
            width: 100%;
            padding: 0;
        }
    }

    @media screen and (max-width: 800px) {
        .topnav a {
            float: none; 
            width: 100%;
        }
    }

</style>
</head>
<body>

<div class="header">
    <h1>Frutería "El Plátano Riendo"</h1>
    <img src="platano.png" style="height:250px;">
    <p>Catálogo en línea con lista de frutas y verduras frescas, precios diarios, ofertas destacadas y recetas saludables.</p>
</div>

<div class="topnav">
     <a href="file:///C:/xampp/htdocs/DW/ProyectoFinal/imagen.html">Inicio</a> 
    <a href="https://marcusfilidor.github.io/frutas/">Frutas</a> 
    <a href="https://marcusfilidor.github.io/verduras/">Verduras</a>
    <a href="https://marcusfilidor.github.io/ofertas/">Ofertas</a>
    <a href="https://marcusfilidor.github.io/recetas/">Recetas</a>
    <a href="https://marcusfilidor.github.io/contacto/" style="float:right">Contacto</a>
</div>

<div class="row">
    <div class="leftcolumn">
        <div class="card">
            <h2>Frutas Frescas</h2>
            <h5>Precios diarios, Diciembre 2024</h5>
            <img src="frutas1.jpg" style="height:350px;">
            <p>En nuestra frutería, encontrarás una amplia selección de frutas frescas a los mejores precios del mercado.</p>
            <ul>
                <li>Manzanas - $1.50 por kg</li>
                <li>Plátanos - $0.80 por kg</li>
                <li>Fresas - $2.00 por caja</li>
                <li>Ciruela - $2.00 por caja</li>
                <li>Durazno - </li>
                <li>Granada roja - </li>
                <li>Limón - </li>
                <li>Mango - </li>
                <li>Melon - </li>
                <li>Piña - </li>
                <li>Sandia - </li>
                <li>Uva - </li>

            </ul>
        </div> 

        <div class="card"> 
            <h2>Verduras Frescas</h2>
            <h5>Precios diarios, Diciembre 2024</h5>
            <img src="verduras.jpg" style="height:315px;"> 
            <p>Ofrecemos una gran variedad de verduras frescas, ideales para tus comidas saludables.</p>
            <ul>
                <li>Lechuga - $1.00 por unidad</li>
                <li>Tomates - $1.20 por kg</li>
                <li>Zanahorias - $0.90 por kg</li>
            </ul>
        </div> 
    </div>

    <div class="rightcolumn">
        <div class="card">
            <h2>Sobre Nosotros</h2>
            <img src="tienda.jpg" style="height:200px;">
            <p>En "El Plátano Riendo" nos dedicamos a ofrecer productos frescos y de calidad para que tu alimentación sea lo más saludable posible.</p> 
        </div> 

        <div class="card"> 
            <h3>Ofertas Destacadas</h3> 
            <img src="promo1.jpeg" style="height=10px;">
            <img src="promo2.jpeg" style="height=10px;">
        </div>
        <div class="card">
            <h3>Recetas Saludables</h3>
            <p>Descubre nuestras recetas fáciles y nutritivas para aprovechar al máximo las frutas y verduras frescas.</p>
	    <a href="https://cookpad.com/mx/recetas/10837615-caldo-de-res-sencillo" target="_blank"> CALDO DE RES (SENCILLO)</a> <br> <br>
            <a href="https://www.recetasnestle.com.co/recetas/ensalada-de-fruta-con-queso" target="_blank"> ENSALADA DE FRUTAS</a>
            <img src="receta1.jpg" style="height=10px;">   
        </div>
    </div>
</div>

<div class="footer"> 
    <h2>Frutería "El Plátano Riendo"</h2>
    <p>&copy; 2024 Todos los derechos reservados</p>
</div>

</body> 
</html>
