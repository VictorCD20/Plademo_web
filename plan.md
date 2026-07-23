<!DOCTYPE html>

<html class="light" lang="es"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Contacto - PLADEMO</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-secondary": "#ffffff",
                        "primary-fixed-dim": "#acc9ef",
                        "primary": "#00162b",
                        "on-error": "#ffffff",
                        "on-tertiary-fixed": "#001e2c",
                        "secondary": "#0e60a6",
                        "inverse-primary": "#acc9ef",
                        "surface-container-low": "#f1f4f7",
                        "on-surface-variant": "#43474d",
                        "on-secondary-fixed-variant": "#004881",
                        "secondary-container": "#77b4ff",
                        "on-background": "#181c1e",
                        "on-primary": "#ffffff",
                        "primary-container": "#082b49",
                        "on-primary-container": "#7693b6",
                        "surface-container-lowest": "#ffffff",
                        "surface-container-high": "#e5e8eb",
                        "on-secondary-container": "#00457b",
                        "text-dark": "#101820",
                        "on-primary-fixed-variant": "#2b4968",
                        "inverse-surface": "#2d3133",
                        "surface-variant": "#e0e3e6",
                        "on-error-container": "#93000a",
                        "error": "#ba1a1a",
                        "tertiary-container": "#002d3f",
                        "success-sustainability": "#75C94B",
                        "on-secondary-fixed": "#001c38",
                        "surface": "#f7fafd",
                        "tertiary-fixed-dim": "#78d1ff",
                        "text-secondary": "#5F6B76",
                        "secondary-fixed-dim": "#a2c9ff",
                        "surface-white": "#FFFFFF",
                        "outline": "#73777e",
                        "surface-bright": "#f7fafd",
                        "tertiary-fixed": "#c3e8ff",
                        "tertiary": "#001722",
                        "surface-dim": "#d7dadd",
                        "primary-fixed": "#d1e4ff",
                        "on-tertiary": "#ffffff",
                        "outline-variant": "#c3c6ce",
                        "on-tertiary-fixed-variant": "#004d68",
                        "on-tertiary-container": "#009bcf",
                        "surface-container": "#ebeef1",
                        "background": "#f7fafd",
                        "on-primary-fixed": "#001d36",
                        "on-surface": "#181c1e",
                        "inverse-on-surface": "#eef1f4",
                        "surface-container-highest": "#e0e3e6",
                        "surface-tint": "#446081",
                        "secondary-fixed": "#d3e4ff",
                        "error-container": "#ffdad6"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "section-padding": "120px",
                        "grid-gutter": "24px",
                        "bento-gap": "16px",
                        "container-max-width": "1440px",
                        "grid-margin": "80px"
                    },
                    "fontFamily": {
                        "body-lg": ["Manrope"],
                        "headline-md": ["Manrope"],
                        "label-caps": ["Manrope"],
                        "headline-md-mobile": ["Manrope"],
                        "display-lg-mobile": ["Manrope"],
                        "display-lg": ["Manrope"],
                        "button": ["Manrope"],
                        "body-md": ["Manrope"],
                        "headline-sm": ["Manrope"]
                    },
                    "fontSize": {
                        "body-lg": ["18px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-md": ["44px", { "lineHeight": "1.2", "letterSpacing": "-0.01em", "fontWeight": "700" }],
                        "label-caps": ["12px", { "lineHeight": "1.0", "letterSpacing": "0.1em", "fontWeight": "700" }],
                        "headline-md-mobile": ["32px", { "lineHeight": "1.2", "fontWeight": "700" }],
                        "display-lg-mobile": ["40px", { "lineHeight": "1.2", "letterSpacing": "-0.01em", "fontWeight": "800" }],
                        "display-lg": ["64px", { "lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "800" }],
                        "button": ["14px", { "lineHeight": "1.0", "letterSpacing": "0.02em", "fontWeight": "600" }],
                        "body-md": ["16px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-sm": ["28px", { "lineHeight": "1.3", "fontWeight": "700" }]
                    }
                },
            },
        }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .bento-card {
            border: 1px solid theme('colors.outline-variant');
            transition: all 0.3s ease;
        }
        .bento-card:hover {
            border-color: theme('colors.secondary');
        }
    </style>
</head>
<body class="bg-background text-on-surface antialiased pt-20">
<!-- TopNavBar -->
<nav class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-grid-margin py-4 max-w-container-max-width mx-auto bg-surface-white border-b border-outline-variant">
<div class="flex items-center gap-8">
<a class="text-headline-sm font-headline-sm font-extrabold text-primary" href="#">PLADEMO</a>
<div class="hidden md:flex items-center gap-6">
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Inicio</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Productos</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Mercados</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Nosotros</a>
<a class="text-secondary font-bold border-b-2 border-secondary pb-1" href="#">Contacto</a>
</div>
</div>
<div class="flex items-center gap-4">
<a class="hidden md:inline-flex items-center justify-center bg-secondary text-surface-white px-6 py-3 font-button text-button rounded hover:bg-on-secondary-fixed transition-colors" href="#contacto">
                Solicitar cotización
            </a>
<button class="md:hidden text-primary">
<span class="material-symbols-outlined text-3xl" data-icon="menu">menu</span>
</button>
</div>
</nav>
<!-- Hero -->
<section class="bg-primary-container text-on-primary py-24 px-5 md:px-grid-margin relative overflow-hidden">
<div class="max-w-container-max-width mx-auto relative z-10">
<h1 class="font-display-lg-mobile text-display-lg-mobile md:font-display-lg md:text-display-lg max-w-3xl">Hablemos de tu próxima solución de empaque</h1>
</div>
<div class="absolute inset-0 opacity-10 pointer-events-none" style="background-image: radial-gradient(circle at 100% 100%, theme('colors.secondary') 0%, transparent 50%);"></div>
</section>
<!-- Form and Image Section -->
<section class="py-section-padding px-5 md:px-grid-margin max-w-container-max-width mx-auto" id="contacto">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-grid-gutter md:gap-bento-gap items-stretch">
<!-- Contact Form -->
<div class="bg-surface-white p-8 md:p-12 bento-card flex flex-col justify-center">
<h2 class="font-headline-sm text-headline-sm text-primary mb-8">Solicitar Cotización</h2>
<form class="space-y-6">
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="nombre">Nombre completo</label>
<input class="w-full border-outline-variant rounded p-3 focus:border-secondary focus:ring-1 focus:ring-secondary bg-surface-white text-on-surface transition-colors" id="nombre" placeholder="Tu nombre" type="text"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="empresa">Empresa</label>
<input class="w-full border-outline-variant rounded p-3 focus:border-secondary focus:ring-1 focus:ring-secondary bg-surface-white text-on-surface transition-colors" id="empresa" placeholder="Nombre de tu empresa" type="text"/>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="correo">Correo electrónico</label>
<input class="w-full border-outline-variant rounded p-3 focus:border-secondary focus:ring-1 focus:ring-secondary bg-surface-white text-on-surface transition-colors" id="correo" placeholder="tu@correo.com" type="email"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="telefono">Teléfono</label>
<input class="w-full border-outline-variant rounded p-3 focus:border-secondary focus:ring-1 focus:ring-secondary bg-surface-white text-on-surface transition-colors" id="telefono" placeholder="Tu número" type="tel"/>
</div>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="producto">Producto o Necesidad</label>
<select class="w-full border-outline-variant rounded p-3 focus:border-secondary focus:ring-1 focus:ring-secondary bg-surface-white text-on-surface transition-colors" id="producto">
<option disabled="" selected="" value="">Selecciona una opción</option>
<option value="empaque_flexible">Empaque Flexible</option>
<option value="etiquetas">Etiquetas</option>
<option value="bolsas">Bolsas preformadas</option>
<option value="otro">Otro</option>
</select>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-2" for="mensaje">Mensaje (opcional)</label>
<textarea class="w-full border-outline-variant rounded p-3 focus:border-secondary focus:ring-1 focus:ring-secondary bg-surface-white text-on-surface transition-colors resize-none" id="mensaje" placeholder="Detalles adicionales sobre tu proyecto..." rows="4"></textarea>
</div>
<button class="w-full bg-secondary text-surface-white py-4 font-button text-button rounded hover:bg-on-secondary-fixed transition-colors flex items-center justify-center gap-2 group" type="button">
                        Enviar solicitud
                        <span class="material-symbols-outlined text-lg group-hover:translate-x-1 transition-transform" data-icon="arrow_forward">arrow_forward</span>
</button>
</form>
</div>
<!-- Industrial Image -->
<div class="h-full min-h-[400px] relative bento-card overflow-hidden group hidden md:block">
<img alt="Industrial Production" class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A high-quality, professional photograph of a modern industrial manufacturing facility. Massive rolls of transparent packaging film are neatly stacked in the foreground on heavy-duty wooden pallets. In the background, clean, state-of-the-art blue and white industrial printing and laminating machines are in operation. The lighting is bright, sterile, and cool, typical of a high-end factory, emphasizing cleanliness and precision. The aesthetic is modern corporate, matching a light-mode industrial design theme with sharp contrasts." src="https://www.gstatic.com/labs-code/stitch/stitch-placeholder-300x300.svg"/>
<div class="absolute inset-0 bg-primary/10"></div>
<!-- Tag overlay -->
<div class="absolute bottom-6 left-6 bg-surface-white/90 backdrop-blur-sm px-4 py-2 flex items-center gap-2 border border-outline-variant">
<span class="w-2 h-2 rounded-full bg-success-sustainability animate-pulse"></span>
<span class="font-label-caps text-label-caps text-primary tracking-wider">PRODUCCIÓN CONTINUA</span>
</div>
</div>
</div>
</section>
<!-- Info Grid & Map -->
<section class="py-12 px-5 md:px-grid-margin max-w-container-max-width mx-auto">
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-bento-gap mb-bento-gap">
<!-- Info Modules -->
<div class="bg-surface-white p-6 bento-card flex flex-col items-start h-full">
<span class="material-symbols-outlined text-3xl text-secondary mb-4" data-icon="call">call</span>
<h3 class="font-label-caps text-label-caps text-on-surface-variant mb-1 uppercase">Teléfono</h3>
<p class="font-body-lg text-body-lg text-primary font-semibold">999 218 3848</p>
</div>
<div class="bg-surface-white p-6 bento-card flex flex-col items-start h-full">
<span class="material-symbols-outlined text-3xl text-secondary mb-4" data-icon="mail">mail</span>
<h3 class="font-label-caps text-label-caps text-on-surface-variant mb-1 uppercase">Correo</h3>
<p class="font-body-lg text-body-lg text-primary font-semibold truncate w-full" title="ventas@plademo.com.mx">ventas@plademo.com.mx</p>
</div>
<div class="bg-surface-white p-6 bento-card flex flex-col items-start h-full">
<span class="material-symbols-outlined text-3xl text-secondary mb-4" data-icon="location_on">location_on</span>
<h3 class="font-label-caps text-label-caps text-on-surface-variant mb-1 uppercase">Ubicación</h3>
<p class="font-body-md text-body-md text-primary">Carretera Dzununcan-Motul, C.P. 97430</p>
</div>
<div class="bg-surface-white p-6 bento-card flex flex-col items-start h-full">
<span class="material-symbols-outlined text-3xl text-secondary mb-4" data-icon="schedule">schedule</span>
<h3 class="font-label-caps text-label-caps text-on-surface-variant mb-1 uppercase">Horario</h3>
<p class="font-body-md text-body-md text-primary">L-V: 8:00 - 18:00<br/>Sáb: 8:00 - 12:30</p>
</div>
</div>
<!-- Map Container -->
<div class="w-full h-96 bento-card bg-surface-container-low relative overflow-hidden flex items-center justify-center">
<!-- Simulated Map placeholder - In real implementation, this would be an iframe or map component -->
<img alt="Map Location" class="absolute inset-0 w-full h-full object-cover opacity-80 mix-blend-multiply" data-alt="A clean, modern light-mode map interface showing a pinpoint location for an industrial area in Dzununcan-Motul. The map uses a very muted, minimal color palette with subtle greys and light blues for roads and water. A sharp corporate blue pinpoint marker indicates the exact location. The style is crisp, flat, and integrates seamlessly into a high-end corporate website design." data-location="Dzununcan-Motul, Mexico" src="https://www.gstatic.com/labs-code/stitch/stitch-placeholder-300x300.svg"/>
<div class="absolute bg-surface-white px-6 py-4 border border-outline-variant shadow-sm z-10 flex flex-col items-center pointer-events-none">
<span class="material-symbols-outlined text-secondary text-4xl mb-2" data-icon="pin_drop" data-weight="fill">pin_drop</span>
<span class="font-button text-button text-primary">Planta PLADEMO</span>
</div>
</div>
</section>
<!-- Recruitment Section -->
<section class="py-16 px-5 md:px-grid-margin max-w-container-max-width mx-auto bg-surface border-t border-outline-variant mt-12">
<div class="flex flex-col md:flex-row justify-between items-center bg-surface-white p-8 md:p-12 bento-card gap-8">
<div class="max-w-xl">
<h2 class="font-headline-sm text-headline-sm text-primary mb-3">¿Quieres trabajar con nosotros?</h2>
<p class="font-body-md text-body-md text-text-secondary">Únete a un equipo enfocado en la precisión técnica y el crecimiento continuo. Descubre oportunidades para desarrollar tu carrera en la industria del empaque.</p>
</div>
<a class="shrink-0 border-2 border-primary text-primary px-8 py-3 font-button text-button rounded hover:bg-primary hover:text-surface-white transition-colors" href="#">
                Ver vacantes
            </a>
</div>
</section>
<!-- Floating WhatsApp Button -->
<a aria-label="Hablar por WhatsApp" class="fixed bottom-8 right-8 z-50 bg-[#25D366] text-surface-white px-6 py-4 rounded-full shadow-lg hover:shadow-xl transition-all duration-300 flex items-center gap-3 hover:-translate-y-1" href="#">
<svg class="w-6 h-6 fill-current" viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413Z"></path></svg>
<span class="font-button text-button hidden md:inline">Hablar por WhatsApp</span>
</a>
<!-- Footer -->
<footer class="w-full bg-primary-container px-grid-margin py-section-padding flex flex-col md:flex-row justify-between gap-grid-gutter mt-24">
<div class="flex flex-col gap-6">
<span class="text-headline-sm font-headline-sm font-extrabold text-surface-white">PLADEMO</span>
<p class="font-body-md text-body-md text-on-primary-container max-w-sm">
                Soluciones de empaque industrial con precisión flexible.
            </p>
</div>
<div class="flex flex-col gap-4">
<nav class="flex flex-col md:flex-row gap-6 md:gap-8 flex-wrap">
<a class="text-on-primary-container font-normal hover:text-secondary-container transition-colors duration-200 font-label-caps text-label-caps" href="#">INICIO</a>
<a class="text-on-primary-container font-normal hover:text-secondary-container transition-colors duration-200 font-label-caps text-label-caps" href="#">PRODUCTOS</a>
<a class="text-on-primary-container font-normal hover:text-secondary-container transition-colors duration-200 font-label-caps text-label-caps" href="#">MERCADOS</a>
<a class="text-on-primary-container font-normal hover:text-secondary-container transition-colors duration-200 font-label-caps text-label-caps" href="#">NOSOTROS</a>
<a class="text-surface-white font-bold hover:text-secondary-container transition-colors duration-200 font-label-caps text-label-caps underline decoration-secondary-container" href="#">CONTACTO</a>
<a class="text-on-primary-container font-normal hover:text-secondary-container transition-colors duration-200 font-label-caps text-label-caps" href="#">BOLSA DE TRABAJO</a>
<a class="text-on-primary-container font-normal hover:text-secondary-container transition-colors duration-200 font-label-caps text-label-caps" href="#">AVISO DE PRIVACIDAD</a>
</nav>
<p class="font-body-md text-body-md text-on-primary-container mt-8">
                © 2024 PLADEMO. Todos los derechos reservados.
            </p>
</div>
</footer>
</body></html>

<!DOCTYPE html>

<html lang="es"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Bolsa de Trabajo - PLADEMO</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-secondary": "#ffffff",
                        "primary-fixed-dim": "#acc9ef",
                        "primary": "#00162b",
                        "on-error": "#ffffff",
                        "on-tertiary-fixed": "#001e2c",
                        "secondary": "#0e60a6",
                        "inverse-primary": "#acc9ef",
                        "surface-container-low": "#f1f4f7",
                        "on-surface-variant": "#43474d",
                        "on-secondary-fixed-variant": "#004881",
                        "secondary-container": "#77b4ff",
                        "on-background": "#181c1e",
                        "on-primary": "#ffffff",
                        "primary-container": "#082b49",
                        "on-primary-container": "#7693b6",
                        "surface-container-lowest": "#ffffff",
                        "surface-container-high": "#e5e8eb",
                        "on-secondary-container": "#00457b",
                        "text-dark": "#101820",
                        "on-primary-fixed-variant": "#2b4968",
                        "inverse-surface": "#2d3133",
                        "surface-variant": "#e0e3e6",
                        "on-error-container": "#93000a",
                        "error": "#ba1a1a",
                        "tertiary-container": "#002d3f",
                        "success-sustainability": "#75C94B",
                        "on-secondary-fixed": "#001c38",
                        "surface": "#f7fafd",
                        "tertiary-fixed-dim": "#78d1ff",
                        "text-secondary": "#5F6B76",
                        "secondary-fixed-dim": "#a2c9ff",
                        "surface-white": "#FFFFFF",
                        "outline": "#73777e",
                        "surface-bright": "#f7fafd",
                        "tertiary-fixed": "#c3e8ff",
                        "tertiary": "#001722",
                        "surface-dim": "#d7dadd",
                        "primary-fixed": "#d1e4ff",
                        "on-tertiary": "#ffffff",
                        "outline-variant": "#c3c6ce",
                        "on-tertiary-fixed-variant": "#004d68",
                        "on-tertiary-container": "#009bcf",
                        "surface-container": "#ebeef1",
                        "background": "#f7fafd",
                        "on-primary-fixed": "#001d36",
                        "on-surface": "#181c1e",
                        "inverse-on-surface": "#eef1f4",
                        "surface-container-highest": "#e0e3e6",
                        "surface-tint": "#446081",
                        "secondary-fixed": "#d3e4ff",
                        "error-container": "#ffdad6"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "section-padding": "120px",
                        "grid-gutter": "24px",
                        "bento-gap": "16px",
                        "container-max-width": "1440px",
                        "grid-margin": "80px"
                    },
                    "fontFamily": {
                        "body-lg": ["Manrope"],
                        "headline-md": ["Manrope"],
                        "label-caps": ["Manrope"],
                        "headline-md-mobile": ["Manrope"],
                        "display-lg-mobile": ["Manrope"],
                        "display-lg": ["Manrope"],
                        "button": ["Manrope"],
                        "body-md": ["Manrope"],
                        "headline-sm": ["Manrope"]
                    },
                    "fontSize": {
                        "body-lg": ["18px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-md": ["44px", { "lineHeight": "1.2", "letterSpacing": "-0.01em", "fontWeight": "700" }],
                        "label-caps": ["12px", { "lineHeight": "1.0", "letterSpacing": "0.1em", "fontWeight": "700" }],
                        "headline-md-mobile": ["32px", { "lineHeight": "1.2", "fontWeight": "700" }],
                        "display-lg-mobile": ["40px", { "lineHeight": "1.2", "letterSpacing": "-0.01em", "fontWeight": "800" }],
                        "display-lg": ["64px", { "lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "800" }],
                        "button": ["14px", { "lineHeight": "1.0", "letterSpacing": "0.02em", "fontWeight": "600" }],
                        "body-md": ["16px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-sm": ["28px", { "lineHeight": "1.3", "fontWeight": "700" }]
                    }
                },
            },
        }
    </script>
<style>
        body { font-family: 'Manrope', sans-serif; }
    </style>
</head>
<body class="bg-background text-on-surface antialiased pt-[88px]">
<!-- TopNavBar (Shared Component) -->
<nav class="bg-surface-white dark:bg-surface-white docked full-width top-0 border-b border-outline-variant flat no shadows fixed top-0 left-0 w-full z-50 flex justify-between items-center px-grid-margin py-4 max-w-container-max-width mx-auto">
<div class="flex items-center gap-8 w-full justify-between">
<a class="text-headline-sm font-headline-sm font-extrabold text-primary dark:text-primary-fixed" href="#">PLADEMO</a>
<div class="hidden md:flex items-center gap-6">
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200 font-button text-button" href="#">Inicio</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200 font-button text-button" href="#">Productos</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200 font-button text-button" href="#">Mercados</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200 font-button text-button" href="#">Nosotros</a>
<a class="text-secondary font-bold border-b-2 border-secondary pb-1 hover:text-secondary transition-colors duration-200 font-button text-button" href="#">Contacto</a>
</div>
<button class="bg-secondary text-on-secondary px-6 py-3 font-button text-button rounded hover:bg-secondary-container hover:text-on-secondary-container transition-colors duration-200">
                Solicitar cotización
            </button>
</div>
</nav>
<main class="max-w-container-max-width mx-auto px-5 md:px-grid-margin py-12 md:py-section-padding">
<!-- Hero Section -->
<section class="mb-20 grid grid-cols-1 lg:grid-cols-12 gap-grid-gutter items-center">
<div class="lg:col-span-5">
<h1 class="font-display-lg-mobile text-display-lg-mobile md:font-display-lg md:text-display-lg text-primary mb-6">Trabaja con PLADEMO</h1>
<p class="font-body-lg text-body-lg text-text-secondary mb-8 max-w-xl">
                    Buscamos personas comprometidas para crecer junto a nuestro equipo. Únete a una empresa líder en soluciones de empaque industrial donde la precisión y el desarrollo profesional van de la mano.
                </p>
<div class="flex gap-4">
<a class="inline-flex items-center justify-center bg-primary text-on-primary px-6 py-3 font-button text-button rounded hover:bg-primary-container transition-colors" href="#vacantes">
                        Ver Vacantes
                    </a>
</div>
</div>
<div class="lg:col-span-7 rounded overflow-hidden h-[400px] lg:h-[500px]">
<img class="w-full h-full object-cover" data-alt="Fotografía industrial de alta resolución mostrando empleados profesionales de PLADEMO trabajando en una moderna línea de producción, ambiente iluminado, limpio y seguro, estética corporativa e industrial, paleta de colores sobrios con acentos azules, composición editorial y balanceada, fotografía de gran angular." src="https://www.gstatic.com/labs-code/stitch/stitch-placeholder-300x300.svg"/>
</div>
</section>
<!-- Vacantes Section (Bento Grid) -->
<section class="mb-24" id="vacantes">
<div class="flex items-center justify-between mb-10 border-b border-outline-variant pb-4">
<h2 class="font-headline-md-mobile text-headline-md-mobile md:font-headline-md md:text-headline-md text-primary">Vacantes Disponibles</h2>
<span class="bg-surface-variant text-on-surface-variant px-3 py-1 rounded-full font-label-caps text-label-caps">2 Oportunidades</span>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-bento-gap">
<!-- Card 1 -->
<div class="bg-surface-white border border-outline-variant p-8 rounded flex flex-col hover:border-secondary transition-colors duration-300">
<div class="flex justify-between items-start mb-6">
<div>
<span class="inline-block bg-primary-fixed-dim text-on-primary-fixed-variant px-2 py-1 text-xs font-bold uppercase tracking-wider mb-2 rounded-sm">Producción</span>
<h3 class="font-headline-sm text-headline-sm text-primary mb-2">Operador de Producción</h3>
</div>
<span class="material-symbols-outlined text-outline">factory</span>
</div>
<div class="grid grid-cols-2 gap-4 mb-8">
<div>
<p class="font-label-caps text-label-caps text-text-secondary mb-1">Ubicación</p>
<p class="font-body-md text-body-md text-on-surface font-medium flex items-center gap-1">
<span class="material-symbols-outlined text-[18px]">location_on</span> Mérida, Yucatán
                            </p>
</div>
<div>
<p class="font-label-caps text-label-caps text-text-secondary mb-1">Jornada</p>
<p class="font-body-md text-body-md text-on-surface font-medium flex items-center gap-1">
<span class="material-symbols-outlined text-[18px]">schedule</span> Tiempo Completo
                            </p>
</div>
</div>
<button class="mt-auto w-full border border-primary text-primary px-6 py-3 font-button text-button rounded hover:bg-primary hover:text-on-primary transition-colors">
                        Postularme
                    </button>
</div>
<!-- Card 2 -->
<div class="bg-surface-white border border-outline-variant p-8 rounded flex flex-col hover:border-secondary transition-colors duration-300">
<div class="flex justify-between items-start mb-6">
<div>
<span class="inline-block bg-secondary-fixed text-on-secondary-fixed-variant px-2 py-1 text-xs font-bold uppercase tracking-wider mb-2 rounded-sm">Administración</span>
<h3 class="font-headline-sm text-headline-sm text-primary mb-2">Auxiliar Administrativo</h3>
</div>
<span class="material-symbols-outlined text-outline">business_center</span>
</div>
<div class="grid grid-cols-2 gap-4 mb-8">
<div>
<p class="font-label-caps text-label-caps text-text-secondary mb-1">Ubicación</p>
<p class="font-body-md text-body-md text-on-surface font-medium flex items-center gap-1">
<span class="material-symbols-outlined text-[18px]">location_on</span> Mérida, Yucatán
                            </p>
</div>
<div>
<p class="font-label-caps text-label-caps text-text-secondary mb-1">Jornada</p>
<p class="font-body-md text-body-md text-on-surface font-medium flex items-center gap-1">
<span class="material-symbols-outlined text-[18px]">schedule</span> Tiempo Completo
                            </p>
</div>
</div>
<button class="mt-auto w-full border border-primary text-primary px-6 py-3 font-button text-button rounded hover:bg-primary hover:text-on-primary transition-colors">
                        Postularme
                    </button>
</div>
</div>
<!-- Empty State Block -->
<div class="mt-bento-gap bg-surface-container-low border border-outline-variant p-8 rounded flex flex-col md:flex-row items-center justify-between gap-6">
<div>
<h4 class="font-headline-sm text-headline-sm text-primary mb-2 flex items-center gap-2">
<span class="material-symbols-outlined text-secondary">inbox</span> Sin vacantes activas de tu interés?
                    </h4>
<p class="font-body-md text-body-md text-text-secondary">Actualmente no tenemos más vacantes publicadas. Puedes compartirnos tu información para futuros procesos.</p>
</div>
<button class="shrink-0 bg-surface-white border border-secondary text-secondary px-6 py-3 font-button text-button rounded hover:bg-secondary-fixed transition-colors">
                    Enviar mi información
                </button>
</div>
</section>
<!-- Form Section -->
<section class="bg-surface-white border border-outline-variant rounded p-8 md:p-12">
<div class="max-w-3xl mx-auto">
<div class="text-center mb-10">
<h2 class="font-headline-md-mobile text-headline-md-mobile md:font-headline-md md:text-headline-md text-primary mb-4">Aplica Ahora</h2>
<p class="font-body-md text-body-md text-text-secondary">Completa el formulario para iniciar tu proceso con nosotros. Asegúrate de adjuntar tu currículum actualizado.</p>
</div>
<form class="space-y-6">
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div>
<label class="block font-label-caps text-label-caps text-text-secondary mb-2" for="nombre">Nombre completo</label>
<input class="w-full bg-surface-bright border border-outline-variant rounded px-4 py-3 focus:ring-1 focus:ring-secondary focus:border-secondary outline-none font-body-md text-body-md" id="nombre" placeholder="Ej. Juan Pérez" type="text"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-text-secondary mb-2" for="correo">Correo electrónico</label>
<input class="w-full bg-surface-bright border border-outline-variant rounded px-4 py-3 focus:ring-1 focus:ring-secondary focus:border-secondary outline-none font-body-md text-body-md" id="correo" placeholder="juan@ejemplo.com" type="email"/>
</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div>
<label class="block font-label-caps text-label-caps text-text-secondary mb-2" for="telefono">Teléfono</label>
<input class="w-full bg-surface-bright border border-outline-variant rounded px-4 py-3 focus:ring-1 focus:ring-secondary focus:border-secondary outline-none font-body-md text-body-md" id="telefono" placeholder="(999) 123 4567" type="tel"/>
</div>
<div>
<label class="block font-label-caps text-label-caps text-text-secondary mb-2" for="puesto">Puesto de interés</label>
<select class="w-full bg-surface-bright border border-outline-variant rounded px-4 py-3 focus:ring-1 focus:ring-secondary focus:border-secondary outline-none font-body-md text-body-md text-on-surface" id="puesto">
<option value="">Selecciona un puesto</option>
<option value="operador">Operador de Producción</option>
<option value="auxiliar">Auxiliar Administrativo</option>
<option value="general">Candidatura Espontánea</option>
</select>
</div>
</div>
<div>
<label class="block font-label-caps text-label-caps text-text-secondary mb-2" for="mensaje">Mensaje o Carta de presentación</label>
<textarea class="w-full bg-surface-bright border border-outline-variant rounded px-4 py-3 focus:ring-1 focus:ring-secondary focus:border-secondary outline-none font-body-md text-body-md resize-none" id="mensaje" placeholder="Cuéntanos brevemente sobre ti..." rows="4"></textarea>
</div>
<div>
<label class="block font-label-caps text-label-caps text-text-secondary mb-2">Adjuntar CV (PDF, DOCX)</label>
<div class="border-2 border-dashed border-outline-variant rounded p-8 text-center bg-surface-bright hover:bg-surface transition-colors cursor-pointer group">
<span class="material-symbols-outlined text-4xl text-outline mb-2 group-hover:text-secondary">upload_file</span>
<p class="font-body-md text-body-md text-on-surface mb-1">Haz clic o arrastra tu archivo aquí</p>
<p class="font-body-sm text-sm text-text-secondary">Tamaño máximo 5MB</p>
</div>
</div>
<div class="pt-4 border-t border-outline-variant flex justify-end">
<button class="bg-secondary text-on-secondary px-8 py-4 font-button text-button rounded hover:bg-secondary-container hover:text-on-secondary-container transition-colors shadow-sm flex items-center gap-2" type="submit">
                            Enviar Solicitud <span class="material-symbols-outlined text-[18px]">send</span>
</button>
</div>
</form>
</div>
</section>
</main>
<!-- Footer (Shared Component) -->
<footer class="w-full bg-primary-container px-grid-margin py-section-padding flex flex-col md:flex-row justify-between gap-grid-gutter mt-20">
<div class="flex flex-col gap-6 w-full md:w-1/3">
<span class="text-headline-sm font-headline-sm font-extrabold text-surface-white">PLADEMO</span>
<p class="text-on-primary-container font-body-md text-body-md max-w-sm">Precisión y flexibilidad en cada solución de empaque para la industria de alto rendimiento.</p>
</div>
<div class="grid grid-cols-2 gap-8 w-full md:w-2/3">
<div class="flex flex-col gap-4">
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Inicio</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Productos</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Mercados</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Nosotros</a>
</div>
<div class="flex flex-col gap-4">
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Contacto</a>
<a class="text-surface-white font-bold font-label-caps text-label-caps underline decoration-secondary-container hover:text-secondary-container transition-colors duration-200" href="#">Bolsa de trabajo</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Aviso de Privacidad</a>
</div>
</div>
<div class="w-full flex justify-between items-end mt-12 md:mt-0 pt-8 border-t border-on-primary-container/20 md:border-t-0 md:pt-0">
<p class="font-body-md text-body-md text-on-primary-container">© 2024 PLADEMO. Todos los derechos reservados.</p>
<!-- Floating WhatsApp conceptual placement within footer -->
<button class="bg-success-sustainability text-surface-white p-3 rounded-full hover:opacity-90 transition-opacity flex items-center justify-center">
<span class="material-symbols-outlined" data-weight="fill">chat</span>
</button>
</div>
</footer>
</body></html>
