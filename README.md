<!-- Asi es como se comenta en HTML -->
<!--Para Visualizar tanto el codigo como la previsualizacion se teclea: F1 o Ctrl+Shift+P y se busca la opcion markdown open preview-->

<!-- Encabezados -->

# Mi titulo H1
## Mi titulo H2
### Mi titulo H3
#### Mi titulo H4
##### Mi titulo H5
###### Mi titulo H6


<!-- italic -->
este es un *texto* en italica

<!-- strong -->
este es un **texto** en negrita

<!-- strikethrough -->
este es un ~~texto~~ <!--Para hacerlo es Alt+126--> tachado

<!-- UL -->
* manzana
    * manzana 2
* naranja
    * hola
* etc

1. manzana
    1. manzana
2. naranja
3. etc

<!-- Asi se pueden poner textos con encales -->
[google.com](https://www.google.com)
<!-- Para ponerle un texto, dentro del parentesis se le escribe el spring -->
[google.com](https://www.google.com "Esto te lleva a google")

<!-- con el > se puede citar frases -->
> Esto es una cita

<!-- Asi se generan lineas -->

---
___

<!-- Para escribir codigo hay que ponerlo dentro de comillas `` -->
`console.log('Hola mundo')`
<!-- Para escribir un bloque de codigo con varias lineas van dentro de triple comillas `````` y en los primeros se puede poner que clase de codigo es para que lo remarque -->
```javascript
const {sumar, restar, multiplicar, dividir} = require ('./caculadora');

switch (process.argv[2]) {
    case "sumar":
        sumar(process.argv[3], procces.argv[4])
        break;
    case "restar":
        restar (process.argv[3],process.argv[4])
        break;

    default:
        break;
}
```

```html
<h1>Hola mundo</h1>
```

<!-- Para hacer textos con regla -->
| Hola esto es titulo con columna   |
|-----------------------------------|
| Ejemplo   |
| Otro ejemplo  |
|Ejemplo 3  |

<!-- Para poner imagenes -->
![Pepe grillo](https://upload.wikimedia.org/wikipedia/commons/b/b5/Jiminy_Cricket.png "Pepe Grillo")

![pepe grillo](pepegrillo.png "Pepe Grillo")

<!-- Para poner listas en Git -->

* [x] Tarea hecha
* [] Tarea hecha
* [x] Tarea hecha
