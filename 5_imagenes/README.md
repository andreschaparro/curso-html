# Capitulo 5: Imágenes

## Crear la carpeta assets

1. Crear una carpeta llamada `assets` dentro de la carpeta `playground`.
2. Crear una carpeta llamada `img` dentro de la carpeta `assets`.
3. Copiar el archivo `imagen.png` a la carpeta `img`.

La carpeta `assets` va a contener los archivos estáticos. Como por ejemplo, las imágenes.

## Crear una imagen

1. Agregar:

```
    <img
      src="./assets/img/imagen.png"
      alt="Panda recaliente porque se rompe el código"
      height="300px"
    />
```

- El atributo `src` nos permite ingresar la ruta de la imagen.
- El atributo `alt` nos permite mostrar un texto como alternativa a la imagen. El mismo, se muestra si hubo un error al cargarla.
- El atributo `width` nos permite definir el ancho de la imagen en `px`.
- El atributo `height` nos permite definir el alto de la imagen en `px`.

**NOTA: No utilizar `width` y `height` al mismo tiempo porque se deforma la imagen.**

## Crear un imagen que sea un enlace

1. Agregar:

```
    <a href="https://www.google.com" target="_blank"
      ><img
        src="./assets/img/imagen.png"
        alt="Panda recaliente porque se rompe el código"
        height="300px"
    /></a>
```
