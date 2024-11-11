# CURSO UDEMY DESARROLLO WEB

## PROYECTO FREELANCER

## CLASE 9

### Etiquetas basícas en HTML

- `<p>` Etiqueta para colocar párrafos
- `<nav>` Etiqueta para colocar una barra de navegación
- `<header>` Etiqueta para encabezados
- `<main>` Etiqueta para el contenido principal de la página
- `<footer>` Etiqueta para colocar un pie de página o elemento

### Ejemplo de la estructura de código HTML

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>

</body>
</html>
```

> NOTA: Investigar ¿Qué es el formato SVG?

#### ¿Qué es un archivo SVG?

El **Scalable Vector Graphics** o **SVG** (_Graficos Variables ampliables_) es un **formato de archivo vectorial** apto para toda la web. Al contrario de los archivos **rasterizados** basados en pixeles, como los: **jpg, png, etc.**

Los archivos vectoriales **almacenan** las imagenes mediante **formatos matemáticos** basados en **puntos** y **lineas** en una **cuadricula**. Por lo tanto, los archivos vectoriales como lo son los SVG **pueden redimensionares considerablemente** sin perder nada de calidad.

La gran popularidad de la que gonzan los SVG no se debe solo a su capacidad de redimensionamiento, si no al hecho de que **almacena cualquier tipo de información de texto como texto literal**, en lugar de formas, ya que se escribe en **código XML**. Esto permite a los motores de busqueda (_como Google_) leer lso graficos SVG de las palabras clave, que pueden ayudar a un sitio web a mejorar su posición en lso resultados de busqueda.

_Los archivos SVG se detectan facilmente con su extensión `.svg`_

#### ¿Qué es XML?

**XML es un lenguaje de marcad similar a HTML**. Significa **Extensible Markup Lenguaje** (_Lenguaje de Marcado Extensible_) y es una especie de **W3C** como lenguaje de marcado de proposito general. Esto significa que, a diferencia de otros lenguajes de marcado, **XML no está prédefinido**, por lo que, **debes definir tus propias etiquetas**. El proppsito general del lenguaje es **compartir datos** a partir de diferentes sistemas, como internet.

#### ¿Para qué sirve XML?

1.- **Facilita el intercambio de datos:** Esto ocurre por dos razones. La primera, porque los datos XML estan almacenados en **formato de texto simple**, lo que permite almacenar y comparitr la información entre diferentes sistmas o aplicaciones de manera más rapida y sencilla. La segunda porque si hay algo que caracteriza a los datos XML, es que los mismos pueden se leidos por diferentes plataformas o sistemas que, aun siendo imcompatibles. permitan a los desarrolladores intercambiar los datos facilmente entre un y otra.

2.- **Separar los datos de HTML:** Gracias a XML, los datos HTML pueden almacenarse en archivos XML separados, lo qeu hace más sencilla su edición cada vez que sea necesaria.

3.- **Simplifica el cambio a una nueva aplicación, sistema o plataforma:** Los datos XML se almacenan en formato de texto simple, haciendo más sencilla la futura expanción o actualización a un nuevo sistema de información, navegador o plataforma.

## CLASE 16: Estructurar contenido HTML

### Etiquetas par agrupar

```HTML
<header>
<footer>
<nav>
<main>
<section>
<article>
<aside>
<div>
```

<!-- COLOCAR IAMGEN PARA UNA MEJOR COMPRENSIÓN. -->

> REGLA: Si el **primer elemento** hijo es un `heading` lo tenemos que **agrupar** en un `section`, pero si se encuentra dentro del contenido principal, lo agrupamos dentro de un `main`.

Los `heading` usualmente sirve / indica la introducción de **nuevos contenidos**

## CLASE 18: Añadir imagenes con HTML

### Sitios web para usar iconos

1.- [Tabler Icons](https://tablericons.com/)

2.- [HeroIcons](https://heroicons.dev/)

3.- [Font Awesome](https://fontawesome.com/)

Introducimos la etiqueta `<img>` la cual lo vamos a utilizar para colocar imagenes dentro de nuestro sitio web, además **no tiene etiqueta de cierre.**

## CLASE 21: Primeros pasos con CSS

Cada que los estilos que colocamos a una etiqueta dentro de nuestra página web no se vean reflejados, nos vamos a dirigir al apartado de **insepccionar** del navegador que estemos utlizando para nuestro desarrollo, y vamos a seleccionar el **icono de la parte superior izquierda** (_que es como un cuadrado con una flecha apuntando hacia arriba a la izquierda_), y despues vamos a seleccionar el elemento en el cual no vemos reflejados los cambios de estilos.

Esto para verificar que estamos colocando los estilos al elemento correcto, por medio de la clase o ID.

## CLASE 23 Estilos a nuetro proyecto

> TAREA: Investigar que son los pixeles, los REM y los EM,

### Unidades de medida en CSS

CSS ofrece varias unidades de medida para dimensionar elementos de una página web. Algunas de las unidades de medida más comunes son los **pixeles** (_px_) , **porcentajes** (_%_), **picas** (_pc_) y las unidades **EM** y **REM**.

#### Unidades EM

La **unidad EM** es relativa al tamaño de fuente del elemento padre. Cuando se especifica un valor en EM, se toma como referencia el tamaño de la fuente del elemento contenedor más cercano. Por ejemplo, si ele tamaño de una fuente de un parráfo es de **16px**. Si un elemento secundario dentro de ese parráfo tiene un tamaño de fuente de **1.5em** su tamaño de fuete será de **24px** (_1,5 \* 16px_).

##### Ventajas de EM

- **Escalabilidad:** Los valores de EM son relztivos y se escalana automáticamente cuando se cambia el tema de la fuente del elemento padre. Esto facilita al creación de diseños flexibles y adaptables.

- **Accesibilidad:** EM permite a los usuarios ajustar el tipo de fuente en su navegador segun sus preferencias de lectura.

#### Unidades REM

La unidad REM, que signififca **"Root EM"** (_EM raíz_), es similara a EM, pero tomá como referencia el tamaño de fuente del elemento raíz del documento HTML en lugar del elemento padre. Por defecto, el tamaño de fuente raíz es de 16px en la mayoria de los navegadores. Si se establece un amrgen de **un REM** en un elemento, sera igual a **16px**. Si se cambía el tamaño de fuente raíz a 20px, todos los elementos con unidad REM se ajustaran en consecuencia.

##### Ventajas de REM

- **Cosnistencia:** REM ofrece una forma más predecible de gestionara tamaños de fuente raíz, lo que facilita la creación de diseños coherentes.

- **Facilita el cambio global:** Cambiar el tamaño de fuente raíz afecta a todos los elementos que utilizan REM en la página, lo que facilita la adaptación global del diseño.

## CLASE 24

### Tipos de selectores

- **Selector de elemento:**

Seleccionara un elemento en base a su etiqeuta.

```CSS
p {
  color: blue;
}
```

- **Selector de clase:**

Una clase se puede crear multiples veces (_es reutilizable_) e **inicia con un punto**.

```CSS
.cliente {
  color: blue;
}
```

- **Selector de ID:**

Puede tener multiples ID's por página, pero **su nombre no pueden repetirse** en un documento HTML.

Un ID inicia con un signo de **gato** / **almohadilla** (_#_)

```CSS
#cliente {
  color: blue;
}
```

- **Selector de atributo:**

Selecciona elementos basados en algún atributo que tenga.

```CSS
[src = "logo.jpg"] {
  color: blue;
}
```

- **Combinación de decententes (selectores):**

Selecciona los elementos hijos cuyo padre sea una clase (_o ID_) en especifico.

```CSS
.cliente .nombre {
  color: blue;
}
```

- **Todos los hijos:**

Aplica la siguiente regla a todos los parráfos hijos.

```CSS
.cliente > p {
  color: blue;
}
```

## CLASE 25: Especificidad en CSS

La **especificidad** es como el navegador va a mostrar el CSS de acuerdo a que tan especifico sea el **selector** que hemos creado.

CSS es en cascada, pero eso no significa que si un selector aparece despues que otro este sera tomado en cuenta, sino que lo más importante es su **especifidad**.

- **Ejemplo sin especificidad.**

```CSS
p {
  color: blue;
}
p {
  color: red;
}
```

- **Ejemplo aplicando especificidad**

```CSS
p.parrafo {
  color: blue;
}
p {
  color: red;
}
```

- **Ejemplo aplicando una mayor especificidad**

```CSS
p#parrafo {
  color: blue;
}
p {
  color: red!important;
}
```

_Recuerda, si un elemento tiene un selector más especifico no importa mucho donde haya sido declarado, CSS decidira pos su especificidad._

## CLASE 29: Estilos CSS a la navegación

> NOTA: Podemos colocarle más de una clase a algun elemento (_etiqueta_) HTML, esto se hace separando el nombre de las clases con un espacio.

```HTML
<h1 clases="clase1 clase2">
```

Pero esto mismo solo funciona con las clases, con las ID´s no, ya que **un elemento HTML solo puede tener un ID**.

## CLASE 30: Estilos CSS a la nevegación y Display en CSS

Existen diferentes tipos de **display**, los que el navegador aplica por defecto son:

- **Dsiplay block o inline**.

> Algunos elementos se van a mostrar de una forma y otros de otra.

Todos los elementos en HTML ya tienen un display por default.

- **Display block:**
  Significa que los elementos se colocarán **uno debajo del otro** sin importar mucho su contenido.
  Un ejemplo de estos son los `<div>`.

- **Display inline:**
  Significa que los elementos se posicionaran a la derecha una ves que hayan tomado el espacio que requieran.
  Un ejemplo son los `<nav>`.

## CLASE 32: Estilos de navegación y posicionando los enlaces con FlexBox

### Los 2 ejes de FlexBox

En FlexBox solo puedes colocar y dirigir tus elementos en una sola dirección filas (_rows_) o columnas (_columns_).

El valor de **Row** se aplica por defecto al definir un **display: flex;**

Los otros valores son **row-reverse**, **column** y **column-revers**.

Si elegimos a **row** o **row-reverse** los elementos hijos se mostraran de izquierda a derecha uno junto al otro.

<!-- Colocar imagen para una mejor comprensión. -->

Al elejir **column** o **column-revers** los elementos colocaran de arriba hacia abajo.

<!-- Colocar imagne para una mejor comprensión. -->

Flex-Box es especialmente diseñado para alinear tus elemenots en tus diseños. No añade efectos de animación, ni textos, es una tecnologia utilizada unicamente para los layouts y sustituye a los floats o table-cell.

## CLASE 33: Estilos par escribir código CSS - BEM, Modulos y Utilidades

### ¿Cómo escribir código CSS?

Existen diferentes maneras de escribir código CSS, las más comunes son: **BEM, Utility First** o **Módulo**. Si el proyecto tiende a ser grande es buena idea a usar cualquiera de los tres anteriores.

#### BEM (Bloque, Elemento, Modificador)

```CSS
.card {} /* Esto viene representando un "BLOQUE" */
.card__titulo {} /* Esto representa a un "ELEMENTO" */
.card__imagen {} /* Esto es otro "ELEMENTO" */
.card__boton {} /* Y esto es otro "ELEMENTO" */
.card__boton--activo {} /* Esto representa a un "MODIFICADOR" */
```

#### Utitity First

Basicámente creamos clases con una sola propiedad que describe que es lo que haría.

```CSS
.texto-center {} /* Si queremos centrar un texto, creamos una clase llamada texto. y dentro colocamos el código CSS para centrar el texto */

/* Si queremos agregar una paleta de colores, tendriamos muchas clases */

.color-red-100 {} /* La propiedad de al final (el número) indicaría la intensidad del color */
.bg-blue-200 {} /* Esta clase sería para colocar un color de fondo */+

/* Clases para colocar <<padding>> y <<margin>> */

.p-2 {} /* padding de 2 */ 
.m-2 {} /* margin de 2 */
```

Basicámente en Utility First vas a tener unicamente una propiedad y un valor por clase.

> DESVENTAJA: Terminas usando demasiado código CSS

#### Módulos

Definimos lo que es el contenido principal y despues seleccionamos los elementos HTML, como lo son las imagenes, un h2, un enlace, etc.
Definimos una clase "padre", y despues vamos seleccionando cada una de las etiquetas del código HTML.

```CSS
.card {}
.card h2 {}
.card img {}
.card a {}
```
_Es posible utilizar más de un enfoque en un mismo proyecto._
> TAREA: Investigar más a fondo sobre lo que es BEM, Utility-First y los Módulos.

### Métodologia BEM (Bloque, Elemento, Modificador)

**BEM** funciona identificando el bloque, el elemento y el modificador de un componente.

BEM en CSS es una metodología de nomenclatura que se utiliza para **organizar y estructurar el código CSS** de una forma más modular y reutilizable. BEM significa **Bloque, Elemento y Modificador**, y se basa en la idea de dividir el código en bloques independientes, elementos dentro de esos bloques y modificadores que permiten aplicar estilos adicionales de forma sencilla y consistente. Esta metodología es ampliamente adoptada en la industria del desarrollo web por su capacidad para mejorar la legibilidad, mantenibilidad y escalabilidad de los estilos CSS.

El BEM (Bloque, Elemento, Modificador) es una metodología de nomenclatura para escribir y organizar el código CSS de manera más eficiente y sostenible. Esta metodología se ha vuelto cada vez más popular en los últimos años debido a sus beneficios en la legibilidad, reutilización y mantenibilidad del código.

El objetivo principal de BEM es evitar la creación de **selectores CSS muy específicos y anidados**, lo cual puede generar problemas de especificidad y dificultar el mantenimiento del código. **Con BEM, se busca tener selectores más claros y desacoplados**, lo que facilita la comprensión y modificación del código en el futuro.

#### Bloques, Elementos y Modificadores

La nomenclatura BEM se basa en tres conceptos principales: bloques, elementos y modificadores. Estos tres conceptos son los componentes básicos que se utilizan para construir la estructura del código CSS.

- **Bloque** es el contenedor principal del componente.
- **Elemento** son las partes internas que conforman el componente.
- **Modificador** son las variaciones del bloque o del elemento.

Un **bloque** es un **componente independiente y reutilizable de la interfaz de usuario**. Puede ser cualquier elemento HTML, como un botón, un menú o un formulario. Los bloques se identifican utilizando una clase CSS que lleva el mismo nombre que el elemento HTML al que representan.

_Por ejemplo, si tenemos un bloque que representa un botón, su clase CSS se llamaría «.boton». Esto permite identificar y aislar fácilmente el estilo asociado a ese botón en el código CSS._

Un **elemento** es una parte **específica y dependiente de un bloque**. Los elementos están dentro de los bloques y se utilizan para componer el diseño y la funcionalidad de un bloque. Se identifican utilizando una clase CSS que lleva el nombre del bloque seguido de un guion bajo y el nombre del elemento.

_Por ejemplo, si tenemos un bloque de formulario con un campo de entrada de texto, su clase CSS se llamaría «.formulario__campo». En este caso, el bloque es «formulario» y el elemento es «campo». Esto ayuda a entender rápidamente la estructura del código y su relación con otros bloques y elementos._

Finalmente, los **modificadores** se utilizan para **cambiar la apariencia o el comportamiento de un bloque o elemento**. Los modificadores se representan mediante una clase CSS adicional que se añade al bloque o elemento relevante.

_Los modificadores se escriben después de un doble guion bajo (__) _para elementos y después de un solo guion bajo (_) para bloques. Por ejemplo, si tenemos un botón que quiere tener un estado «activo» o «desactivado», podríamos utilizar las clases «.boton–activo» y «.boton–desactivado» para aplicar diferentes estilos a esos botones en particular._

Los nombre de las clases con cenversion BEM, se pueden tener la siguiente sintaxis:

- [bloque]
- [bloque]__[elemento]
- [bloque]--[modificador]
- [elemento]--[modificador]
- [bloque]__[elemento]--[modificador]

Y así se veria el HTML

```HTML
<form ="button"></form>
<input ="button__entrada">
<input ="button--activo">
```

IMPORTANTE: Recuerda que:
- Los guiones bajos (__) se usan para separar el bloque del elemento.
- Los guienes medios (--) se usan para separar el bloque o el elemento del modificador.

#### Ventajas de utilizar BEM

La métodologia BEM ofrece varias ventajas que la hacen una opción atractiva para escribir código CSS:

- **Legibilidad**: El uso de nombres de clases descriptivas y autoexplicativas facilita la comprensión del código para otros desarrolladores.
- **Mantenibilidad**: Al tener estilos más claros y desacoplados, es más fácil realizar cambios y modificaciones en el código sin generar efectos no deseados en otras partes del sitio.
- **Reutilización**: Los bloques y elementos pueden ser fácilmente reutilizados en diferentes partes del sitio sin necesidad de reescribir código.
- **Escalabilidad**: BEM es una metodología que se adapta fácilmente a proyectos grandes y complejos, ya que organiza el código de manera estructurada y coherente.


> FUENTES:
[¿Qué es BEM en CSS?](https://we-school.es/que-es-bem-en-css/)
| [Guia de BEM para CSS](https://platzi.com/blog/bem/)