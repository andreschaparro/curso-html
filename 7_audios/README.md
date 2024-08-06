# Capitulo 7: Audios

## Crear un audio

1. Crear una carpeta llamada `audio` dentro de la carpeta `assets`.
2. Copiar un audio con nombre y formato `audio.mp3` a la carpeta `audio`.
3. Agregar:

```
    <audio controls muted autoplay>
      <source src="./assets/audio/audio.mp3" type="audio/mp3" />
      <p>
        Tu navegador no soporta este formato para poder descargarlo haz clic
        <a href="./assets/audio/audio.mp3">aquí</a>
      </p>
    </audio>
```

- El atributo `controls` nos permite crear controles como los de YouTube para el audio.
- El atributo `autplay` nos permite reproducir el audio automáticamente al abrir la pagina web.
- El atributo `muted` nos permite silenciar el audio automáticamente al abrir la pagina web.
- El atributo `src` nos permite ingresar la ruta del audio.
