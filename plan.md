Actúa como desarrollador frontend especializado en sitios web estáticos con HTML5 y CSS3.

Necesito mejorar únicamente las páginas de “Productos” y “Detalle de producto” del sitio web de PLADEMO. El sitio está hecho solo con HTML y CSS, por lo tanto no debes usar React, Vite, JSX, Vue, Angular, Node.js ni frameworks de JavaScript.

El objetivo es que la sección de productos deje de verse genérica y se perciba como un catálogo técnico-industrial profesional, claro y enfocado en cotización.

PÁGINA: productos.html

Crear una página de productos con estructura comercial y técnica, no tipo e-commerce.

La página debe incluir:

1. Hero corto de productos

- Título principal:
  “Catálogo técnico de empaques flexibles”
- Texto descriptivo:
  “Soluciones de empaque diseñadas para uso industrial, comercial y operativo, fabricadas con criterios de resistencia, funcionalidad y adaptación a cada necesidad.”
- Botón principal:
  “Solicitar cotización”
- Botón secundario:
  “Ver productos”

2. Introducción breve
   Agregar un bloque antes del catálogo que explique que PLADEMO trabaja productos estándar y soluciones a medida, sin mostrar precios ni carrito de compras.

Texto sugerido:
“Cada producto puede adaptarse según calibre, medida, presentación y volumen requerido. Nuestro equipo revisa las especificaciones de cada cliente para ofrecer una solución funcional y adecuada a su operación.”

3. Grid de productos
   Mostrar únicamente estos productos:

- Rollo Polietileno calibre 600
- Bolsas para basura “Es-Rollo”
- Bolsas Hoteleras
- Soluciones de empaque a medida

No mostrar estos productos:

- Bolsa tipo camiseta
- Bolsa para hielo
- Película termoencogible
- Cubre trajes

Cada card de producto debe incluir:

- Imagen clara y diferente para cada producto.
- Nombre del producto.
- Descripción corta de máximo 2 líneas.
- 3 datos rápidos:
  - Uso principal.
  - Presentación.
  - Aplicación recomendada.
- Botón “Ver ficha técnica”.
- Botón “Cotizar”.

Importante:
No repetir imágenes entre productos. Si no existe imagen específica para “Soluciones de empaque a medida”, usar una imagen de producción, rollos industriales, maquinaria, almacén o materiales personalizados, no una foto repetida de otro producto.

4. Diseño de cards
   Las cards deben verse industriales y profesionales:

- Imagen grande en la parte superior.
- Fondo blanco o verde claro muy suave.
- Bordes limpios.
- Sombra ligera.
- Botones visibles.
- Texto legible.
- Evitar exceso de información técnica dentro de la card.
- La card debe invitar a entrar al detalle, no saturar al usuario.

5. CTA final
   Agregar una sección final:
   Título:
   “¿No encuentras la medida que necesitas?”

Texto:
“Podemos revisar tus requerimientos técnicos y preparar una cotización personalizada según calibre, volumen, medidas y aplicación.”

Botones:

- “Solicitar asesoría técnica”
- “Contactar por WhatsApp”

PÁGINA: detalle-producto.html

Crear una plantilla para la página interna de cada producto.

La página de detalle debe incluir:

1. Encabezado del producto

- Migas de pan:
  Inicio / Productos / Nombre del producto
- Nombre del producto
- Categoría o aplicación
- Descripción comercial breve

Ejemplo:
“Producto diseñado para aplicaciones industriales y comerciales que requieren resistencia, protección y adaptación a distintas condiciones de uso.”

2. Sección principal
   Dividir en dos columnas en desktop:

Columna izquierda:

- Imagen grande del producto.
- Galería pequeña opcional con 2 o 3 imágenes.
- Si no hay más imágenes, mostrar solo una imagen principal limpia.

Columna derecha:

- Nombre del producto.
- Descripción breve.
- Lista de beneficios.
- Botón “Solicitar cotización”.
- Botón “Contactar por WhatsApp”.

3. Datos técnicos
   Crear una sección clara con tarjetas o tabla simple.

Campos recomendados:

- Material.
- Calibre.
- Presentación.
- Medidas disponibles.
- Color.
- Aplicaciones.
- Personalización.
- Volumen de producción.

No inventar datos exactos si no están confirmados. Usar textos generales como:
“Según requerimiento”
“A definir por cotización”
“Disponible bajo solicitud”

4. Usos principales
   Agregar sección con 3 o 4 usos del producto.

Ejemplo para Rollo Polietileno calibre 600:

- Protección de superficies.
- Uso agrícola.
- Cubiertas temporales.
- Separación o aislamiento de áreas.

Ejemplo para Bolsas Hoteleras:

- Manejo de residuos.
- Operación hotelera.
- Limpieza y mantenimiento.
- Áreas de servicio.

5. Formulario de cotización visual
   Agregar formulario estático con campos:

- Nombre
- Empresa
- Teléfono
- Correo
- Producto de interés
- Medida requerida
- Cantidad aproximada
- Mensaje

Botón:
“Enviar solicitud de cotización”

Nota:
El formulario puede quedar visualmente preparado, aunque el envío real se conecte después.

6. Productos relacionados
   Agregar al final una sección:
   “También puede interesarte”

Mostrar 3 cards pequeñas con otros productos vigentes.

No mostrar productos retirados.

ESTILO VISUAL

Usar la identidad de PLADEMO:

Tipografías:

- Lexend para títulos principales.
- Gilroy o una sans serif similar para textos, botones y navegación.

Colores:

- Azul claro: #bbdaea
- Azul marino: #0f2d56
- Verde principal: #007d32
- Verde oscuro: #1a3b23
- Verde claro: #c0f1be
- Blanco: #ffffff
- Gris secundario: #5f6b76

La vista debe sentirse:

- Industrial
- Técnica
- Comercial
- Moderna
- Limpia
- Enfocada en cotización
- No genérica
- No tipo tienda en línea

REGLAS IMPORTANTES

- No usar precios.
- No usar carrito de compras.
- No usar etiquetas como “comprar ahora”.
- No saturar las cards con demasiado texto.
- No repetir imágenes entre productos.
- No mostrar productos retirados.
- No usar capturas de pantalla como imágenes finales.
- Todo debe funcionar solo con HTML y CSS.
- La página debe ser responsive para móvil.
