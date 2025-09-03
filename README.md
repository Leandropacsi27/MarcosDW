URL: https://leandropacsi27.github.io/MarcosDW/

📌 Clases de Bootstrap en tu código
General de estructura

container → Contenedor con ancho máximo adaptativo (centra y da márgenes laterales).

row → Fila de la grilla Bootstrap (flexbox row).

col-md-4 / col-md-3 / col-md-6 / col-lg-6 / col-12 → Columnas que cambian su ancho según el tamaño de pantalla (md, lg, col-12 = ancho completo en móviles).

g-4 / gy-4 → Gutter (espacio entre columnas). g = en ambos ejes, gy = solo vertical.

mb-2 / mb-3 / mb-4 / mb-0 → Margin bottom con distintos tamaños.

mt-5 / pt-4 / py-5 / py-3 → Márgenes y paddings top/vertical.

mx-auto → Márgen horizontal automático (centra elementos).

gap-2 / gap-3 → Espaciado entre elementos flex/grid.

Navbar

navbar → Barra de navegación básica.

navbar-expand-lg → Navbar expandida desde pantallas grandes (lg) hacia arriba; colapsa en móviles.

sticky-top → Fija la navbar arriba al hacer scroll.

navbar-brand → Estilo para logo/nombre de la marca.

navbar-toggler → Botón hamburguesa en vista móvil.

navbar-toggler-icon → Icono del botón hamburguesa.

collapse navbar-collapse → Contenedor del menú colapsable.

navbar-nav → Lista de navegación (horizontal).

nav-item → Item de navegación.

nav-link → Enlaces de navegación.

border-0 → Elimina bordes del toggler button.

d-flex → Convierte en flex container.

d-inline-block → Comportamiento inline pero como bloque (útil en links).

Botones

btn → Clase base para botones.

btn-lg → Botón más grande.

rounded-pill → Bordes redondeados estilo píldora.

rounded-circle → Botón redondeado en círculo.

position-fixed → Posición fija en pantalla.

position-absolute → Posiciona relativo al contenedor.

fw-bold → Fuente en negrita fuerte.

Carousel

carousel slide → Activa el componente carrusel con animación.

carousel-inner → Contenedor de los ítems.

carousel-item → Cada diapositiva del carrusel.

active → Marca el ítem inicial activo.

carousel-control-prev / carousel-control-next → Botones de navegación.

carousel-control-prev-icon / carousel-control-next-icon → Iconos de navegación.

Cards (Especialidades)

card → Componente card básico.

card-body → Contenedor del contenido de la card.

card-title → Título dentro de la card.

h-100 → Altura al 100% del contenedor padre.

Imágenes y relaciones

ratio ratio-4x3 → Mantiene proporción 4:3 en el contenedor (útil para imágenes/videos).

ratio ratio-16x9 → Mantiene proporción 16:9 (ej: iframe de Google Maps).

img-fluid (implícito en Bootstrap) → Hace que la imagen se ajuste al contenedor. (no lo pusiste explícito, pero tu CSS usa el mismo principio)

Formulario

row g-3 → Fila con espacio (g-3) entre columnas del formulario.

col-md-6 / col-12 → Campos que ocupan media fila o toda según tamaño.

form-label → Estilo para las etiquetas <label>.

form-control → Input estilizado.

form-select → Select estilizado.

textarea.form-control → Área de texto estilizada.

Footer

list-unstyled → Quita los estilos de lista (ul/li).

border-secondary-subtle → Borde con tono gris claro.

text-center → Texto centrado.

text-decoration-none → Quita el subrayado de los enlaces.

social (personalizada) → No es de Bootstrap, es tuya.

Texto y tipografía

fw-bold → Texto en negrita.

fw-800 (personalizada en tu CSS) → Estilo extra bold.

text-uppercase → Convierte texto a mayúsculas.

text-white → Texto blanco.

text-decoration-none → Quita el subrayado de links.

Utilidades varias

d-flex → Contenedor flexbox.

align-items-center / justify-content-center → Alineación vertical/horizontal con flex.

opacity-0.9 (con :hover a 1) → No es de Bootstrap, lo pusiste en tu CSS.

aria-* → Atributos de accesibilidad (no clases, pero útiles).

👉 En resumen, usaste:

Estructura: container, row, col-*, g-*, py-*, mb-*.

Navbar: navbar, navbar-expand-lg, nav-item, nav-link, collapse, navbar-toggler.

Botones: btn, btn-lg, rounded-pill, rounded-circle.

Carousel: carousel-*.

Cards: card, card-body, card-title.

Formularios: form-control, form-select, form-label.

Footer: list-unstyled, text-center, border-*.

Utilidades: d-flex, justify-content-center, fw-bold, text-uppercase.
