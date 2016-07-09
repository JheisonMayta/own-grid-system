# OwnGrid
Sistema de grillas minimalista.

## Uso
Compile el archivo `styles.scss` en un `.css`, puede realizar esta acción mediante la consola de su sistema operativo o también haciendo uso de alguna aplicación de compilación como [Koala](http://koala-app.com/). Una vez tenga el archivo `.css`, deberá enlazarla al archivo `.html` mediante la etiqueta `<link>`.

##### Ejemplo:
```html
<link rel="stylesheet" type="text/css" href="/ruta-al-archivo.css/">
```
Y listo, podrá comenzar a programar su web rápidamente.


## Elementos
### Grillas

En caso desee modificar los valores por defecto de las variables que controlan el tamaño mínimo de la página (`$minPageWidth`), el tamaño máximo de la misma (`$maxWidth`), la cantidad de columnas (`$columns`), los márgenes de la grilla (`$marginWidth`) y/o el tamaño de los canales (`$gutterWidth`), conocidos también como *gutters*, ir a la ruta que se muestra debajo y modificar los valores de las variables.

> **`file:`** `project-folder/scss/modules/_variables.scss`

```scss
// Grid Variables

$minPageWidth: {pixels};
$maxWidth: {pixels};
$marginWidth: {pixels};
$columns: {integer};
$gutterWidth: {pixels};
```

El tipo de información que acepta cada variable está descrita entre llaves (`{value}`), se debe tener en cuenta las unidades ya que sino generaría un error de valor.


###### Ejemplo:

```scss
// Grid Variables

$minPageWidth: 320px;
$maxWidth: 1024px;
$marginWidth: 20px;
$columns: 12;
$gutterWidth: 16px;
```


>**`@author`** Jheison Mayta

>**`@email`** [jjmayta.caceres@gmail.com](mailto:jjmayta.caceres@gmail.com)
