# Capitulo 2: Head

## Metadatos

El metadato `charset`, se utiliza para indicar el juego de caracteres que tendra la pagina web.

El resto de los metadatos, tienen el siguiente formato: ```<meta name="nombre" content="valor" http-equiv="cabecera-http" schema="esquema">```.

Por ejemplo, el siguiente metadato se utiliza para darle responsividad a la pagina web:

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

La responsividad, implica que la pagina web se vea de forma correcta tanto en una PC como en un dispositivo movil.

1. Agregar ```<meta name="author" content="valor">```.
2. Reemplazar `valor` con nuestro nombre.
3. Agregar ```<meta name="description" content="Este es mi Playground para HTML">```.

El metadato ```<meta name="keywords" content="curso,html">``` lo utilizan los buscadores para poder encontrar nuestra pagina web. El `content`, se compone de varias palabras separadas por coma.

## link

Se utiliza para agregar hojas de estilos CSS.

1. Agregar ```<link rel="stylesheet" href="style.css">```.
2. Crear un archivo llamado `style.css` dentro de la carpeta `playground`.

## favicon

Es el icono  que va a mostrar el navegador en la pestaña donde tengamos abierta nuestra pagina web.

1. Descargar un icono de HTML de [ICONS8](https://icons8.com/).
2. Guardarlo dentro de la carpeta `playground`.
3. Renombrar el archivo del icono a `favicon.ico`.
4. Agregar ```<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">```.