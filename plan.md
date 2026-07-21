<!DOCTYPE html>

<html class="light" lang="es"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Productos - PLADEMO</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface-dim": "#d7dadd",
                        "inverse-surface": "#2d3133",
                        "text-dark": "#101820",
                        "outline": "#73777e",
                        "on-secondary-fixed-variant": "#004881",
                        "surface-white": "#FFFFFF",
                        "inverse-on-surface": "#eef1f4",
                        "on-tertiary-container": "#009bcf",
                        "error-container": "#ffdad6",
                        "on-error-container": "#93000a",
                        "inverse-primary": "#acc9ef",
                        "on-error": "#ffffff",
                        "on-primary-fixed-variant": "#2b4968",
                        "text-secondary": "#5F6B76",
                        "primary-container": "#082b49",
                        "surface-container-low": "#f1f4f7",
                        "secondary-container": "#77b4ff",
                        "secondary-fixed-dim": "#a2c9ff",
                        "surface-container-lowest": "#ffffff",
                        "secondary": "#0e60a6",
                        "tertiary-container": "#002d3f",
                        "surface-bright": "#f7fafd",
                        "on-tertiary": "#ffffff",
                        "surface-variant": "#e0e3e6",
                        "on-tertiary-fixed": "#001e2c",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#d3e4ff",
                        "outline-variant": "#c3c6ce",
                        "on-background": "#181c1e",
                        "success-sustainability": "#75C94B",
                        "tertiary-fixed": "#c3e8ff",
                        "on-primary-container": "#7693b6",
                        "on-secondary": "#ffffff",
                        "surface-container-highest": "#e0e3e6",
                        "primary-fixed": "#d1e4ff",
                        "on-surface": "#181c1e",
                        "on-primary": "#ffffff",
                        "background": "#f7fafd",
                        "primary": "#00162b",
                        "on-tertiary-fixed-variant": "#004d68",
                        "surface-tint": "#446081",
                        "surface-container": "#ebeef1",
                        "surface-container-high": "#e5e8eb",
                        "surface": "#f7fafd",
                        "on-primary-fixed": "#001d36",
                        "on-secondary-container": "#00457b",
                        "tertiary-fixed-dim": "#78d1ff",
                        "on-secondary-fixed": "#001c38",
                        "on-surface-variant": "#43474d",
                        "tertiary": "#001722",
                        "primary-fixed-dim": "#acc9ef"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "grid-gutter": "24px",
                        "section-padding": "120px",
                        "grid-margin": "80px",
                        "container-max-width": "1440px",
                        "bento-gap": "16px"
                    },
                    "fontFamily": {
                        "body-lg": ["Manrope"],
                        "headline-md-mobile": ["Manrope"],
                        "body-md": ["Manrope"],
                        "label-caps": ["Manrope"],
                        "display-lg-mobile": ["Manrope"],
                        "display-lg": ["Manrope"],
                        "headline-sm": ["Manrope"],
                        "headline-md": ["Manrope"],
                        "button": ["Manrope"]
                    },
                    "fontSize": {
                        "body-lg": ["18px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "headline-md-mobile": ["32px", { "lineHeight": "1.2", "fontWeight": "700" }],
                        "body-md": ["16px", { "lineHeight": "1.6", "fontWeight": "400" }],
                        "label-caps": ["12px", { "lineHeight": "1.0", "letterSpacing": "0.1em", "fontWeight": "700" }],
                        "display-lg-mobile": ["40px", { "lineHeight": "1.2", "letterSpacing": "-0.01em", "fontWeight": "800" }],
                        "display-lg": ["64px", { "lineHeight": "1.1", "letterSpacing": "-0.02em", "fontWeight": "800" }],
                        "headline-sm": ["28px", { "lineHeight": "1.3", "fontWeight": "700" }],
                        "headline-md": ["44px", { "lineHeight": "1.2", "letterSpacing": "-0.01em", "fontWeight": "700" }],
                        "button": ["14px", { "lineHeight": "1.0", "letterSpacing": "0.02em", "fontWeight": "600" }]
                    }
                }
            }
        }
    </script>
<style>
        body { font-family: 'Manrope', sans-serif; }
    </style>
</head>
<body class="bg-surface text-on-surface antialiased pt-24">
<!-- TopNavBar -->
<header class="bg-surface-white dark:bg-surface-white docked full-width top-0 border-b border-outline-variant flat no shadows fixed top-0 left-0 w-full z-50">
<div class="flex justify-between items-center px-grid-margin py-4 max-w-container-max-width mx-auto w-full">
<a class="text-headline-sm font-headline-sm font-extrabold text-primary dark:text-primary-fixed" href="#">PLADEMO</a>
<nav class="hidden md:flex gap-8">
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Inicio</a>
<a class="text-secondary font-bold border-b-2 border-secondary pb-1 opacity-80 scale-95 transition-all" href="#">Productos</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Mercados</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Nosotros</a>
<a class="text-text-secondary font-medium hover:text-secondary transition-colors duration-200" href="#">Contacto</a>
</nav>
<button class="bg-secondary text-surface-white font-button text-button px-6 py-3 rounded hover:bg-on-secondary-fixed-variant transition-colors duration-200">
                Solicitar cotización
            </button>
</div>
</header>
<!-- Editorial Hero Section -->
<section class="relative w-full h-[70vh] min-h-[600px] flex items-end mb-16 overflow-hidden">
<div class="absolute inset-0 bg-primary">
<img alt="Industrial packaging production facility" class="w-full h-full object-cover opacity-50 mix-blend-overlay" src="https://lh3.googleusercontent.com/aida-public/AB6AXuChDBlRns8mwO1NqEm7HlsOfZwLxg6IX2xKqdGEkcT4KPBELIQDDaRLDAeGtVhiy3o-Sqx6kTqNzUjDBQX8XyKiaJbgduAkdErwTIhrmWpjFxZh47d5UVYijW5VQX9PSuK1T0qY_D9FtQ-eVcwsLAkClTalQY7Kg0xbzFGjbnK-ACLIir5xOfTGd-g0Fd0AoQRXmeI_aK43e2BGXWh4APzYuJmCT-ckd-nL7TfOBaYY7isbca-Nazsxtg"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary via-primary/50 to-transparent"></div>
</div>
<div class="relative z-10 max-w-container-max-width mx-auto px-5 md:px-grid-margin w-full pb-16 flex flex-col md:flex-row justify-between items-end gap-8">
<div class="max-w-3xl">
<div class="flex items-center gap-4 mb-6">
<span class="text-secondary-fixed font-label-caps text-label-caps tracking-[0.2em] uppercase border border-secondary-fixed/30 px-3 py-1 bg-primary/40 backdrop-blur-sm">Catálogo Técnico</span>
<div class="h-px w-16 bg-secondary-fixed/50"></div>
<span class="text-secondary-fixed font-label-caps text-label-caps tracking-[0.2em] uppercase">Ref. 2024</span>
</div>
<h1 class="font-display-lg-mobile md:font-display-lg text-display-lg-mobile md:text-display-lg text-surface-white mb-6 leading-none">Soluciones de<br/>Empaque Flexible</h1>
<p class="font-body-lg text-body-lg text-secondary-fixed-dim max-w-xl">Ingeniería de precisión en plásticos para la industria. Exploración de materiales de alta resistencia, sellabilidad y rendimiento automatizado.</p>
</div>
<div class="hidden lg:flex gap-6 bg-surface-white/10 backdrop-blur-md border border-surface-white/20 p-6">
<div class="flex flex-col gap-1">
<span class="text-secondary-fixed text-label-caps font-label-caps opacity-70">ISO-9001</span>
<span class="text-surface-white text-headline-sm font-headline-sm">CERT</span>
</div>
<div class="w-px h-12 bg-surface-white/20"></div>
<div class="flex flex-col gap-1">
<span class="text-secondary-fixed text-label-caps font-label-caps opacity-70">CALIBRES</span>
<span class="text-surface-white text-headline-sm font-headline-sm">20-200μ</span>
</div>
</div>
</div>
</section>
<!-- Search and Filters (Editorial Style) -->
<section class="max-w-container-max-width mx-auto px-5 md:px-grid-margin mb-16 border-y border-outline-variant py-8">
<div class="flex flex-col lg:flex-row gap-8 items-center justify-between">
<div class="relative flex-grow w-full max-w-xl">
<span class="material-symbols-outlined absolute left-0 top-1/2 transform -translate-y-1/2 text-primary text-3xl">search</span>
<input class="w-full pl-12 pr-4 py-4 bg-transparent text-primary font-headline-sm text-headline-sm placeholder-outline focus:outline-none focus:border-b-2 focus:border-secondary transition-colors" placeholder="Buscar solución técnica..." type="text"/>
</div>
<div class="flex flex-wrap gap-2 lg:justify-end w-full lg:w-auto">
<button class="px-4 py-2 bg-primary text-surface-white font-label-caps text-label-caps uppercase tracking-widest hover:bg-secondary transition-colors">Todos</button>
<button class="px-4 py-2 border border-outline-variant text-primary font-label-caps text-label-caps uppercase tracking-widest hover:border-primary transition-colors">Bolsas</button>
<button class="px-4 py-2 border border-outline-variant text-primary font-label-caps text-label-caps uppercase tracking-widest hover:border-primary transition-colors">Rollos</button>
<button class="px-4 py-2 border border-outline-variant text-primary font-label-caps text-label-caps uppercase tracking-widest hover:border-primary transition-colors">Automático</button>
<button class="px-4 py-2 border border-success-sustainability/30 text-success-sustainability bg-success-sustainability/5 font-label-caps text-label-caps uppercase tracking-widest hover:bg-success-sustainability/10 transition-colors">Eco / Reciclado</button>
</div>
</div>
</section>
<!-- Bento Product Grid -->
<section class="max-w-container-max-width mx-auto px-5 md:px-grid-margin pb-section-padding">
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-bento-gap auto-rows-[320px]">
<!-- Large Feature Block (Industrial Bags) -->
<article class="col-span-1 md:col-span-2 lg:col-span-2 row-span-2 bg-surface-white border border-outline-variant group relative overflow-hidden flex flex-col hover:shadow-xl transition-shadow duration-500">
<div class="absolute inset-0 z-0">
<img alt="Industrial garbage bags" class="w-full h-full object-cover opacity-90 group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAvBsgVHjooOJlg4AqZ3oUsD_x0SYA-Da-vFEgLDhUSLg55-WHyD4cY7Ps8-V0AOfBPR6IXiS91iNDazMhd7G6NzHdxDG_9wVWSY8zW8ivjdLVpB2g3fe1-qUdoUzi05rMUS2r02dGscasVcXmIesupacFEpIRS8P22cDIcOazAOzEC2OTaCaAdePBcJiVtvcQH7LCZ4moU-owUgBbh5JNUNkH91KtGPI1gI7hzQQWuh_UX6r2E8pUK3Q"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/90 via-primary/40 to-transparent"></div>
</div>
<div class="relative z-10 p-8 flex flex-col h-full justify-between">
<div class="flex justify-between items-start">
<div class="bg-primary px-3 py-1 font-label-caps text-label-caps text-surface-white uppercase tracking-widest border border-surface-white/20">IND-01</div>
<div class="flex gap-2">
<span class="w-2 h-2 bg-secondary rounded-full"></span>
<span class="w-2 h-2 bg-outline-variant rounded-full"></span>
</div>
</div>
<div class="mt-auto text-surface-white">
<div class="flex items-center gap-4 mb-2">
<span class="text-tertiary-fixed font-label-caps text-label-caps tracking-widest uppercase">Uso Industrial</span>
<div class="h-px flex-grow bg-surface-white/20"></div>
</div>
<h3 class="font-display-lg-mobile text-display-lg-mobile mb-4">Bolsa de basura<br/>Alta Resistencia</h3>
<p class="font-body-md text-secondary-fixed max-w-md mb-8">Diseñadas para el manejo eficiente de residuos industriales. Soportan cargas pesadas sin desgarros. Calibres especiales para entornos exigentes.</p>
<div class="flex gap-4">
<button class="bg-surface-white text-primary font-button text-button px-6 py-3 hover:bg-secondary hover:text-surface-white transition-colors">Cotizar Volumen</button>
<button class="border border-surface-white/30 text-surface-white font-button text-button px-6 py-3 hover:bg-surface-white/10 transition-colors backdrop-blur-sm">Ficha Técnica</button>
</div>
</div>
</div>
</article>
<!-- Standard Block (Hotel Bags) -->
<article class="col-span-1 md:col-span-1 lg:col-span-1 row-span-1 bg-surface-container-lowest border border-outline-variant group flex flex-col hover:border-primary transition-colors">
<div class="p-6 flex flex-col h-full">
<div class="flex justify-between items-center mb-6">
<span class="text-text-secondary font-label-caps text-label-caps uppercase tracking-widest">COM-02</span>
<span class="material-symbols-outlined text-outline group-hover:text-primary transition-colors">local_mall</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-primary mb-2">Bolsa hotelera</h3>
<p class="font-body-md text-text-secondary line-clamp-3 mb-6 flex-grow">Soluciones de empaque especializado para hospitalidad. Acabado premium para lavandería y amenidades.</p>
<div class="h-32 bg-surface-container-low mb-6 overflow-hidden relative border border-outline-variant/50">
<img alt="Hotel laundry bags" class="w-full h-full object-cover mix-blend-multiply" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAPBYmOf49-KG38HI13bb736DUU48CtYR4MvVB2PCTRJJh3yL33VQJEN2YNI6lrPhrsCpMNBCzSCJfknmzNUzOltOjJbUtnr2dKyvTuwRSfu7jC0ieHsyW7EHlQ3ZHqcs-gWyjQC6_NYBYKz4z5JUsussPZ2QddUFXRIaBGz_BxOSRqfiNf5KMwD4Khs7QS6IGQ_KrRV8RWly53SOQJdS_NHVtlXSvIgaiiCZufotBLNwaTg1xNLUY2DA"/>
</div>
<button class="w-full border border-primary text-primary font-button text-button py-2 hover:bg-primary hover:text-surface-white transition-colors">Cotizar</button>
</div>
</article>
<!-- Data/Material Focus Block (Tubular Roll) -->
<article class="col-span-1 md:col-span-1 lg:col-span-1 row-span-2 bg-primary text-surface-white group flex flex-col relative overflow-hidden">
<img alt="Tubular polyethylene roll macro" class="absolute inset-0 w-full h-full object-cover opacity-40 mix-blend-luminosity group-hover:scale-110 transition-transform duration-1000" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDq9KqoTTzYjjARQ4dbmnV_FDKu8K_EahVRqsOq21P9kz9b94LP4StwX5ZAZZWl0Z0Cx9J-Wg_GuVrZ3NwI9WoDN6OjIh5Ah_YrjrVzbwFhVuWC6LIrtlrZFfv28tSRKC4te02ovM5t9wKOywBlWHwLf6Czrzf27FcFREYL1WbhVmD1Q1yiFAqnb4CzLBAlPcdSLtr1kAZBegq_sKoxRMvbRqyQyWL92OzuSn73jQUJw9vmQwIX8eXg9g"/>
<div class="relative z-10 p-6 flex flex-col h-full">
<div class="bg-surface-white/10 backdrop-blur-md border border-surface-white/20 p-4 mb-6">
<span class="text-tertiary-fixed font-label-caps text-label-caps uppercase tracking-widest block mb-1">Empaque Automático</span>
<span class="text-headline-md font-headline-md text-surface-white block leading-none mb-2">AUT-03</span>
<div class="w-full h-1 bg-surface-white/20 mt-4"><div class="w-2/3 h-full bg-tertiary-fixed"></div></div>
</div>
<h3 class="font-headline-sm text-headline-sm mb-4">Rollo tubular continuo</h3>
<p class="font-body-md text-secondary-fixed opacity-90 mb-6 flex-grow">Película tubular ideal para procesos automatizados. Excelente sellabilidad térmica y resistencia mecánica para líneas de alta velocidad.</p>
<div class="grid grid-cols-2 gap-4 mb-8">
<div class="border-t border-surface-white/20 pt-2">
<span class="block text-xs font-label-caps text-surface-white/60 mb-1">RENDIMIENTO</span>
<span class="block font-bold">Alto</span>
</div>
<div class="border-t border-surface-white/20 pt-2">
<span class="block text-xs font-label-caps text-surface-white/60 mb-1">SELLADO</span>
<span class="block font-bold">Térmico</span>
</div>
</div>
<button class="w-full bg-secondary text-surface-white font-button text-button py-3 hover:bg-secondary-container hover:text-primary transition-colors">Especificaciones</button>
</div>
</article>
<!-- Eco Block (Natural Bags) -->
<article class="col-span-1 md:col-span-1 lg:col-span-1 row-span-1 bg-success-sustainability/10 border border-success-sustainability/30 group flex flex-col p-6 hover:bg-success-sustainability/20 transition-colors">
<div class="flex justify-between items-start mb-4">
<span class="bg-success-sustainability text-primary px-2 py-1 font-label-caps text-[10px] uppercase tracking-widest font-bold">Línea Verde</span>
<span class="material-symbols-outlined text-success-sustainability">eco</span>
</div>
<h3 class="font-headline-sm text-headline-sm text-primary mb-2">Bolsa natural</h3>
<p class="font-body-md text-on-surface-variant flex-grow mb-4">Empaque versátil sin pigmentación, procesos optimizados para menor impacto.</p>
<button class="text-primary font-button text-button underline decoration-2 decoration-success-sustainability hover:text-success-sustainability transition-colors text-left mt-auto">Cotizar ecológica</button>
</article>
<!-- Horizontal Block (Custom Packaging) -->
<article class="col-span-1 md:col-span-2 lg:col-span-2 row-span-1 bg-surface-container-lowest border border-outline-variant flex flex-col md:flex-row group overflow-hidden hover:border-primary transition-colors">
<div class="w-full md:w-2/5 h-48 md:h-full relative overflow-hidden bg-surface-container-low border-r border-outline-variant">
<img alt="Custom printed flexible packaging" class="absolute inset-0 w-full h-full object-cover mix-blend-multiply group-hover:scale-105 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB9UXl2NMNngFBQU4briymZNCftgdAHS6A99ZlyHr3PmoOAovnMCTGeM9OMaoSZb-uhViE6K5izPlmPuR0wWoJOdxnqkAIr9x8osIn_sJCKzPlgkMUzth85aLvGwHYfC3STj_V70y1e8IekYZLE0TbF_XAOq42FZJ3B1lprkyE-m4QqTuvS67zfUol16AN53vS10p2Nq32LRa-hF2hVGIJP4Ow0IBRVuRd6c-ER0ivsvGcX7UDLFq4mAA"/>
<div class="absolute top-4 left-4 bg-surface-white text-primary border border-outline-variant px-2 py-1 font-label-caps text-[10px] uppercase tracking-widest">PER-05</div>
</div>
<div class="w-full md:w-3/5 p-6 flex flex-col justify-center">
<div class="flex items-center gap-3 mb-2">
<h3 class="font-headline-sm text-headline-sm text-primary">Empaques personalizados</h3>
<div class="h-px flex-grow bg-outline-variant"></div>
</div>
<p class="font-body-md text-text-secondary mb-6">Soluciones a medida con impresión flexográfica. Dimensiones, calibres y acabados exactos para su marca.</p>
<div class="flex gap-4">
<button class="border border-primary text-primary font-button text-button px-6 py-2 hover:bg-primary hover:text-surface-white transition-colors">Ver opciones</button>
</div>
</div>
</article>
<!-- Tall Image Focus (Auto Rolls) -->
<article class="col-span-1 md:col-span-1 lg:col-span-1 row-span-2 bg-surface-white border border-outline-variant relative overflow-hidden group">
<div class="absolute inset-0">
<img alt="Automated packaging machinery" class="w-full h-full object-cover opacity-80 group-hover:scale-105 transition-transform duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD7F5Q5zIELtLtN71zQotFnXTp7RD70fwv6DuVvc2HtywAyJ1kWkx5-bcGdvkpveFLqDVV-zqawezIlvCAyQK1IscYvFZHPIMs3pB35J1I9EwmFrzfedQrXW3w6BCVs8sq2h6mnD1KbsM6vDLYQanzHa6tJSy71bvFDQROrO1EUJbLBrnAEywqtgarIPl1BfVETcyBijQQbxEXkLWsRhl2mpp6xNh0dhPRsN1wTEPmT1YQndDaOM7rR5w"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary via-surface-white/20 to-transparent"></div>
</div>
<div class="relative z-10 p-6 flex flex-col h-full justify-end text-surface-white">
<div class="bg-primary/80 backdrop-blur-sm p-4 border border-surface-white/20">
<span class="text-tertiary-fixed font-label-caps text-label-caps uppercase tracking-widest mb-1 block">VFFS / HFFS</span>
<h3 class="font-headline-sm text-headline-sm mb-2">Rollos Automático</h3>
<p class="font-body-md text-surface-white/80 text-sm mb-4">Bobinas de alto rendimiento para envasadoras. Excelente uniformidad.</p>
<button class="w-full bg-surface-white text-primary font-button text-button py-2 hover:bg-secondary hover:text-surface-white transition-colors">Ficha Técnica</button>
</div>
</div>
</article>
<!-- Text Heavy Block (Commercial Bags) -->
<article class="col-span-1 md:col-span-1 lg:col-span-1 row-span-1 bg-surface-container-low border border-outline-variant p-6 flex flex-col">
<span class="text-secondary font-label-caps text-label-caps uppercase tracking-widest mb-4 block border-b border-outline-variant pb-2">Sector Retail</span>
<h3 class="font-headline-sm text-headline-sm text-primary mb-3">Bolsas para comercio</h3>
<p class="font-body-md text-on-surface-variant flex-grow mb-6">Empaque primario y secundario. Opciones robustas y estéticas para proteger el producto.</p>
<a class="flex items-center gap-2 text-secondary font-button text-button hover:gap-4 transition-all" href="#">
<span>Explorar línea retail</span>
<span class="material-symbols-outlined text-sm">arrow_forward</span>
</a>
</article>
<!-- Technical Specs Block (Punched Roll) -->
<article class="col-span-1 md:col-span-1 lg:col-span-1 row-span-1 bg-primary-container text-surface-white p-6 flex flex-col border border-primary">
<div class="flex justify-between items-start mb-6">
<h3 class="font-headline-sm text-headline-sm">Rollo punteado</h3>
<span class="font-mono text-secondary-fixed text-sm">COM-06</span>
</div>
<ul class="font-body-md text-secondary-fixed space-y-3 mb-6 flex-grow border-l-2 border-secondary pl-4">
<li>Pre-corte de precisión</li>
<li>Desprendimiento rápido</li>
<li>Optimización en CEDIS</li>
</ul>
<button class="border border-secondary-fixed text-secondary-fixed font-button text-button py-2 hover:bg-secondary-fixed hover:text-primary transition-colors">Cotizar Bobinas</button>
</article>
</div>
</section>
<!-- Editorial Final CTA Section -->
<section class="bg-primary text-surface-white py-24 relative overflow-hidden">
<div class="absolute inset-0 opacity-10" style="background-image: radial-gradient(#ffffff 1px, transparent 1px); background-size: 24px 24px;"></div>
<div class="max-w-4xl mx-auto px-5 md:px-grid-margin relative z-10 flex flex-col items-center text-center">
<div class="w-16 h-1 bg-secondary mb-8"></div>
<h2 class="font-display-lg-mobile md:font-display-lg text-display-lg-mobile md:text-display-lg mb-6 leading-tight">Desarrollo técnico<br/>a la medida</h2>
<p class="font-body-lg text-body-lg text-secondary-fixed max-w-2xl mb-12">Nuestro equipo de ingeniería de empaque diseña la solución exacta basada en polímeros específicos, calibres, barreras y requerimientos mecánicos de su línea de producción.</p>
<div class="flex flex-col sm:flex-row gap-4">
<button class="bg-secondary text-surface-white font-button text-button px-8 py-4 hover:bg-on-secondary-fixed-variant transition-colors uppercase tracking-wider">Solicitar Asesoría Técnica</button>
<button class="border border-surface-white/30 text-surface-white font-button text-button px-8 py-4 hover:bg-surface-white/10 transition-colors uppercase tracking-wider backdrop-blur-sm">Contactar Ventas B2B</button>
</div>
</div>
</section>
<!-- Footer -->
<footer class="w-full bg-primary-container px-grid-margin py-section-padding flex flex-col md:flex-row justify-between gap-grid-gutter full-width bg-primary-container dark:bg-primary-container flat no shadows relative">
<div class="flex flex-col gap-6">
<span class="text-headline-sm font-headline-sm font-extrabold text-surface-white">PLADEMO</span>
<span class="text-on-primary-container font-body-md text-body-md">© 2024 PLADEMO. Todos los derechos reservados.</span>
</div>
<div class="flex flex-col gap-4">
<a class="text-surface-white font-bold font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200 underline decoration-secondary-container" href="#">Inicio</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Productos</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Mercados</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Nosotros</a>
</div>
<div class="flex flex-col gap-4">
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Contacto</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Bolsa de trabajo</a>
<a class="text-on-primary-container font-normal font-label-caps text-label-caps hover:text-secondary-container transition-colors duration-200" href="#">Aviso de Privacidad</a>
</div>
<!-- Floating WhatsApp Icon conceptual representation within footer bounds for B2B accessibility -->
<div class="absolute bottom-12 right-12 md:bottom-24 md:right-grid-margin">
<button aria-label="Contactar por WhatsApp" class="bg-[#25D366] text-white p-4 rounded-full shadow-lg hover:scale-105 transition-transform flex items-center justify-center">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">chat</span>
</button>
</div>
</footer>
</body></html>
