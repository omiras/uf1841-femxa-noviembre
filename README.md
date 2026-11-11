# Supuesto práctico UF1841: Huellas Felices

**Duración:** 150 minutos  
**Entrega:** contenido completo de `index.html`, pegado en la respuesta de Moodle.

## Situación

La protectora ficticia **Huellas Felices** necesita una página web para presentar animales y recibir solicitudes de contacto.

Se facilitan:

- Una plantilla mínima `index.html` con algunos estilos iniciales.
- La hoja `formulario.css`, que contiene los estilos visuales del formulario.
- La carpeta `images` con las fotografías y el patrón del footer.
- Dos imágenes orientativas del resultado final.

Todos los textos visibles necesarios ya están colocados dentro del `<body>` de `index.html`. Las rutas de las imágenes, los textos alternativos, los enlaces y la configuración del formulario se detallan en este enunciado. Tu trabajo consiste en organizar el contenido mediante HTML y completar dentro de `<style>` la presentación general de la página.

## Aspecto general solicitado

La página tendrá una cabecera, una sección de animales, una sección de contacto y un pie de página.

### Colores

- Fondo de la cabecera: `#2f6f61`.
- Título **Huellas Felices** y elementos del menú: blanco.
- Títulos **Animales en adopción** y **Contacta con nosotros**: `#24564b`.
- Textos de datos como **Perra mestiza · 4 años**: `#6b5e50`.
- Fondo claro de tarjetas y formulario: `#f7f3ec`.
- Tipografía general: una familia sin serifa.

El título de la web y los elementos del menú deben distinguirse claramente entre sí.

## Estructura de la página

Utiliza al menos cinco etiquetas semánticas HTML5, por ejemplo: `header`, `nav`, `main`, `section`, `article` y `footer`.

### Cabecera

Incluye:

- Título: **Huellas Felices**.
- Enlaces internos: **Inicio**, **Adopciones** y **Contacto**.

### Animales en adopción

Cada animal aparecerá en una tarjeta visualmente separada de las demás. Debe contener nombre, datos, imagen y descripción. El contenido tendrá espacio interior entre el texto y el borde de la tarjeta.

Para presentar las tarjetas:

- Utiliza `background-color: #f7f3ec` como color de fondo.
- Aplica `border: 1px solid #d8cfc2` como borde de cada tarjeta.
- Puedes aplicar `max-width: 250px` a cada tarjeta para limitar su anchura.

**Luna**  
Perra mestiza · 4 años  
Luna es cariñosa, tranquila y disfruta de los paseos. Se lleva bien con otros perros y busca una familia con la que compartir muchos momentos.  
Imagen: `images/luna.png`.  
Texto alternativo: `Luna, perra mestiza de pelo claro en el jardín de la protectora`.

**Milo**  
Gato común europeo · 1 año  
Milo es curioso, juguetón y muy sociable. Le encantan las caricias y observar todo desde un lugar alto.  
Imagen: `images/milo.png`.  
Texto alternativo: `Milo, gato joven de color naranja en el jardín de la protectora`.

**Nala**  
Perra mestiza · 3 años  
Nala es inteligente y activa. Aprende con rapidez, disfruta jugando y necesita un hogar que pueda ofrecerle paseos diarios.  
Imagen: `images/nala.png`.  
Texto alternativo: `Nala, perra negra con una mancha blanca en el pecho`.

**Escarcha**  
Gata común europea · hembra  
Escarcha es una gata de otra protectora y ya fue adoptada. Puedes conocer su historia en la web de Protectora Baix Vinalopó.  
Imagen: `https://protectorabaix.org/imas/animales/_3512/a_35121678310524.jpg`.  
Texto alternativo: `Escarcha, gata común europea de color claro`.  
Ficha: `https://protectorabaix.org/ficha-3512`.

Una parte significativa del texto de Escarcha será un enlace a su ficha. El enlace se abrirá en una pestaña nueva.

Las tarjetas se distribuirán horizontalmente cuando haya espacio. Al reducirse el ancho de la pantalla, cambiarán de fila hasta quedar una debajo de otra.

### Formulario de contacto

La sección tendrá el título **Contacta con nosotros** y el texto:

**¿Quieres adoptar o necesitas más información?**

Construye un formulario con:

| Campo | Configuración |
|---|---|
| Nombre | `name="nombre"`, obligatorio y 60 caracteres como máximo |
| Correo electrónico | `name="correo"`, obligatorio, con formato de correo válido y 254 caracteres como máximo |
| Mensaje | `name="comentario"`, obligatorio y 500 caracteres como máximo |
| Envío | Botón con el texto **Enviar mensaje** |

Cada campo tendrá una etiqueta asociada. El formulario utilizará `method="post"` y el siguiente valor en el atributo `action`:

`https://servicio-contacto.onrender.com/contacto`

### Pie de página

Incluye el texto:

**© 2026 Huellas Felices**

Utiliza `images/animal-pattern-50.png` como imagen de fondo repetida del footer. Configura el tamaño del fondo a `50px 50px` para que la huella se repita por toda la superficie. El texto del copyright debe quedar alineado en el centro del pie de página.

## Referencias visuales

- `referencia-escritorio.png`.
- `referencia-movil.png`.

Las imágenes muestran una aproximación visual. La puntuación se obtiene mediante los resultados concretos descritos en la rúbrica.

