Actúa como desarrollador frontend y auditor técnico del proyecto PLADEMO.

Objetivo:
Antes de subir el sitio a cPanel, necesito limpiar y organizar el proyecto actual en HTML, CSS y JavaScript, especialmente las imágenes y carpetas de assets. No migres el proyecto a React, Vite, JSX ni uses estructura tipo src/components/App.jsx. Mantén la estructura estática actual.

Contexto:
El sitio de PLADEMO ya fue validado visual y técnicamente. Ahora se necesita preparar el proyecto para subirlo a cPanel de forma limpia, evitando carpetas innecesarias, imágenes duplicadas, assets sin uso y archivos de respaldo que no deban publicarse.

Tarea principal:
Revisa todo el proyecto archivo por archivo para identificar exactamente qué imágenes, íconos, logos, videos, fuentes y assets están siendo llamados desde el código. Después organiza únicamente los assets usados dentro de una carpeta central llamada assets, actualiza las rutas en todos los archivos y valida que el sitio siga funcionando visualmente.

Instrucciones obligatorias:

1. No migrar tecnología

- No convertir el proyecto a React.
- No usar Vite.
- No crear src, components, pages, hooks, services, App.jsx ni main.jsx.
- Mantener HTML, CSS y JS estático.

2. Hacer respaldo antes de modificar
   Antes de mover, renombrar o eliminar archivos:

- Crear una carpeta llamada \_backup_pre_limpieza.
- Guardar ahí una copia del estado actual del proyecto.
- No borrar nada hasta terminar el análisis completo.

3. Analizar todos los archivos del proyecto
   Revisar archivo por archivo:

- .html
- .css
- .js
- archivos de configuración si existen
- cualquier archivo donde se llamen imágenes, fuentes, íconos, videos o assets

Buscar referencias en:

- src=""
- href=""
- url(...)
- data-src
- background-image
- preload
- scripts dinámicos de JavaScript
- rutas relativas
- rutas absolutas internas
- imágenes usadas en sliders, cards, galerías, productos, hero, favicon, logos y formularios

4. Crear inventario de assets usados
   Generar un inventario con esta estructura:

Archivo donde se usa | Asset detectado | Ruta actual | Tipo | Nueva ruta propuesta | Estado

Tipos:

- Imagen
- Logo
- Ícono
- Fuente
- Video
- CSS
- JS
- Otro

Estados:

- Usado
- Duplicado
- No encontrado
- Pendiente de validar
- No usado

5. Organizar carpeta assets
   Centralizar los archivos usados en esta estructura:

assets/
├── img/
│ ├── home/
│ ├── productos/
│ ├── mercados/
│ ├── blog/
│ ├── nosotros/
│ └── generales/
├── icons/
├── logos/
├── videos/
├── fonts/
├── css/
└── js/

Criterios:

- Imágenes de productos dentro de assets/img/productos/
- Imágenes del home dentro de assets/img/home/
- Imágenes de mercados dentro de assets/img/mercados/
- Logos dentro de assets/logos/
- Íconos dentro de assets/icons/
- Videos dentro de assets/videos/
- CSS dentro de assets/css/
- JS dentro de assets/js/

6. Actualizar rutas
   Después de mover archivos usados:

- Actualizar todas las rutas en HTML, CSS y JS.
- Verificar rutas relativas correctamente.
- Evitar rutas rotas.
- No dejar referencias apuntando a carpetas antiguas.
- No cambiar contenido, textos ni diseño salvo que sea necesario para corregir rutas.

7. Manejo de imágenes no usadas
   No borrar directamente al inicio.

Primero:

- Identificar imágenes que no aparecen referenciadas en ningún archivo.
- Moverlas a una carpeta llamada \_assets_no_usados_revision.
- Confirmar que no se llaman desde código, CSS, JS, sliders o formularios.
- Si después de validar no afectan la parte visual, dejarlas marcadas como candidatas a borrar.

No eliminar:

- favicon.
- logos.
- imágenes usadas por CSS.
- imágenes usadas por JavaScript.
- imágenes de carga diferida.
- imágenes que se usen en sliders aunque no aparezcan directamente en HTML.
- archivos necesarios para responsive o versiones móviles.

8. Revisar carpetas backup
   Identificar carpetas como:

- backup
- backups
- old
- anterior
- respaldo
- copia
- unused
- assets-old
- img-old

Para cada una:

- Revisar si algún archivo dentro de esas carpetas se está llamando desde el código.
- Si no se usa nada, mover la carpeta a \_backup_no_publicar.
- No incluir esas carpetas en la versión final para cPanel.
- No borrar sin reportar primero.

9. Validación visual obligatoria
   Después de reorganizar:

- Abrir el sitio en escritorio.
- Abrir el sitio en móvil/responsive.
- Revisar Home.
- Revisar Productos.
- Revisar Detalle de producto.
- Revisar Mercados.
- Revisar Blog.
- Revisar Nosotros.
- Revisar Contacto.
- Revisar Bolsa de trabajo.

Confirmar:

- No hay imágenes rotas.
- No hay íconos faltantes.
- No hay fondos perdidos.
- No hay sliders dañados.
- No hay estilos perdidos.
- No hay errores en consola relacionados con rutas.
- Los formularios siguen funcionando visualmente.
- El botón “Cargar en formulario” sigue funcionando.

10. Preparar versión lista para cPanel
    Crear una carpeta final llamada:

plademo_cpanel_ready/

Dentro debe quedar solo lo necesario para publicar:

plademo_cpanel_ready/
├── index.html
├── productos.html
├── detalle-producto.html
├── mercados.html
├── blog.html
├── nosotros.html
├── contacto.html
├── bolsa-trabajo.html
├── aviso-privacidad.html
├── assets/
└── otros archivos realmente necesarios

No incluir:

- carpetas backup
- archivos duplicados
- imágenes no usadas
- capturas de prueba
- documentos internos
- archivos de diseño no usados
- carpetas antiguas
- archivos de desarrollo que no se ocupen en producción

11. Reporte final obligatorio
    Al terminar, entrega un reporte con:

A. Resumen general

- Qué se limpió.
- Qué se movió.
- Qué se mantuvo.
- Qué quedó pendiente.

B. Assets usados
Tabla con:

- Archivo
- Ruta nueva
- Dónde se usa
- Tipo

C. Assets no usados
Tabla con:

- Archivo
- Ruta original
- Motivo por el que se considera no usado
- Acción realizada: movido a \_assets_no_usados_revision o \_backup_no_publicar

D. Archivos modificados
Lista de archivos donde se actualizaron rutas.

E. Validación visual
Indicar:

- Páginas revisadas.
- Resultado en escritorio.
- Resultado en móvil.
- Errores encontrados.
- Errores corregidos.

F. Pendientes
Marcar solo lo que no se pudo confirmar, usando:
[PENDIENTE DE VALIDAR]

Regla importante:
No elimines definitivamente ningún archivo hasta entregar el reporte. Primero mueve lo no usado a carpeta de revisión. Después de que yo valide el reporte, se podrá borrar lo innecesario.
