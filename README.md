<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AROMA DEL DIA</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet" />
  
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

  <style>
    /* Estilo para el fondo con textura sutil */
    body {
      /* Textura sutil para evitar el "fondo plano" */
      background-image: url('https://www.transparenttextures.com/patterns/dark-denim.png'); 
      background-repeat: repeat;
      background-color: #1a202c; 
    }
  </style>
</head>
<body class="text-gray-100 font-sans">

  <header class="bg-gray-800 shadow-lg sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-10 h-10 rounded-md bg-black text-white flex items-center justify-center font-bold">AM</div>
        <div>
          <h1 class="text-xl font-semibold text-white">AROMA DEL DIA</h1>
          <p class="text-xs text-gray-400">Comienza tus mañanas con un sorbo.</p>
        </div>
      </div>
      <nav class="flex items-center gap-6 text-sm">
        <a href="#historia" class="hover:text-white text-gray-300">Conocenos</a>
        <a href="#cafe" class="hover:text-white text-gray-300">Nuestro café</a>
        <a href="#espacio" class="hover:text-white text-gray-300">El espacio</a>
        <a href="#menu-info" class="hover:text-white text-gray-300">Menu</a>
        <a href="#contacto" class="hover:text-white text-gray-300">Contacto</a>
      </nav>
    </div>
  </header>

  <section class="relative h-[65vh] overflow-hidden">
    <img src="https://www.nippon.com/es/ncommon/contents/japan-topics/329561/329561.jpg" class="absolute inset-0 w-full h-full object-cover opacity-90" />
    <div class="absolute inset-0 bg-black/60"></div> 
    <div class="relative z-10 max-w-7xl mx-auto px-6 h-full flex items-center">
      <div class="text-white max-w-xl" data-aos="fade-up">
        <h2 class="text-5xl font-extrabold leading-tight">El arte del café, hecho con alma</h2>
        <p class="mt-4 text-lg text-gray-200">Un espacio dedicado a ti y tus pensamientos.</p>
        <a href="#menu-info" class="mt-8 inline-block bg-white text-black font-bold py-3 px-8 rounded-md text-lg hover:bg-gray-200 transition-colors">
          Ver el Menú
        </a>
      </div>
    </div>
  </section>

  <section id="historia" class="max-w-7xl mx-auto px-6 py-20 grid md:grid-cols-2 gap-10 bg-gray-900 rounded-lg shadow-xl" data-aos="fade-up">
    <div class="flex flex-col justify-center">
      <h3 class="text-4xl font-bold mb-4">Nuestra historia</h3>
      <p class="text-gray-300 leading-relaxed text-lg">Fundada por amantes del café y la música, "Aroma del dia" nació con la intención de recuperar lo que hace especial a una buena taza: la pausa, la charla honesta y el cariño por lo artesanal. No somos una cadena, somos un punto de encuentro.</p>
      <p class="mt-4 text-gray-300 leading-relaxed text-lg">Apostamos por procesos tradicionales, tostadores locales y una filosofía simple: calidad a cantidad, no lo olvides nuestras siglas "AM" no solo son siglas es Am de tu mañana</p>
    </div>
    <img src="https://i0.wp.com/foodandpleasure.com/wp-content/uploads/2022/04/l1000298.jpg?fit=1280%2C721&ssl=1" class="rounded-lg shadow-md" />
  </section>

  <section id="cafe" class="bg-gray-800 py-20 border-t border-b border-gray-700">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-14" data-aos="fade-up">
      <img src="https://perfectdailygrind.com/es/wp-content/uploads/sites/2/2023/07/Preparacion-de-cafe-en-barra.jpg" class="rounded-xl shadow" />
      <div class="flex flex-col justify-center">
        <h3 class="text-4xl font-bold mb-4">Nuestro café</h3>
        <p class="text-gray-300 text-lg leading-relaxed">Trabajamos con granos seleccionados de Chiapas, Veracruz y Oaxaca. Cada lote es tostado en pequeños volúmenes para garantizar frescura y un perfil aromático profundo.</p>
        <ul class="mt-4 space-y-2 text-gray-300 text-lg">
          <li>• Tostado artesanal</li>
          <li>• Selección de micro-lotes</li>
          <li>• Técnicas tradicionales y contemporaneas de preparación</li>
          <li>• Calidad y confianza</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="espacio" class="max-w-7xl mx-auto px-6 py-20">
    <h3 class="text-4xl font-bold mb-10 text-center" data-aos="fade-up">El espacio para tu ser y tu alma</h3>
    
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-gray-800 rounded-xl overflow-hidden shadow-xl transition-transform duration-300 hover:scale-105" data-aos="fade-up" data-aos-delay="100">
        <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=1000&q=60" class="w-full h-56 object-cover" />
        <div class="p-5">
          <h4 class="font-semibold text-xl text-white">Tu segunda casa</h4>
          <p class="text-gray-400 mt-2">Ideal para universitarios, trabajadores, contadores y administradores.</p>
        </div>
      </div>

      <div class="bg-gray-800 rounded-xl overflow-hidden shadow-xl transition-transform duration-300 hover:scale-105" data-aos="fade-up" data-aos-delay="200">
        <img src="https://images.unsplash.com/photo-1504754524776-8f4f37790ca0?auto=format&fit=crop&w=1000&q=60" class="w-full h-56 object-cover" />
        <div class="p-5">
          <h4 class="font-semibold text-xl text-white">Diseño hogareño</h4>
          <p class="text-gray-400 mt-2">Madera, luz suave y detalles que te hacen no querer irte</p>
        </div>
      </div>

      <div class="bg-gray-800 rounded-xl overflow-hidden shadow-xl transition-transform duration-300 hover:scale-105" data-aos="fade-up" data-aos-delay="300">
        <img src="https://hips.hearstapps.com/hmg-prod/images/cafe-1599479980.jpg?crop=1xw:1xh;center,top&resize=640:*" class="w-full h-56 object-cover" />
        <div class="p-5">
          <h4 class="font-semibold text-xl text-white">Panadería y reposteria</h4>
          <p class="text-gray-400 mt-2">Horneada diariamente,fresca y perfecta para acompañar un buen café o bebida.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="menu-info" class="bg-gray-900 py-20 border-t border-b border-gray-800">
    <div class="max-w-4xl mx-auto px-6">
      <h3 class="text-4xl font-bold mb-10 text-center" data-aos="fade-up">El Menú Completo de Aroma del Día</h3>

      <div id="accordion-menu" class="space-y-4">

        <div class="bg-gray-800 rounded-xl shadow-xl transition-shadow duration-300 hover:shadow-yellow-500/10" data-aos="fade-up" data-aos-delay="100">
          <div class="flex justify-between items-center p-5 cursor-pointer accordion-toggle" data-target="menu-desayuno">
            <h4 class="font-bold text-2xl text-white">🍳 Desayuno</h4>
            <svg class="w-6 h-6 text-yellow-400 transform transition-transform duration-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9l6 6 6-6"/></svg>
          </div>
          <div id="menu-desayuno" class="p-5 pt-0 hidden accordion-content">
            <p class="text-gray-400 mb-6 text-sm">Energía para iniciar tu día. Disponible hasta las 12:00 PM.</p>
            <div class="space-y-4">
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Huevos al gusto</span><span class="font-semibold text-yellow-400">$75</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Chilaquiles</span><span class="font-semibold text-yellow-400">$80</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Molletes</span><span class="font-semibold text-yellow-400">$95</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Hotcake o Waffle</span><span class="font-semibold text-yellow-400">$105</span></div>
              <div class="flex justify-between"><span class="text-gray-200">Fruta de Temporada</span><span class="font-semibold text-yellow-400">$55</span></div>
            </div>
          </div>
        </div>

        <div class="bg-gray-800 rounded-xl shadow-xl transition-shadow duration-300 hover:shadow-yellow-500/10" data-aos="fade-up" data-aos-delay="200">
          <div class="flex justify-between items-center p-5 cursor-pointer accordion-toggle" data-target="menu-almuerzo">
            <h4 class="font-bold text-2xl text-white">🥗 Almuerzo</h4>
            <svg class="w-6 h-6 text-yellow-400 transform transition-transform duration-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9l6 6 6-6"/></svg>
          </div>
          <div id="menu-almuerzo" class="p-5 pt-0 hidden accordion-content">
            <p class="text-gray-400 mb-6 text-sm">Opciones frescas y ligeras para media mañana o comida.</p>
            <div class="space-y-4">
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Sándwich</span><span class="font-semibold text-yellow-400">$115</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Ensaladas</span><span class="font-semibold text-yellow-400">$110</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Baguette</span><span class="font-semibold text-yellow-400">$110</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Chapatas</span><span class="font-semibold text-yellow-400">$85</span></div>
              <div class="flex justify-between"><span class="text-gray-200">Enchiladas</span><span class="font-semibold text-yellow-400">$80</span></div>
            </div>
          </div>
        </div>

        <div class="bg-gray-800 rounded-xl shadow-xl transition-shadow duration-300 hover:shadow-yellow-500/10" data-aos="fade-up" data-aos-delay="300">
          <div class="flex justify-between items-center p-5 cursor-pointer accordion-toggle" data-target="menu-reposteria">
            <h4 class="font-bold text-2xl text-white">🍰 Repostería & Panadería</h4>
            <svg class="w-6 h-6 text-yellow-400 transform transition-transform duration-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9l6 6 6-6"/></svg>
          </div>
          <div id="menu-reposteria" class="p-5 pt-0 hidden accordion-content">
            <p class="text-gray-400 mb-6 text-sm">El complemento perfecto para tu café, horneado diariamente.</p>
            <div class="space-y-4">
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Rebanada de pastel</span><span class="font-semibold text-yellow-400">$100</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Croissants</span><span class="font-semibold text-yellow-400">$90</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Tartas</span><span class="font-semibold text-yellow-400">$85</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Muffin</span><span class="font-semibold text-yellow-400">$68</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Brownies</span><span class="font-semibold text-yellow-400">$70</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Galletas</span><span class="font-semibold text-yellow-400">$58</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Cuernitos</span><span class="font-semibold text-yellow-400">$45</span></div>
              <div class="flex justify-between"><span class="text-gray-200">Empanadas</span><span class="font-semibold text-yellow-400">$45</span></div>
            </div>
          </div>
        </div>
        
        <div class="bg-gray-800 rounded-xl shadow-xl transition-shadow duration-300 hover:shadow-yellow-500/10" data-aos="fade-up" data-aos-delay="400">
          <div class="flex justify-between items-center p-5 cursor-pointer accordion-toggle" data-target="menu-calientes">
            <h4 class="font-bold text-2xl text-white">☕ Bebidas Calientes</h4>
            <svg class="w-6 h-6 text-yellow-400 transform transition-transform duration-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9l6 6 6-6"/></svg>
          </div>
          <div id="menu-calientes" class="p-5 pt-0 hidden accordion-content">
            <p class="text-gray-400 mb-6 text-sm">El alma de la casa, preparadas con granos de origen mexicano.</p>
            <div class="space-y-4">
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Café Expresso</span><span class="font-semibold text-yellow-400">$68</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Café Moka</span><span class="font-semibold text-yellow-400">$65</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Café Capuchino</span><span class="font-semibold text-yellow-400">$82</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Café Latte</span><span class="font-semibold text-yellow-400">$85</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Chocolate</span><span class="font-semibold text-yellow-400">$95</span></div>
              <div class="flex justify-between"><span class="text-gray-200">Té Chai</span><span class="font-semibold text-yellow-400">$90</span></div>
            </div>
          </div>
        </div>

        <div class="bg-gray-800 rounded-xl shadow-xl transition-shadow duration-300 hover:shadow-yellow-500/10" data-aos="fade-up" data-aos-delay="500">
          <div class="flex justify-between items-center p-5 cursor-pointer accordion-toggle" data-target="menu-frias">
            <h4 class="font-bold text-2xl text-white">🧊 Bebidas Frías</h4>
            <svg class="w-6 h-6 text-yellow-400 transform transition-transform duration-300" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9l6 6 6-6"/></svg>
          </div>
          <div id="menu-frias" class="p-5 pt-0 hidden accordion-content">
            <p class="text-gray-400 mb-6 text-sm">Refrescantes y vibrantes para un despertar frío.</p>
            <div class="space-y-4">
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Café Helado</span><span class="font-semibold text-yellow-400">$60</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Frappe de Moka</span><span class="font-semibold text-yellow-400">$100</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Frappe de Capuchino</span><span class="font-semibold text-yellow-400">$108</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Té Chai (Frío)</span><span class="font-semibold text-yellow-400">$110</span></div>
              <div class="flex justify-between border-b border-gray-700 pb-2"><span class="text-gray-200">Chocolate Frío</span><span class="font-semibold text-yellow-400">$110</span></div>
              <div class="flex justify-between"><span class="text-gray-200">Agua Embotellada</span><span class="font-semibold text-yellow-400">$30</span></div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <section id="ubicacion" class="max-w-7xl mx-auto px-6 py-20" data-aos="fade-up">
    <h3 class="text-4xl font-bold mb-6 text-center">Ubicación</h3>
    <p class="text-gray-300 text-lg mb-4 text-center">Nos encontramos en donde todo y nada ocurre:.</p>
    <p class="text-white font-semibold text-lg text-center mb-6">Av Sor Juana Inés de La Cruz 280, Centro Industrial Tlalnepantla, 54033 Tlalnepantla, Méx., México.</p>
    
    <div class="w-full h-[400px] rounded-xl overflow-hidden shadow-lg border border-gray-700">
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3760.83296853247!2d-99.1961603889988!3d19.50587748174418!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85d1f87a869fed69%3A0x67a1a49931326c71!2sAv%20Sor%20Juana%20In%C3%A9s%20de%20La%20Cruz%20280%2C%20Centro%20Industrial%20Tlalnepantla%2C%2054033%20Tlalnepantla%2C%20M%C3%A9x.!5e0!3m2!1ses-419!2smx!4v1731720875240!5m2!1ses-419!2smx" 
        width="100%" 
        height="100%" 
        style="border:0;" 
        allowfullscreen="" 
        loading="lazy" 
        referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>
    </section>

<section id="contacto" class="max-w-7xl mx-auto px-6 py-20" data-aos="fade-up">
    <h3 class="text-4xl font-bold mb-6">Contacto</h3>
    <p class="text-gray-300 text-lg mb-4">Para colaboraciones, sugerencias o información adicional:</p>
    <p class="text-white font-semibold text-lg">sooul.mp3@gmail.com</p>
    <p class="text-gray-400 text-md mt-2">Lunes a sabado — 8:00 a 21:00</p>
  </section>

  <section id="encuesta" class="bg-gray-800 py-20 border-t border-gray-700">
    <div class="max-w-3xl mx-auto px-6 text-center" data-aos="fade-up">
      
      <div id="success-message" class="hidden py-16 bg-gray-700 rounded-lg">
          <h3 class="text-4xl font-bold text-green-400 mb-4">¡Gracias por tu opinión!</h3>
          <p class="text-gray-200 text-lg">Tu comentario ha sido enviado exitosamente Valoramos mucho tu apoyo ☕.</p>
          <button id="reset-form-btn" class="mt-8 bg-black text-white font-bold py-2 px-6 rounded-md hover:bg-gray-900 transition-colors">
              Volver a Comentar
          </button>
      </div>

      <form id="survey-form">
        <h3 class="text-4xl font-bold mb-6">¿Qué te pareció tu visita?</h3>
        <p class="text-gray-300 text-lg mb-8">¡Tu opinión nos importa! Ayúdanos a mejorar.</p>
        
        <div class="mb-6">
          <label class="block text-lg font-semibold mb-3">Califica tu experiencia</label>
          <div class="flex justify-center gap-4 text-4xl text-gray-400" id="star-rating">
            <span class="star cursor-pointer" data-value="1">★</span>
            <span class="star cursor-pointer" data-value="2">★</span>
            <span class="star cursor-pointer" data-value="3">★</span>
            <span class="star cursor-pointer" data-value="4">★</span>
            <span class="star cursor-pointer" data-value="5">★</span>
          </div>
          <input type="hidden" name="calificacion" id="rating-value" value="0">
        </div>

        <div class="mb-6">
          <label for="comentarios" class="block text-lg font-semibold mb-3">Tus comentarios (opcional)</label>
          <textarea 
            id="comentarios" 
            name="comentarios" 
            rows="4" 
            class="w-full p-3 border border-gray-600 rounded-md shadow-sm focus:ring-yellow-500 focus:border-yellow-500 bg-gray-700 text-white placeholder-gray-400" 
            placeholder="Escribe tu opinión aquí..."
          ></textarea>
        </div>

        <button type="submit" class="bg-white text-black font-bold py-3 px-10 rounded-md text-lg hover:bg-gray-200 transition-colors">
          Enviar Opinión
        </button>
      </form>

    </div>
  </section>
  <footer class="bg-gray-800 border-t border-gray-700 mt-8">
    <div class="max-w-7xl mx-auto px-6 py-8">
      <div class="flex flex-col md:flex-row items-center justify-between">
        <div class="text-sm text-gray-400 mb-4 md:mb-0">
          © 2025 Cafetería Aroma del dia S.A DE C.V.
        </div>
        
        <div class="flex gap-6">
          <a href="#" class="text-gray-400 hover:text-white" title="Instagram">
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10 10-4.477 10-10S17.523 2 12 2zm0 16c-3.314 0-6-2.686-6-6s2.686-6 6-6 6 2.686 6 6-2.686 6-6 6zm0-10c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm6.5-3c-.828 0-1.5.672-1.5 1.5s.672 1.5 1.5 1.5 1.5-.672 1.5-1.5-.672-1.5-1.5-1.5z" clip-rule="evenodd"/></svg>
          </a>
          <a href="#" class="text-gray-400 hover:text-white" title="Facebook">
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.772-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd"/></svg>
          </a>
          <a href="#" class="text-gray-400 hover:text-white" title="Twitter (X)">
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
          </a>
        </div>
        
        <div class="text-sm text-gray-400 mt-4 md:mt-0">
          Hecho con cafe y codigo
        </div>
      </div>
    </div>
  </footer>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({
      duration: 800,
      once: true,
    });
    
    document.addEventListener('DOMContentLoaded', function() {
      // --- LÓGICA DE CALIFICACIÓN POR ESTRELLAS ---
      const stars = document.querySelectorAll('#star-rating .star');
      const ratingInput = document.getElementById('rating-value');
      let currentRating = 0;

      function highlightStars(value) {
        stars.forEach(star => {
          if (star.dataset.value <= value) {
            star.classList.add('text-yellow-500');
            star.classList.remove('text-gray-400');
          } else {
            star.classList.remove('text-yellow-500');
            star.classList.add('text-gray-400');
          }
        });
      }

      stars.forEach(star => {
        star.addEventListener('mouseover', function() { highlightStars(this.dataset.value); });
        star.addEventListener('mouseout', function() { highlightStars(currentRating); });
        star.addEventListener('click', function() {
          currentRating = this.dataset.value;
          ratingInput.value = currentRating;
          highlightStars(currentRating);
        });
      });

      // --- LÓGICA DE SIMULACIÓN DE ENVÍO DE FORMULARIO ---
      const surveyForm = document.getElementById('survey-form');
      const successMessage = document.getElementById('success-message');
      const resetButton = document.getElementById('reset-form-btn');

      surveyForm.addEventListener('submit', function(event) {
        event.preventDefault(); // Detiene el envío real del formulario (simulación)
        
        surveyForm.classList.add('hidden');
        successMessage.classList.remove('hidden');

        // Limpia el formulario y el rating
        surveyForm.reset();
        currentRating = 0;
        ratingInput.value = '0';
        highlightStars(0);
      });

      resetButton.addEventListener('click', function() {
        successMessage.classList.add('hidden');
        surveyForm.classList.remove('hidden');
      });


      // --- LÓGICA DEL MENÚ ACORDEÓN ---
      const toggles = document.querySelectorAll('.accordion-toggle');

      toggles.forEach(toggle => {
          toggle.addEventListener('click', () => {
              const targetId = toggle.getAttribute('data-target');
              const content = document.getElementById(targetId);
              const icon = toggle.querySelector('svg');

              // Si el contenido está oculto, lo muestra y rota el ícono
              if (content.classList.contains('hidden')) {
                  // Cierra cualquier otro contenido abierto (opcional, pero más limpio)
                  document.querySelectorAll('.accordion-content').forEach(item => {
                      item.classList.add('hidden');
                  });
                  document.querySelectorAll('.accordion-toggle svg').forEach(svg => {
                      svg.classList.remove('rotate-180');
                  });

                  // Abre el contenido actual
                  content.classList.remove('hidden');
                  icon.classList.add('rotate-180');
              } else {
                  // Si está visible, lo oculta
                  content.classList.add('hidden');
                  icon.classList.remove('rotate-180');
              }
          });
      });
    });
  </script>

</body>
</html>
