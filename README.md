Sidebar Responsive - Sebastian Sarmiento

Descripción

Este proyecto consiste en el diseño de un Sidebar/Nav lateral responsivo para un panel administrativo.

El diseño está inspirado en la interfaz de referencia proporcionada, pero se modificaron los colores, el nombre y los iconos para crear una propuesta propia.

El proyecto es únicamente visual, por lo que no contiene funcionalidades de navegación, autenticación, bases de datos ni JavaScript.

Tecnologías utilizadas

HTML5

CSS3

Flexbox

Media Queries

Font Awesome 6

Estructura del proyecto

sidebar-sebastian/
│
├── index.html
├── style.css
└── README.md

index.html

Contiene la estructura HTML del Sidebar:

Logo y nombre de Sebastian Sarmiento.

Menú de navegación.

Iconos de Font Awesome.

Perfil del administrador.

style.css

Contiene todos los estilos visuales y responsive:

Distribución mediante Flexbox.

Colores y fondos.

Estados hover y active.

Diseño responsive para tablet y celular.

Truncamiento de texto con text-overflow: ellipsis.

Diseño responsivo

El Sidebar se adapta según el tamaño de la pantalla.

Escritorio

El Sidebar tiene un ancho de 250px y muestra:

Iconos.

Nombre de cada opción.

Nombre del usuario.

Rol del usuario.

Tablet

A partir de 820px el Sidebar se reduce a 78px.

Se mantienen los iconos y se ocultan los textos para aprovechar mejor el espacio.

Celular

A partir de 480px el Sidebar se reduce a 68px, manteniendo únicamente los elementos esenciales.

Flexbox

El proyecto utiliza Flexbox para organizar los diferentes niveles del Sidebar.

Ejemplo:

.sidebar {
    display: flex;
    flex-direction: column;
}

.navigation {
    display: flex;
    flex-direction: column;
}

.profile {
    display: flex;
    align-items: center;
}

No se utiliza CSS Grid.
