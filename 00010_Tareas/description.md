Necesitamos organizar nuestras tareas y para ello vamos a crear una lista de pendientes :white_check_mark: que contenga:

- un título `h1` que diga: `Mis tareas`;
- un título `h2` que diga: `Tareas para hoy`;
- agregar 6 tareas, que deben tener:
  - un título `h3` con la tarea a realizar (por ejemplo `Hacer las compras`);
  - un elemento en línea `span` con el estado de la tarea: `pendiente`, `haciendo`, `hecha`, `cancelada`.
  
Por ejemplo:

```
Mis tareas
Tareas para hoy

Ir al banco
Cancelada

Preparar parcial
Haciendo

Pasear al perro
Hecha
```
Tené en cuenta las siguientes consideraciones:

- poner a los títulos la tipografía de Google Fonts `Poppins`;
- dar a los títulos h1 y h2 un tamaño de fuente de `25px`;
- poner a cada estado un color de letra distinto utilizando clases siguiendo el siguiente criterio:
  - pendiente: Azul `#0000FF`;
  - haciendo: Naranja `#FF8000`;
  - hecha: Verde `#008F39`;
  - cancelada: Rojo `#FF0000`;

Las clases deben tener el mismo nombre que el estado, por ejemplo: `class= "pendiente"`.

> Creá el código HTML que acabamos de describir.