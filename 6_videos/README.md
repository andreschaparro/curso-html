# Capitulo 6: Videos

## Crear un video con auto-play

1. Crear una carpeta llamada `video` dentro de la carpeta `assets`.
2. Copiar un video con el nombre y extension `video.mp4` a la carpeta `video`.
3. Agregar:

```
    <video
      src="./assets/video/video.mp4"
      controls
      autoplay
      muted
      width="500px"
    ></video>
```

- El atributo `src` nos permite ingresar la ruta del video.
- El atributo `controls` nos permite crear controles como los de YouTube sobre el video.
- El atributo `autplay` nos permite reproducir el video automáticamente al abrir la pagina web.
- El atributo `muted` nos permite quitar el sonido del video automáticamente al abrir la pagina web.
- El atributo `width` nos permite definir el ancho del video en `px`.

## Crear un video sin auto-play

1. Agregar:

```
    <video controls muted width="500px" poster="./assets/img/imagen.png">
      <source src="./assets/video/video.mp4" type="video/mp4" />
      <p>
        Tu navegador no soporta este formato para poder descargarlo haz clic
        <a href="./assets/video/video.mp4">aquí</a>
      </p>
    </video>
```

- El atributo `poster` nos permite mostrar una imagen antes de reproducir el video.

Agregar un elemento `<source />` es una buena practica para mejora la legibilidad del código.
