# Flexbox
> Flexbox (o CSS Flexible Box Layout) es un sistema de diseño en CSS que te permite organizar elementos de manera flexible y eficiente en una dimensión (ya sea horizontal o vertical).

## ¿Para qué se usa Flexbox?
> Flexbox resuelve muchos problemas comunes de maquetación que antes eran complicados:
> Alineación y distribución: Puedes centrar elementos tanto horizontal como verticalmente de forma muy sencilla, distribuir espacio entre elementos, o alinearlos de diferentes maneras.
> Layouts responsivos: Los elementos pueden crecer, encogerse o mantener su tamaño según el espacio disponible, lo que es perfecto para diseños que se adaptan a diferentes pantallas.
> Orden flexible: Puedes cambiar el orden visual de los elementos sin modificar el HTML.

## Conceptos básicos
> Para usar flexbox, defines un contenedor como display: flex. Esto crea dos ejes:

    [] Eje principal (main axis): Por defecto horizontal
    [] Eje transversal (cross axis): Perpendicular al principal

> Los elementos hijos se convierten automáticamente en "flex items" que puedes controlar con propiedades como:

    [] justify-content: Para alinear en el eje principal
    [] align-items: Para alinear en el eje transversal
    [] flex-direction: Para cambiar la dirección del eje principal
    [] flex-wrap: Para permitir que los elementos se envuelvan en nuevas líneas

> Flexbox es especialmente útil para barras de navegación, centrado de contenido, distribución de tarjetas, y cualquier layout donde necesites que los elementos se adapten dinámicamente al espacio disponible.
