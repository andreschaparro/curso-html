# Capitulo 1: Introducción

## El archivo index.html

El archivo `index.html` es el punto de entrada a una pagina web. En el mismo, se ingresa código HTML para describir la estructura de la pagina.

1. Crear una carpeta llamada `playground`.
2. Crear un archivo llamado `index.html` dentro de la carpeta `playground`.

## Elementos

El código HTML esta formado por elementos que pueden contener:

- Otros elementos, es decir, se permite el anidamiento de los mismos.
- Texto.

El siguiente elemento, que contiene texto, se muestra con el fin de identificar su estructura semántica:

`<h1 class="titulo">Titulo</h1>`.

Donde vemos que tiene:

- Una etiqueta de apertura `<h1>`.
- Un atributo con un valor `class="titulo"`.
- El texto `Titulo`.
- Una etiqueta de cierre `</h1>`.

## Estructura estándar por elementos anidados

El elemento `<html></html>`, es el elemento raíz de la pagina web.

Donde vemos que tiene:

1. Ingresar `html` dentro del archivo `index.html`.
2. Seleccionar `html:5`.

### Titulo de la pagina web

Dentro del elemento `<head></head>`, va la informacion de la pagina web.

El elemento `<title></title>`, es parte de la informacion de la pagina web.

1. Ingresar `HTML Playground` como el texto del elemento `<title></title>`.

### Contenido de la pagina web

Dentro del elemento `<body></body>`, va el contenido de la pagina web.

1. Ingresar `<h1>Hola Mundo</h1>` dentro del elemento `<body></body>`.

## Usar el Live Server

1. Hacer clic derecho sobre `index.html`.
2. Seleccionar `Open with Live Server`.

![Live Server](live_server.png)
