# Capitulo 8: Listas

## Lista desordenada

1. Agregar:

```
<h1>
    Lista del supermercado:
</h1>

<hr>

<ul>
    <li>Cafe</li>
    <li>Azucar</li>
    <li>Canela</li>
    <li>Vainilla</li>
</ul>
```

El elemento ```<ul></ul>``` representa la lista desordenada. Luego, cada elemento ```<li></li>``` es un item de la lista desordenada.

## Lista ordenada

1. Agregar:

```
<h1>
    Lista del actividades que vamos a hacer hoy:
</h1>

<hr>

<ol>
    <li>Lavarse los dientes</li>
    <li>Ir a hacer las compras</li>
    <li>Cocina</li>
    <li>Comer</li>
    <li>Estudiar el curso de HTML</li>
    <li>Dormir</li>
</ol>
```

El elemento ```<ol></ol>``` representa la lista ordenada. Luego, cada elemento ```<li></li>``` es un item de la lista ordenada.

## Listas anidadas

1. Agregar:

```
<h1>
    Lista del actividades que vamos a hacer hoy:
</h1>

<hr>

<ol start="6" type="a" reversed>
    <li>Lavarse los dientes</li>
    <li>Ir a hacer las compras
        <ul>
            <li>Cafe</li>
            <li>Azucar</li>
            <li>Canela</li>
            <li>Vainilla</li>
        </ul>
    </li>
    <li>Cocina</li>
    <li>Comer</li>
    <li>Estudiar el curso de HTML</li>
    <li>Dormir</li>
</ol>
```

Con el atributo `start`, podemos hacer que la numeracion de una lista ordenada no empiece desde `1`.

Con el atributo `type`, podemos hacer que utilice letras en vez de numeros en una lista ordenada.

Con el atributo `reversed`, podemos hacer que enumere de forma descendente en una lista ordenada.