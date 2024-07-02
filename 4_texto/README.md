# Capitulo 4: Texto

## Parrafo

Es un elemento que se utiliza para mostrar textos largos.

Si no tenemos el texto definitivo, podemos usar el texto `Lorem ipsum` a modo de prueba.

1. Agregar ```<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>```.

## Negrita

1. Agregar ```<p>Texto en <b>negrita</b></p>```.

## Cursiva

1. Agregar ```<p>Texto en <i>cursiva</i></p>```.

## Elementos en linea y en bloque

Un parrafo es un elemento en bloque. Pero negrita y cursiva, son elementos en linea.

Un elemento en bloque, toma todo el ancho posible que puede ocupar. Mientras, que un elemento en linea solo toma el ancho de su contenido.

1. Agregar ```<p style="background-color: turquoise;">Elemento en bloque</p>```.
2. Agregar ```<b style="background-color: magenta;">Elemento en linea</b>```.

Ademas, los elementos en bloque ignoran los saltos de linea que tengan en su texto.

3. Agregar la etiqueta:

```
<p>Lorem ipsum dolor sit amet, 
    consectetur adipiscing elit, 
    sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
    Ut enim ad minim veniam, 
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
    Excepteur sint occaecat cupidatat non proident, 
    sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
```

De modo que agregar saltos de linea, solo sirve para mejorar la legibilidad del codigo.

## HTML semantico

El elemento ```<strong></strong>```, tambien sirve para mostrar el texto en negrita.

El elemento ```<en></en>```, tambien sirve para mostrar el texto en cursiva.

1. Agregar ```<p>Este texto es <strong>importante</strong></p>```.
2. Agregar ```<p>Este texto es <en>enfatico</en></p>```.

Pero ademas, estos elementos son utilizados por los motores de busqueda.

Cuando utilizamos los elementos y atributos que mejoran nuestro posicionamiento en la web, se dice que estamos utilizando HTML semantico. Y es la forma en que debe trabajarse.

## Etiquetas sin cierre

El elemento en linea ```<br>```, permite introducir un salto de linea dentro de un elemento en bloque.

1. Agregar:

```
<p>Lorem ipsum dolor sit amet, <br>
    consectetur adipiscing elit, <br>
    sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <br>
    Ut enim ad minim veniam, <br>
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
    Excepteur sint occaecat cupidatat non proident, <br>
    sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
```

## Titulos

Los titulos tienen jerarquia:

- ```<h1>Titulo Principal</h1>```. Se usa una vez por pagina web.
- ```<h2>Titulo Secundario/h2>```. Se usa para indicar subcategorias dentro de la pagina web.
- ```<h3>Otros titulos</h3>```.
- ```<h4>Otros titulos</h4>```.
- ```<h5>Otros titulos</h5>```.
- ```<h6>Otros titulos</h6>```.

1. Agregar ```h1>Titulo Principal</h1>```.
2. Agregar ```<hr>```.

El elemento en bloque ```<hr>```, permite introducir una linea horizontal de separacion. Se lo suele colocar despues de un elemento```<h1></h1>```.

## Parrafo con saltos de linea y sangria

Es un elemento en bloque.

1. Agregar:

```
<pre>
    linea 1
    linea 2
    linea 3
    linea 4
</pre>
```

## Citas

Es un elemento en linea.

1. Agregar ```<p><q cite="https://www.lanacion.com.ar">Locura es hacer la misma cosa una y otra vez esperando obtener diferentes resultados</q>Albert Einstein</p>```.

El atributo `cite`, nos permite mejorar el posicionamiento de nuestra pagina web en los buscadores

2. Agregar ```<p>En japones la forma de decir que el tiempo todo lo arregla es: <q lang="JA-ja">NANKURUNAISA</q></p>```.

El atributo `lang`, nos permite mejorar el posicionamiento de nuestra pagina web en los buscadores.

## Superindice

Es un elemento en linea.

1. Agregar ```<p>hipotenusa<sup>2</sup> = cateto opuesto<sup>2</sup> + cateto adyacente<sup>2</sup></p>```.

## Subindice

Es un elemento en linea.

1. Agregar ```<p>El agua es: H<sub>2</sub>O</p>```.

## Abreviaturas

Es un elemento en linea.

Nos permite mostrar un mensaje de ayuda cuando el usuario pasa el cursor sobre el texto mostrado en la pagina web.

1. Agregar ```<p>Desde la tierra a la luna hay 384.400 <abbr title="Kilometros">Kms</abbr></p>```.

El atributo `title`, nos permite definir el mensaje de ayuda para mejorar la experiencia de usuario.

## Enlace

Es un elemento en linea.

1. Agregar ```<a href="https://www.google.com" target="_blank">Haz clic aqui para ir a google</a>```.

El atributo `target="_blank"`, nos permite abrir el enlace en una pestaña. Esto es util para que nuestra pagina no se cierre.

2. Agregar la etiqueta ```<a href="mailto:chaparroandres87@gmail.com">Enviar mail</a>```.
3. Agregar la etiqueta ```<a href="tel:+591155554444">Llamar por telefono</a>```.