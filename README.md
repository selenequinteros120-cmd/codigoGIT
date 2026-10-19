# Proyecto Web - Buscador PokéAPI

## Descripción del Proyecto
Este proyecto es una aplicación web que se conecta con la PokéAPI para consultar y mostrar información detallada de distintos Pokémon en tiempo real. 

La página cuenta con una interfaz intuitiva que permite a los usuarios:
* Buscar cualquier Pokémon ingresando su nombre o su número de ID.
* Explorar Pokémon de forma aleatoria mediante un botón interactivo.
* Visualizar la tarjeta con la imagen, tipo, habilidades y estadísticas del Pokémon seleccionado.

El proyecto está creado de la siguiente forma:

1. HTML5 (`index.html` y `pokemon.html`)
   * index.html: Página de bienvenida e introducción al proyecto.
   * pokemon.htm: Contiene principalmente donde se ubica el buscador y se renderizan las tarjetas de los Pokémon.

2. CSS (estilos.css):
   * Contiene todos los estilos visuales, colores, tipografías y el diseño responsive para adaptar la interfaz a distintas pantallas.

3. JavaScript & PokéAPI:
   * Se utiliza la API Fetch (`fetch`) para realizar peticiones asíncronas HTTP a `https://pokeapi.co/api/v2/pokemon/`.
   * Manipulación dinámica del DOM para actualizar las imágenes, estadísticas y datos sin necesidad de recargar la página.


## Requisitos Técnicos y Git
Estructura de ramas:
  * master / main: Rama principal.
  * rama-estilos: Desarrollo del diseño CSS y maquetación.
  * rama-pokemon: Implementación de la lógica JS y la integración con la API.

Integrantes:
* Selene Quinteros, Maza Tania y Ugarte Susan

Instrucciones de Ejecución
1. Clonar o descargar este repositorio en tu computadora.
2. Abrir el archivo `index.html` en tu navegador web de preferencia.
3. Navegar hacia la sección del buscador (`pokemon.html`) e ingresar el nombre de un Pokémon para probar la aplicación.