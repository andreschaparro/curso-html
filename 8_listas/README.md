# Capitulo 8: Listas

## Crear una lista desordenada

1. Agregar:

```
    <h2>Lista del supermercado</h2>

    <ul>
      <li>Cafe</li>
      <li>Azúcar</li>
      <li>Turrones</li>
      <li>Galletas</li>
    </ul>
```

- El elemento `<ul></ul>` nos permite crear la lista desordenada.
- Los elementos `<li></li>` nos permiten agregar items a la lista desordenada.

## Crear una lista ordenada

1. Agregar:

```
    <h2>Lista de las actividades que vamos a hacer hoy</h2>

    <ol>
      <li>Lavarme los dientes</li>
      <li>Bañarme</li>
      <li>Ir a hacer las compras</li>
      <li>Cocinar</li>
      <li>Comer</li>
      <li>Estudiar</li>
      <li>Dormir</li>
    </ol>
```

- El elemento `<ol></ol>` nos permite crear la lista ordenada.
- Los elementos `<li></li>` nos permiten agregar items a la lista ordenada.

## Crear listas combinadas

1. Agregar:

```
    <h2>Lista de las actividades que vamos a hacer hoy</h2>

    <ol start="5" type="a" reversed>
      <li>Lavarme los dientes</li>
      <li>Bañarme</li>
      <li>
        Ir a hacer las compras
        <ul>
          <li>Cafe</li>
          <li>Azúcar</li>
          <li>Turrones</li>
          <li>Galletas</li>
        </ul>
      </li>
      <li>Cocinar</li>
      <li>Comer</li>
      <li>Estudiar</li>
      <li>Dormir</li>
    </ol>
```

- El atributo `start` nos permite hacer que una lista ordenada no empiece con el indice `1`.
- En atributo `type` nos permite hacer que una lista ordenada utilice letras o números romanos como indice.
- El atributo `reversed` nos permite hacer una lista ordenada de forma descendente.
