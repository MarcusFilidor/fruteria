<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title> El platano riendo </title>

<style>
    * {
        box-sizing: border-box;
    }

    body {
        font-family: Arial; 
        padding: 5px;
        background: green;
    }

    /* Header/Blog Title */
    .header {
        position: relative; /* Necesario para que la imagen se posicione dentro del contenedor */
        padding: 30px; 
        text-align: center; 
        background: white;
        border: 2px solid;
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
        border: 2px solid;
        
    }

    .rightcolumn {
        float: left; 
        width: 25%;
        background-color: green; 
        padding-left: 2px;
        border: 2px solid;
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
            width: 75%;
            padding: 0;
            border: 2px solid;

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
    <img src="platano.png" style="height:100px;">
    <p>Catálogo en línea con lista de frutas y verduras frescas, precios diarios, ofertas destacadas y recetas saludables.</p>
</div>

<div class="topnav">
    <a href="https://marcusfilidor.github.io/fruteria/">Inicio</a> 
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
            <img src="frutas1.jpg" style="height:350px;">
            <h5>Precios diarios, Diciembre 2024</h5>
            <p>En nuestra frutería, encontrarás una amplia selección de frutas frescas a los mejores precios del mercado.</p>
            <ul>
                <li>Manzanas  </li> <br>
                <li>Plátanos  </li> <br>
                <li>Fresas  </li> <br>
                <li>Ciruela  </li> <br>
                <li>Durazno  </li> <br>
                <li>Granada roja </li> <br>
                <li>Limón </li> <br>
                <li>Mango </li> <br>
                <li>Melon </li> <br>
                <li>Piña </li> <br>
                <li>Sandia  </li> <br>
                <li>Uva </li> <br>

            </ul>
        </div> 

        <div class="card"> 
            <h2>Verduras Frescas</h2>
            <img src="verduras.jpg" style="height:315px;">
            <h5>Precios diarios, Diciembre 2024</h5> 
            <p>Ofrecemos una gran variedad de verduras frescas, ideales para tus comidas saludables.</p>
            <ul>
                <li>Lechuga </li> <br>
                <li>Tomates </li> <br>
                <li>Zanahorias </li> <br>
                <li>Acelga </li> <br>
                <li>Ajo </li> <br>
                <li>Apio </li> <br>
                <li>Brócoli </li> <br>
                <li>Cebolla </li> <br>
                <li>Coliflor </li> <br>
                <li>Espinaca </li> <br>
                <li>Pepino </li> <br>
                
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
            <ul class="offers-list">
                <li>Manzana: 10% de descuento por compra mayor a 5 kg.</li> <br> <br>
                <li>Plátano: 2x1 en la compra de 3 kg.</li> <br> <br>
                <li>Tomate: 15% de descuento en compras mayores a $20.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Recetas Saludables</h3>
            <p>Descubre nuestras recetas fáciles y nutritivas para aprovechar al máximo las frutas y verduras frescas.</p>
            <a href="https://cookpad.com/mx/recetas/10837615-caldo-de-res-sencillo" target="_blank"> CALDO DE RES (SENCILLO)</a> <br> <br>
            <a href="https://www.recetasnestle.com.co/recetas/ensalada-de-fruta-con-queso" target="_blank"> ENSALADA DE FRUTAS</a>
        </div>
    </div>
</div>

<div class="footer"> 
    <h2>Frutería "El Plátano Riendo"</h2>
    <p>&copy; 2024 Todos los derechos reservados</p>
</div>

</body> 
</html>
