# Capitulo 11: Incrustar contenido externo con iframe

## Video de [Youtube](https://www.youtube.com/)

1. Ir al video del [panda recaliente en la oficina](https://www.youtube.com/watch?v=CX98sH80B5Q).
2. Clic en `Compartir`.
3. Clic en `Incorporar`.
4. Agregar el elemento ```<iframe></iframe>``` que nos da:

```
    <h1>
        Contenido incrustado
    </h1>
    <hr>

    <h2>
        Youtube
    </h2>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/CX98sH80B5Q?si=8beIYWK1Un1B-4dk"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pict
```

## Sonido de [Souncloud](https://soundcloud.com/es)

1. Ir al sonido [Voltage Drop](https://soundcloud.com/es/voltagedrop).
2. Clic en `Share`.
3. Clic en `Embed`.
4. En `Options` seleccionar `#050505`.
5. Agregar el elemento ```<iframe></iframe>``` que nos da:

```
    <h1>
        Contenido incrustado
    </h1>
    <hr>

    <h2>
        Youtube
    </h2>

    <iframe height="200" src="https://www.youtube.com/embed/CX98sH80B5Q?si=8beIYWK1Un1B-4dk"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <h2>
        Souncloud
    </h2>

    <iframe width="100%" height="200" scrolling="no" frameborder="no" allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/116376952&color=%23050505&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true">
    </iframe>
```

## Direccion de [Google Maps](https://www.google.com/maps)

1. Buscar [el palacio de la pizza](https://www.google.com/maps/place/El+Palacio+de+la+Pizza/@-34.6033038,-58.3798694,17z/data=!3m1!4b1!4m6!3m5!1s0x95bccacc2a008c3f:0xf0ccb76a4575b22e!8m2!3d-34.6033082!4d-58.3772945!16s%2Fg%2F1ym82rkrg?entry=ttu).
2. Clic en `Compartir`.
3. Clic en `Incorporar un mapa`.
4. Agregar el elemento ```<iframe></iframe>``` que nos da:

```
    <h1>
        Cotenido incrustado
    </h1>
    <hr>

    <!-- <h2>
        Youtube
    </h2>

    <iframe height="200" src="https://www.youtube.com/embed/CX98sH80B5Q?si=8beIYWK1Un1B-4dk"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <h2>
        Souncloud
    </h2>

    <iframe width="100%" height="200" scrolling="no" frameborder="no" allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/116376952&color=%23050505&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true">
    </iframe> -->

    <h2>
        Google Maps
    </h2>

    <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3284.0339204705515!2d-58.379869425246724!3d-34.60330375747461!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x95bccacc2a008c3f%3A0xf0ccb76a4575b22e!2sEl%20Palacio%20de%20la%20Pizza!5e0!3m2!1ses-419!2sar!4v1720135289092!5m2!1ses-419!2sar"
        width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"></iframe>
```

