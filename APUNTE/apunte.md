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
