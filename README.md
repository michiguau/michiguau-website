# michiguau-website
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda Michiguau</title>
    <style>
        body {
            background-color: #f0f8ff; /* Azul celeste */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4682b4; /* Azul acero */
            color: #ffffff; /* Blanco */
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin-top: 0;
        }
        nav {
            background-color: #87ceeb; /* Azul cielo */
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #ffffff; /* Blanco */
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: #6495ed; /* Azul claro */
        }
        section {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #4682b4; /* Azul acero */
            color: #ffffff; /* Blanco */
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .product-images {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .product-images img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            margin: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>¡Bienvenido a Michiguau!</h1>
        <p>Tu tienda de mascotas favorita</p>
    </header>
    
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#productos">Productos</a>
        <a href="#contacto">Contacto</a>
    </nav>
    
    <section id="inicio">
        <h2>Inicio</h2>
        <p>Bienvenido a Michiguau, tu tienda de mascotas favorita. Aquí encontrarás todo lo que necesitas para consentir a tu mascota.</p>
        <img src="ruta/a/tu/imagen.jpg" alt="Imagen de inicio">
    </section>
    
    <section id="productos">
        <h2>Productos</h2>
        <h3>Gatos</h3>
        <div class="product-images">
            <!-- Aquí puedes agregar imágenes de productos para gatos -->
            <img src="ruta/a/tu/imagen1.jpg" alt="Producto para gatos 1">
            <img src="ruta/a/tu/imagen2.jpg" alt="Producto para gatos 2">
            <img src="ruta/a/tu/imagen3.jpg" alt="Producto para gatos 3">
            <img src="ruta/a/tu/imagen4.jpg" alt="Producto para gatos 4">
            <img src="ruta/a/tu/imagen5.jpg" alt="Producto para gatos 5">
        </div>
        <h3>Perros</h3>
        <div class="product-images">
            <!-- Aquí puedes agregar imágenes de productos para perros -->
            <img src="ruta/a/tu/imagen6.jpg" alt="Producto para perros 1">
            <img src="ruta/a/tu/imagen7.jpg" alt="Producto para perros 2">
            <img src="ruta/a/tu/imagen8.jpg" alt="Producto para perros 3">
            <img src="ruta/a/tu/imagen9.jpg" alt="Producto para perros 4">
            <img src="ruta/a/tu/imagen10.jpg" alt="Producto para perros 5">
        </div>
        <h3>Otras mascotas</h3>
        <div class="product-images">
            <!-- Aquí puedes agregar imágenes de productos para otras mascotas -->
            <img src="ruta/a/tu/imagen11.jpg" alt="Producto para otras mascotas 1">
            <img src="ruta/a/tu/imagen12.jpg" alt="Producto para otras mascotas 2">
            <img src="ruta/a/tu/imagen13.jpg" alt="Producto para otras mascotas 3">
            <img src="ruta/a/tu/imagen14.jpg" alt="Producto para otras mascotas 4">
            <img src="ruta/a/tu/imagen15.jpg" alt="Producto para otras mascotas 5">
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Estamos aquí para ayudarte. Puedes contactarnos en cualquier momento para obtener más información sobre nuestros productos y servicios.</p>
        <p>Número de teléfono: <a href="https://wa.me/3001244872">3001244872 (WhatsApp)</a></p>
        <p>Instagram: <a href="https://www.instagram.com/michiguauu/">@michiguauu</a></p>
        <p>Dirección: Cr 52 #128 sur 69, Caldas, Antioquia</p>
    </section>
    
    <footer>
        <p>&copy; 2024 Michiguau - Todos los derechos reservados</p>
    </footer>
</body>
</html>
