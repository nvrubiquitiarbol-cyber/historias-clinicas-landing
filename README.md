# historias-clinicas-landing
 Historias Clínicas — Edición Consultorio
Landing Page comercial para el sistema de fichas médicas, evoluciones y recetas desarrollado por Misiones Tech Service.

Sistema de escritorio para Windows pensado para médicos, especialistas y consultorios independientes. Pago único, sin Internet, datos protegidos en su computadora.

🖥️ Vista Previa
La página presenta el producto con un diseño médico institucional de alto impacto, optimizado para convertir visitantes en consultas directas por WhatsApp.

Secciones incluidas
Sección	Descripción
Navbar fija	Identidad de marca + navegación + botón WhatsApp con efecto glassmorphism
Hero	Titular persuasivo + mockup interactivo del software con datos de ejemplo
Problema vs. Solución	Comparativa visual entre sistemas web con abono y nuestro sistema local
Módulos y Funciones	Tarjetas con las 5 funcionalidades principales del sistema
Recetario	Simulación visual de una receta médica impresa (1/3 de A4)
3 Pasos	Proceso de puesta en marcha simplificado
Preguntas Frecuentes	Acordeón interactivo con las dudas más comunes
Cierre Comercial	Llamado a la acción final hacia WhatsApp
Botón flotante	Ícono de WhatsApp fijo con animación de pulso
🚀 Tecnologías
HTML5 semántico
Tailwind CSS (CDN, sin compilación)
Lucide Icons (CDN)
JavaScript vanilla (acordeón, animaciones, menú móvil)
Cero dependencias de compilación — un único archivo index.html
📱 Optimizado para iPhone y Safari iOS
La página fue blindada para dispositivos Apple de alta gama con las siguientes mejoras:

Safe Area Insets — env(safe-area-inset-bottom) en botón flotante, footer y menú móvil para no interferir con el Home Indicator del iPhone.
Viewport dinámico — viewport-fit=cover para pantallas con notch e Isla Dinámica.
Renderizado Retina — -webkit-font-smoothing: antialiased y font stack con SF Pro Display.
Glassmorphism Safari — -webkit-backdrop-filter como fallback en el navbar translúcido.
Mockup deslizable — En móvil, la simulación del software se desliza horizontalmente con scroll táctil fluido (-webkit-overflow-scrolling: touch).
Botones de 48px+ — Todos los CTA cumplen con las guías de ergonomía táctil y ocupan ancho completo en móvil.
Cero desborde horizontal — overflow-x: hidden global y contención estricta en cada sección.
📂 Estructura del Proyecto

landig-page-HC2.0/
├── index.html      ← Archivo único, listo para publicar
└── README.md
🌐 Publicación
El archivo está diseñado para desplegarse sin compilación en cualquier hosting estático gratuito:

GitHub Pages
Suba el repositorio a GitHub.
Vaya a Settings → Pages.
Seleccione la rama main y la carpeta / (root).
Su página estará disponible en https://su-usuario.github.io/nombre-del-repo/.
Cloudflare Pages
Conecte el repositorio desde el panel de Cloudflare Pages.
No requiere comando de compilación.
Directorio de salida: / (raíz).
Netlify
Arrastre la carpeta del proyecto a Netlify Drop.
Publicado al instante.
📞 Contacto Comercial
Todas las llamadas a la acción de la página apuntan al WhatsApp oficial:

+54 9 3755 548794

→ Enviar mensaje por WhatsApp

