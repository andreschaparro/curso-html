# Capitulo 1: Introduccion

## index.html

Por convencion, los navegadores van a buscar un archivo llamado `index.html` como punto de ingreso a una pagina web.

1. Crear una carpeta llamada `playground`.
2. Crear un archivo llamado `index.html` dentro de la carpeta `playground`.

Dentro de `index.html`, vamos a colocar nuestro codigo HTML. El mismo, va a describir la estructura de nuestra pagina web.

## Elementos

HTML es un lenguje de elementos. Donde cada cada elemento puede contener a otros elementos o texto. Esto se conoce como anidamiento.

Por ejemplo, un elemento podria ser: ```<h1 class="titulo">Titulo</h1>```. Cuyos componentes son:

- Etiqueta de apertura ```<h1>```.
- Atributo `class="titulo"`.
- Texto `Titulo`.
- Etiqueta de cierre ```</h1>```.

## Estructura estandar

El elemento ```<html></html>```, es el elemento raiz de la pagina web.

1. Ingresar `html` dentro del archivo `index.html`.
2. Seleccionar `html:5`.

### Titulo de la pagina web

Dentro del elemento ```<head></head>```, va la informacion de la pagina web. 

El elemento ```<title></title>```, es parte de la informacion de la pagina web.

1. Ingresar `HTML Playground` como el texto del elemento ```<title></title>```.

### Contenido de la pagina web

Dentro del elemento ```<body></body>```, va el contenido de la pagina web.

1. Ingresar ```<h1>Hola Mundo</h1>``` dentro del elemento ```<body></body>```.

## Usar el Live Server

1. Hacer clic derecho sobre `index.html`.
2. Seleccionar `Open with Live Server`.

![Live Server](live_server.png)