# Capitulo 5: Imagenes

## Imagen

1. Agregar ```<img src="imagen.png" alt="panda recaliente en la oficina" height="300px">```.

El atributo `src`, nos permite ingresar la ruta de la imagen.

El atributo `alt`, nos permite mostrar un texto que describa a la imagen. El mismo, se muestra si fallo la carga de la imagen o si la pagina accedida por un lector para personas con discapacidad visual.

El atributo `width`, nos permite definir el ancho en `px`.

El atributo `height`, nos permite definir el alto en `px`.

No conviene utilizar `width` y `height` al mismo tiempo porque va a deformar la imagen.

## Carpeta assets

Es la carpeta que va a contener archivos estaticos, y entre ellos, las imagenes.

1. Crear una carpeta llamada `assets` dentro de la carpeta `playground`.
2. Crear una carpeta llamada `img` dentro de la carpeta `assets`.
3. Copiar el archivo `imagen.png` a la carpeta `img`.
4. Agregar ```<img src="./assets/img/imagen.png" alt="panda recaliente en la oficina" height="300px">```.

## Enlace

1. Agregar:

```
<a href="https://www.google.com" target="_blank">
    <img src="./assets/img/imagen.png" alt="panda recaliente en la oficina" height="300px">
</a>
```