# La Villa Dulce

Sitio web de repostería artesanal creado para **La Villa Dulce**, una marca dedicada a preparar postres frescos para disfrutar cualquier día o celebrar momentos especiales.

## Descripción

La página presenta una experiencia visual cálida, elegante y llamativa. El hero principal utiliza la imagen de las tartaletas como producto destacado y conduce al usuario hacia el menú de postres.

El diseño combina tonos crema, coral, amarillo y negro, junto con tipografías serif y sans serif para crear una identidad dulce, artesanal y moderna.

## Información comercial

- **Pedidos por WhatsApp:** [0424-2220010](https://wa.me/584242220010)
- **Ubicación:** Ureña, estado Táchira, Venezuela.
- **Horario de atención:** martes a sábados, de 2:00 p. m. a 7:00 p. m.
- **Servicio:** delivery disponible para los pedidos.
- **Redes sociales:** Instagram, Facebook y TikTok.

## Secciones de la página

- **Inicio:** hero principal con el mensaje “Pequeños momentos, grandes antojos” y las tartaletas de la casa.
- **Menú:** catálogo de productos con fotografías, nombres, descripciones breves y precios.
- **Nuestra historia:** presentación del origen y la filosofía de La Villa Dulce.
- **Celebraciones:** sección para promocionar tortas y pedidos personalizados.
- **Contacto:** correo electrónico, WhatsApp para pedidos, ubicación, horario de atención y enlaces a redes sociales.
- **Pie de página:** franja negra compacta con la identidad de la marca, ubicación, horario, delivery, copyright y redes sociales.

## Productos mostrados

El menú utiliza las imágenes disponibles en la carpeta `images/`:

- Tartaletas
- Torta de hojaldre rellena
- Quesillo
- Donas
- Vaso dulcero
- Torta fría
- Torta de quesillo

## Estructura del proyecto

```text
postres-/
├── index.html
├── README.md
├── css/
│   └── style.css
├── images/
│   ├── donas.jpg
│   ├── quesillo.jpg
│   ├── tartaletas.jpg
│   ├── torta de hojaldre rellena.jpg
│   ├── torta frias.jpg
│   ├── torta quesillo.jpg
│   └── vaso dulcero.jpg
└── scripts/
    └── main.js
```

## Características

- Diseño adaptable para computadoras, tabletas y teléfonos móviles.
- Menú hamburguesa funcional en pantallas pequeñas.
- El menú móvil se despliega sin cubrir el texto principal del hero.
- El menú móvil permanece dentro del ancho visible y no genera desplazamiento horizontal.
- Navegación interna mediante enlaces a cada sección.
- Imágenes con textos alternativos para mejorar la accesibilidad.
- Carga diferida en imágenes que aparecen debajo del hero.
- Botones y enlaces para realizar pedidos y contactar con la marca.
- Atención de martes a sábados, de 2:00 de la tarde a 7:00 de la noche.
- Ubicación en Ureña, estado Táchira.
- Servicio de delivery disponible.
- Footer responsive con distribución compacta de la información comercial.
- Enlaces externos a los sitios oficiales de Instagram, Facebook y TikTok.

## Cómo visualizar el proyecto

No requiere instalación de dependencias. Abre `index.html` directamente en el navegador o utiliza la extensión **Live Server** de Visual Studio Code para iniciar una vista local.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Google Fonts: Playfair Display y DM Sans