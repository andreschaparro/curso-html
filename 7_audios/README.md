# Capitulo 7: Audios

## Video

1. Crear una carpeta llamada `audio` dentro de la carpeta `assets`.
2. Copiar el archivo `audio.mp3` a la carpeta `audio`.
3. Agregar ```<audio src="./assets/audio/audio.mp3" controls muted autoplay></audio>```.

El atributo `controls`, nos da controles parecidos a los de spotify sobre el audio.

El atributo `autplay`, nos permite que el audio se reproduzca automaticamente al abrir la pagina web.

El atributo `muted`, nos permite que el audio se reproduzca sin sonido.

## Source

1. Agregar:

```
<audio controls muted autoplay>
    <source src="./assets/audio/audio.mp3">
    <p>Tu navegador no soporta este formato para poder descargarlo haz clic <a href="./assets/audio/audio.mp3">aqui</a></p>
</audio>
```

El elemento ```<soruce>``` nos permite tener mas ordenado el codigo y mejorar la experiencia de usuario en caso de que el audio no se pueda reproducir.