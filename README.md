# PLADEMO - Sitio Web Estático

Este repositorio contiene el código fuente del sitio web de **PLADEMO**, una solución de empaques flexibles de alta ingeniería. El sitio ha sido optimizado y reestructurado técnica y visualmente para garantizar un rendimiento óptimo, seguridad y facilidad de publicación en cPanel.

---

## 🛠️ Tecnologías y Arquitectura

*   **HTML5 Semántico**: Estructura limpia y accesible de las páginas.
*   **CSS / Tailwind CDN**: Estilos gestionados dinámicamente mediante la CDN oficial de Tailwind CSS. No requiere compilación local ni dependencias de Node.js.
*   **JavaScript Vanilla (ES6)**: Lógica interactiva en cliente (menús móviles, sliders, cargador dinámico de artículos).
*   **Apache .htaccess**: Reglas de servidor para forzar HTTPS, configurar caché del navegador (WPO), compresión GZIP, prevenir Hotlinking y bloquear acceso a archivos sensibles.

---

## 📂 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```text
plademo/
├── backup/                        # Carpeta limpia y lista para subir a cPanel (Producción)
│   ├── assets/                    # Recursos de producción optimizados
│   │   ├── css/                   # Carpeta para CSS futuro
│   │   ├── js/                    # Carpeta para JS futuro
│   │   ├── icons/                 # Iconos en formato (.webp)
│   │   ├── img/                   # Subcarpetas organizadas por sección:
│   │   │   ├── home/
│   │   │   ├── productos/
│   │   │   ├── mercados/
│   │   │   ├── nosotros/
│   │   │   └── generales/         # Recursos transversales (ej: planta hero)
│   │   ├── logos/                 # Logotipos autorizados
│   │   ├── videos/                # Videos corporativos en uso
│   │   └── favicon.ico            # Favicon del sitio
│   ├── blog_articulos/            # Artículos individuales del blog
│   │   └── articulos.js           # Listado de variables para renderizado dinámico
│   ├── .htaccess                  # Configuración Apache de producción
│   └── [páginas].html             # Archivos HTML estáticos
│
├── _backup_pre_limpieza/          # Respaldo completo previo a la optimización (No publicar)
├── _assets_no_usados_revision/    # Archivos descartados durante la limpieza (No publicar)
├── _backup_no_publicar/           # Carpetas antiguas de desarrollo (No publicar)
├── blog_articulos/                # Carpeta de desarrollo del blog
├── assets/                        # Carpeta de desarrollo de assets
└── README.md                      # Este archivo de documentación
```

---

## ✍️ Cómo Administrar el Blog

El blog funciona de forma semi-dinámica a través de variables en JavaScript, evitando la necesidad de bases de datos.

### Para agregar un artículo nuevo:
1.  **Crear el archivo del artículo**: Crea un archivo HTML para tu artículo dentro de la carpeta `blog_articulos/` (tanto en la raíz como en `backup/blog_articulos/`). Ejemplo: `blog_articulos/tendencias-empaque-2026.html`.
2.  **Registrar la variable**: Abre el archivo `blog_articulos/articulos.js` y añade un objeto al principio del arreglo `ARTICULOS` con la siguiente estructura:

```javascript
const ARTICULOS = [
    {
        id: "tendencias-empaque-2026",
        title: "Tendencias de empaque flexible para 2026",
        excerpt: "Análisis técnico de las nuevas regulaciones y materiales biodegradables en la industria.",
        date: "14 de Agosto, 2026",
        image: "assets/img/nosotros/1.png", // Imagen del artículo
        category: "Industria",
        url: "blog_articulos/tendencias-empaque-2026.html"
    }
    // ... artículos anteriores
];
```

*Nota: Si el arreglo `const ARTICULOS = [];` se mantiene vacío, el sitio mostrará automáticamente una sección estética con el mensaje **"Próximamente más artículos"**.*

---

## 🚀 Guía de Publicación en cPanel

Para publicar o actualizar el sitio web en cPanel:

1.  **Utiliza el contenido de la carpeta `backup/`**: Este directorio contiene únicamente los archivos limpios y necesarios para el sitio de producción.
2.  **Sube los archivos**:
    *   Ingresa al Administrador de Archivos de tu cPanel.
    *   Ve a la carpeta raíz de publicación (habitualmente `public_html/`).
    *   Sube el contenido completo de la carpeta `backup/` (incluyendo la carpeta `assets/`, `blog_articulos/` y el archivo `.htaccess`).
3.  **No subir**: Evita subir las carpetas de respaldo como `_backup_pre_limpieza`, `_assets_no_usados_revision`, `_backup_no_publicar` o archivos de configuración local como `.git`.

---

## 🎨 Ajustes Visuales Clave Realizados

*   **Evitar Flash Blanco**: Se configuró la propiedad `background-color: #0f2d56` inline en el `<head>` de todas las páginas de forma que las transiciones de página (`.fade-in-page`) ocurran sobre un lienzo oscuro homogéneo.
*   **Alineación Header-Hero**: Se estableció el padding superior del body en `index.html` a `pt-[70px]` para que coincida milimétricamente con la altura de la barra de navegación fixed y no se filtre la línea blanca de fondo.
*   **Preload de Imágenes**: Se pre-carga la imagen pesada del hero (`hero-planta.webp`) en las cabeceras HTML para acelerar el renderizado del primer viewport y evitar desplazamientos de layout.
