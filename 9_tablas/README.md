# Capitulo 9: Tablas

## Tabla basica

1. Agregar:

```
    <h1>
        Tabla
    </h1>
    <hr>
    
    <table>
        <tr>
            <td>Item 1</td>
            <td>Item 2</td>
            <td>Item 3</td>
            <td>Item 4</td>
        </tr>
        <tr>
            <td>Item 1</td>
            <td>Item 2</td>
            <td>Item 3</td>
            <td>Item 4</td>
        </tr>        
    </table>
```

El elemento ```<table></table>``` representa la tabla. Luego, cada elemento ```<tr></tr>``` es una fila. Y finalmente, cada elemento ```<td></td>``` es una columna dentro de una fila.

## CSS basico

1. Modificar el contenido de `style.css`:

```
table {
    /* Para que los bordes se unan porque esta colapsado */
    border-collapse: collapse;
    /* Borde exterior de la tabla de 2 pixeles de color gris */
    border: 2px solid rgb(200, 200, 200);
    /* Separacion entre letras */
    letter-spacing: 1px;
    /* Tamaño de fuente un poco mas chico */
    font-size: 0.8rem;
}
td, th {
    /* Borde interior de la tabla de 1 pixele de color gris levemente mas oscuro, que se va a pegar al borde exterior de la tabla porque esta colapsado */
    border: 1px solid rgb(190, 190, 190);
    /* Separacion interno entre las filas y columnas */
    padding: 10px 20px;
}
```

Ahora, la tabla se ve como una tabla.

## Tabla avanzada

1. Agregar:

```
    <h1>
        Tabla de Mascotas
    </h1>
    <hr>

    <table>

        <colgroup>
            <col style="background-color: lightgray;">
            <col>
            <col>
            <col>
            <col>    
        </colgroup>

        <tr>
            <th>&nbsp;</th>
            <th>Lima</th>
            <th>Pandi</th>
            <th>Chiqui</th>
            <th>Luna</th>
        </tr>
        <tr>
            <td>Edad</td>
            <td>2</td>
            <td>5</td>
            <td>4</td>
            <td>4</td>
        </tr>   
        <tr>
            <td>Raza</td>
            <td>3 Patas</td>
            <td>Jack Russell</td>
            <td>Vampira</td>
            <td>Mestiza</td>
        </tr>
        <tr>
            <td>Comidas</td>
            <td>2</td>
            <td>3</td>
            <td>1</td>
            <td>2</td>
        </tr>
        <tr>
            <td>Popo</td>
            <td>Afuera</td>
            <td>Afuera</td>
            <td>Afuera</td>
            <td>Afuera</td>
        </tr>
        <tr>
            <td>Peso</td>
            <td>9</td>
            <td>10</td>
            <td>8</td>
            <td>20</td>
        </tr>
    </table>
```

2. Modificar el contenido de `style.css`:

```
table {
    /* Para que los bordes se unan porque esta colapsado */
    border-collapse: collapse;
    /* Borde exterior de la tabla de 2 pixeles de color gris */
    border: 2px solid rgb(200, 200, 200);
    /* Separacion entre letras */
    letter-spacing: 1px;
    /* Tamaño de fuente un poco mas chico */
    font-size: 0.8rem;
}
td, th {
    /* Borde interior de la tabla de 1 pixele de color gris levemente mas oscuro, que se va a pegar al borde exterior de la tabla porque esta colapsado */
    border: 1px solid rgb(190, 190, 190);
    /* Separacion interno entre las filas y columnas */
    padding: 10px 20px;
}
th {
    /* Borde interior de la tabla de 1 pixele de color gris levemente mas oscuro, que se va a pegar al borde exterior de la tabla porque esta colapsado */
    border: 1px solid rgb(190, 190, 190);
    /* Separacion interno entre las filas y columnas */
    padding: 10px 20px;
    /* El color de fondo es el gris mas oscuro */
    background-color: grey;
}
```

`&nbsp;` se utiliza para dejar el contenido vacio.

El elemento ```<colgroup></colgroup>```, en conjunto con los elemento ```<col>```, nos permiten definir una apariencia distinta para cada columna.

El elemento ```<th></th>``` se utliza en lugar de ```<td></td>```, en la fila que tiene las etiquetas y nos permiten definirle una apariencia distinta.