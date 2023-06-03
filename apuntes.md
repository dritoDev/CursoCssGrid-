## Que es Css Grid Layout?

- es una especificacion de css que nacio de la necesidad de hacer Layout mucho mas dinamicos Css Grid introdujo unas grillas que tienen tanto colimnas como filas con grid podemos usar los ejes para posicionar elementos podemos jugar con las posiciones, el tamano que ocupan y como se alinean

# Consectos basicos de grid!

- que es un contenedor: Es el elemento que se ba conbertir en una grilla

    <div class="container" > <==  Contenedor

        <div class="item item1">1</div> 
        <div class="item item2">2</div>

    </div>

- que es el Item: sson los elementos que se encuetran dentro del contenedor

    <div class="container" > 

        <div class="item item1">1</div> \
                                         |  <=== Item
        <div class="item item2">2</div> /

    </div>

## Conceptos para comensar.

- Rows = Lines.

- Colunm = columnas.

- lines: Son las que dividen las colimnas de las filas. 

- Celdas: es unidad minima que podemos usar dentro de una grilla y normalmente solo usa una unidad de una columna

## grupos dde celdas 

- Track: son los grupos de celdas que estan en una misma columna o en una misma fila.

- Area: Las areas en barias filas y barias columnas a la vez.


## Propiedaes del contenedor.

- Estas con las propiedades que nos permiten crear una grilla de diferente caamtidad de filas y columnas y definir los espaciados entre estas filas y columnas

- Display grid
- Grid-template
- Gaps
- Grid-auto

