# FJL Licores

Landing page estática para **FJL Licores**, una marca de licores artesanales de
Balcarce. El sitio presenta la colección de productos, comunica el origen
artesanal de la marca y ofrece sus canales de contacto.

## Características

- Encabezado con el nombre de la marca, logotipo y ubicación.
- Presentación de tres productos:
  - Limoncello tradicional.
  - Licor de chocolate.
  - Cisne Negro.
- Sección institucional sobre la elaboración artesanal.
- Enlaces de contacto a Instagram y WhatsApp.
- Diseño responsive:
  - En pantallas grandes, los productos se muestran en una grilla.
  - En dispositivos móviles, las tarjetas se apilan y se simplifican sus
    descripciones.

## Tecnologías

- HTML5.
- CSS3.
- SVG inline para los íconos de contacto.
- No requiere JavaScript, frameworks ni dependencias externas.

## Estructura del proyecto

```text
.
├── index.html                 # Página principal
├── css/
│   └── style.css              # Estilos, variables visuales y responsive
└── assets/
    └── img/
        ├── licors/            # Imágenes de los productos
        └── logos/             # Logotipos de FJL Licores
```

## Ejecución local

Enlace a la pagina: https://nahulamorte.github.io/fjl-landing-page/

## Personalización

- Editar los textos, productos y datos de contacto en `index.html`.
- Reemplazar las imágenes dentro de `assets/img/` y actualizar sus rutas en
  `index.html` si cambian los nombres de archivo.
- Modificar la paleta, tipografías, espaciados y radios desde las variables
  definidas en `css/style.css`.
- Ajustar el comportamiento para móviles en el bloque
  `@media (max-width: 768px)` de `css/style.css`.

## Contacto

- Instagram: [@fjl_licores](https://www.instagram.com/fjl_licores/)
- WhatsApp: 2266 470084
