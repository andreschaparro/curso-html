# Capitulo 6: Videos

## Video

1. Crear una carpeta llamada `video` dentro de la carpeta `assets`.
2. Copiar el archivo `video.mp4` a la carpeta `video`.
3. Agregar ```<video src="./assets/video/video.mp4" controls autoplay muted width="500px"></video>```.

El atributo `autplay`, nos permite que el video se reproduzca automaticamente al abrir la pagina web.

El atributo `muted`, nos permite que el video se reproduzca sin sonido.

El atributo `width`, nos permite definir el ancho en `px`.

El atributo `controls`, nos da controles parecidos a los de youtube sobre el video.

## Source

1. Agregar:

```
<video controls muted width="500px" poster="./assets/img/imagen.png">
    <source src="./assets/video/video.mp4" type="video/mp4">
    <p>Tu navegador no soporta este formato para poder descargarlo haz clic <a href="./assets/video/video.mp4">aqui</a></p>
</video>
```

El atributo `poster`, nos permite mostrar una imagen antes de iniciar la reproduccion del video.

El elemento ```<soruce>``` nos permite tener mas ordenado el codigo y mejorar la experiencia de usuario en caso de que el video no se pueda reproducir.

## Comentarios

El navegador ignora las linea comentadas y los comentarios son multilinea.

1. Reemplazar de la linea ```<video src="./assets/video/video.mp4" controls autoplay muted width="500px"></video>``` por ```<!-- <video src="./assets/video/video.mp4" controls autoplay muted width="500px" ></video> -->```.