 <!DOCTYPE html>  
    <html lang="es">  
    <head>  
        <meta charset="UTF-8">  
        <meta name="viewport" content="width=device-width, initial-scale=1.0">  
        <title>Agencia de Marketing</title>  
        <script src="https://cdn.tailwindcss.com"></script>  
        <style>  
            .fade-in {  
                animation: fadeIn 1s ease-in-out;  
            }  
            @keyframes fadeIn {  
                from { opacity: 0; }  
                to { opacity: 1; }  
            }  
        </style>  
    </head>  
    <body class="bg-gray-100">  
        <header class="bg-blue-600 text-white p-6 text-center fade-in">  
            <h1 class="text-5xl font-bold">Impulsa tu Negocio con Nuestra Agencia de Marketing</h1>  
            <p class="mt-2 text-lg">Estrategias personalizadas para alcanzar tus objetivos</p>  
            <a href="#contact" class="mt-4 inline-block bg-white text-blue-600 font-semibold py-2 px-4 rounded shadow hover:bg-gray-200 transition">Contáctanos</a>  
        </header>  
        
        <section class="p-6 fade-in">  
            <h2 class="text-4xl font-bold text-center">Nuestros Servicios</h2>  
            <div class="mt-4 grid grid-cols-1 md:grid-cols-3 gap-6">  
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">  
                    <h3 class="font-semibold text-xl">SEO</h3>  
                    <p>Optimización para motores de búsqueda para aumentar tu visibilidad.</p>  
                </div>  
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">  
                    <h3 class="font-semibold text-xl">Publicidad Digital</h3>  
                    <p>Campañas efectivas en redes sociales y Google Ads.</p>  
                </div>  
                <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition">  
                    <h3 class="font-semibold text-xl">Diseño Web</h3>  
                    <p>Creación de sitios web atractivos y funcionales.</p>  
                </div>  
            </div>  
        </section>  

        <section class="bg-gray-200 p-6 fade-in">  
            <h2 class="text-4xl font-bold text-center">Testimonios</h2>  
            <div class="mt-4">  
                <blockquote class="text-center italic">"Gracias a esta agencia, nuestras ventas han aumentado un 50%!" - Cliente Satisfecho</blockquote>  
            </div>  
        </section>  

        <section id="contact" class="p-6 fade-in">  
            <h2 class="text-4xl font-bold text-center">Contáctanos</h2>  
            <form class="mt-4 max-w-md mx-auto bg-white p-6 rounded-lg shadow-lg">  
                <input type="text" placeholder="Tu Nombre" class="w-full p-2 mb-4 border rounded" required>  
                <input type="email" placeholder="Tu Correo" class="w-full p-2 mb-4 border rounded" required>  
                <textarea placeholder="Tu Mensaje" class="w-full p-2 mb-4 border rounded" required></textarea>  
                <button type="submit" class="w-full bg-blue-600 text-white font-semibold py-2 rounded hover:bg-blue-700 transition">Enviar</button>  
            </form>  
        </section>  

        <footer class="bg-blue-600 text-white text-center p-4">  
            <p>&copy; 2023 Agencia de Marketing. Todos los derechos reservados.</p>  
        </footer>  
    </body>  
    </html>  
