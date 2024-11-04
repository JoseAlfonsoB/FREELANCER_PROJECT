# CURSO DESARROLLO WEB

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