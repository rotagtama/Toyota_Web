# Toyota_Web

[![HTML](https://img.shields.io/badge/HTML-56.9%25-orange)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-43.1%25-blue)](https://developer.mozilla.org/es/docs/Web/CSS)
[![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)](https://github.com/rotagtama/Toyota_Web)

Propuesta de rediseño del sitio web de Toyota, desarrollada como proyecto de maquetacion web con HTML y CSS puro. El sitio presenta informacion sobre modelos, novedades y contacto, manteniendo la estetica y la identidad visual de la marca.

## Vista previa

(Puedes anadir aqui una captura de pantalla de tu sitio)

## Demo

Puedes ver el sitio en funcionamiento aqui:  
https://rotagtama.github.io/Toyota_Web

(Activa GitHub Pages en los ajustes de tu repositorio para que este enlace funcione)

## Estructura del proyecto
Toyota_Web/
│
├── index.html # Pagina de inicio /n
├── modelos.html # Catalogo de vehiculos
├── novedades.html # Noticias y lanzamientos
├── contacto.html # Formulario de contacto
├── toyota.html # Pagina institucional (historia/marca)
├── style.css # Hoja de estilos principal (global)
│
├── estilos/
│ ├── estilos-modelos.css # Estilos especificos para la pagina de modelos
│ ├── estilos-contacto.css # Estilos especificos para el formulario de contacto
│ └── estilos-novedades.css # Estilos especificos para la seccion de novedades
│
├── font/ # Fuentes tipograficas personalizadas
│ └── toyota-font.woff2
│
└── img/ # Imagenes del sitio
├── └── modelos #imagenes de los autos
├── └── iconos-formulario #iconos para los formularios de la web

## Tecnologias utilizadas

- HTML5 - Estructura semantica
- CSS3 - Estilos y responsive design
- Git y GitHub - Control de versiones

## Caracteristicas

- Diseño responsive (adaptado a moviles, tablets y escritorio)
- Navegacion entre 5 paginas
- Tipografias personalizadas
- Formulario de contacto maquetado
- Galeria de modelos estructurada
- Codigo 100% estatico (sin frameworks)

## Responsive design

El sitio se adapta a los siguientes puntos de corte:

| Dispositivo | Anchura maxima | Ajustes aplicados |
|-------------|----------------|-------------------|
| Movil       | 480px          | Fuente reducida, espaciado compacto |
| Tablet      | 768px          | Menu en columna, grid a 1 columna |
| Escritorio  | > 768px        | Grid de 3 columnas, layout completo |

## Instalacion y uso local

1. Clona el repositorio:
   git clone https://github.com/rotagtama/Toyota_Web.git

2. Accede a la carpeta del proyecto:
  cd Toyota_Web

3. Abre index.html en tu navegador preferido.

No se requieren dependencias ni servidor local.


Autores
-Robinson Tamayo - @rotagtama
-Sara Cardena Carpio - @SaraCardena
