# 036-html-w3schools
Fundamentos de HTML con W3Schools

## HTML es el lenguaje de marcado estándar para páginas web.
# 02-introduccion
## ¿Qué es HTML?
HTML significa Lenguaje de Marcado de Hipertexto, es el lenguaje de marcado estándar para crear páginas web.
describe la estructura de una página web, consta de una serie de elementos
Los elementos HTML le indican al navegador cómo mostrar el contenido.
Los elementos HTML etiquetan fragmentos de contenido como "este es un encabezado", "este es un párrafo", "este es un enlace", etc.

# 04-basico
# Encabezados
se define con las etiquetas h1 a h6
h1 define el encabezado mas importante y el h6 define el encabezado menos importante

# parrafos
los parrafoes de definen con la etiqueta p

# enlaces
los enlaces se definen con la "a"

# imagenes
se definen con img
El archivo fuente ( src), el texto alternativo ( alt), widthy heightse proporcionan como atributos

# elementos
Un elemento HTML se define mediante una etiqueta de inicio, algún contenido y una etiqueta de cierre.

# atributos
- Todos los elementos HTML pueden tener atributos.
- Los atributos proporcionan información adicional sobre los elementos.
- Los atributos siempre se especifican en la etiqueta de inicio.
- Los atributos suelen presentarse en pares nombre/valor como: nombre="valor"

La a etiqueta define un hipervínculo. El hrefatributo especifica la URL de la página a la que conduce el enlace

* El atributo lang
Siempre debes incluir el langatributo dentro de la  html etiqueta para declarar el idioma de la página web. 

* El atributo del título
Este titleatributo define información adicional sobre un elemento.

# 08-parrafos
Reglas horizontales HTML
Esta hr etiqueta define una separación temática en una página HTML y, por lo general, se muestra como una línea horizontal.

# 09-estilos
El style atributo HTML se utiliza para añadir estilos a un elemento, como color, fuente, tamaño, etc.

- Utilice el styleatributo para dar estilo a los elementos HTML.
- Utilizar background-colorpara el color de fondo
- Utilizar colorpara colores de texto
- Utilizar font-familypara fuentes de texto
- Utilizar font-sizepara tamaños de texto
- Utilizar text-alignpara la alineación del texto

# 10-formato
b- Texto en negrita
strong- Texto importante
i- Texto en cursiva
em- Texto resaltado
mark- Texto marcado
small- Texto más pequeño
del- Texto eliminado
ins- Texto insertado
sub- Texto de subíndice
sup- Texto en superíndice

# 13-colores
Los colores HTML se especifican mediante nombres de color predefinidos o mediante valores RGB, HEX, HSL, RGBA o HSLA.

## Colores RGB Y RGBA
* Un valor de color RGB representa fuentes de luz ROJA, VERDE y AZUL. rgb( rojo, verde , azul )

* Un valor de color RGBA es una extensión de RGB con un canal alfa (opacidad).

## Colores HEX de HTML
Un color hexadecimal se especifica con: #RRGGBB, donde los enteros hexadecimales RR (rojo), GG (verde) y BB (azul) especifican los componentes del color.

## Colores HTML HSL y HSLA
HSL significa tono, saturación y luminosidad.

Los valores de color HSLA son una extensión de HSL con un canal alfa (opacidad).

## Colores HTML HSL y HSLA
HSL significa tono, saturación y luminosidad.

Los valores de color HSLA son una extensión de HSL con un canal alfa (opacidad).

## Valores de color HSL
En HTML, un color se puede especificar utilizando el tono, la saturación y la luminosidad (HSL) de la siguiente forma:

hsl( tono , saturación , luminosidad )

* El tono es un grado en la rueda de colores que va de 0 a 360. 0 es rojo, 120 es verde y 240 es azul.

* La saturación es un valor porcentual. El 0% significa un tono de gris y el 100% es el color completo.

* La luminosidad también es un valor porcentual. El 0% es negro y el 100% es blanco.

## Saturación
La saturación puede describirse como la intensidad de un color.

- El 100% es color puro, sin tonalidades de gris.
- El 50% es 50% gris, pero aún se puede ver el color.
- El 0% es completamente gris; ya no se puede ver el color.

## Valores de color HSLA
Los valores de color HSLA son una extensión de los valores de color HSL, con un canal alfa que especifica la opacidad de un color.

Un valor de color HSLA se especifica con:
- hsla( tono, saturación , luminosidad, alfa )
- El parámetro alfa es un número entre 0,0 (totalmente transparente) y 1,0 (nada transparente)

# 14 Estilos css
CSS significa Hojas de Estilo en Cascada.

CSS ahorra mucho trabajo. Permite controlar el diseño de varias páginas web a la vez.

Se puede agregar CSS a los documentos HTML de 3 maneras:

En línea : mediante el uso del styleatributo dentro de los elementos HTML
Interno - mediante el uso de un <!--<style>-->elemento en la <!--<head>-->sección
Externo : mediante el uso de un <!--<link>--> elemento para enlazar con un archivo CSS externo.

## Colores, fuentes y tamaños CSS
Aquí, mostraremos algunas propiedades CSS de uso común. Aprenderás más sobre ellas más adelante.

colorLa propiedad CSS define el color del texto que se va a utilizar.

font-familyLa propiedad CSS define la fuente que se va a utilizar.

font-sizeLa propiedad CSS define el tamaño del texto que se va a utilizar.

Utilice el styleatributo HTML para el estilo en línea.
Utilice el style elemento HTML para definir el CSS interno.
Utilice el link elemento HTML para hacer referencia a un archivo CSS externo.
Utilice el head elemento HTML para almacenar elementos style y link.
Utilice la colorpropiedad CSS para los colores del texto.
Utilice la font-familypropiedad CSS para fuentes de texto.
Utilice la font-sizepropiedad CSS para los tamaños de texto.
Utilice la borderpropiedad CSS para los bordes.
Utilice la paddingpropiedad CSS para el espacio dentro del borde.
Utilice la marginpropiedad CSS para el espacio fuera del borde.

# 15 Enlaces
Por defecto, los enlaces aparecerán de la siguiente manera en todos los navegadores:

Un enlace no visitado aparece subrayado y en azul.
Un enlace visitado aparece subrayado y en color morado.
Un enlace activo aparece subrayado y en rojo.

El targetatributo especifica dónde abrir el documento vinculado.

El targetatributo puede tener uno de los siguientes valores:

_self- Predeterminado. Abre el documento en la misma ventana/pestaña en la que se hizo clic.
_blank- Abre el documento en una ventana o pestaña nueva.
_parent- Abre el documento en el marco principal.
_top- Abre el documento en todo el cuerpo de la ventana.

Utilice el a elemento para definir un enlace.
Utilice el hrefatributo para definir la dirección del enlace.
Utilice el targetatributo para definir dónde abrir el documento vinculado.
Utilice el img elemento (dentro de  a) para usar una imagen como enlace.
Utilice el mailto:esquema dentro del hrefatributo para crear un enlace que abra el programa de correo electrónico del usuario.

* marcador
Utilice el idatributo (id=" valor ") para definir marcadores en una página.
Utilice el hrefatributo (href="# valor ") para enlazar con el marcador.

# 16 imagenes
Sintaxis de imágenes HTML
La img etiqueta HTML se utiliza para insertar una imagen en una página web.

Las imágenes no se insertan técnicamente en una página web; se enlazan a páginas web. La img etiqueta crea un espacio reservado para la imagen a la que se hace referencia.

La img etiqueta está vacía, contiene solo atributos y no tiene etiqueta de cierre.

La img etiqueta tiene dos atributos obligatorios:

src - Especifica la ruta a la imagen
alt - Especifica un texto alternativo para la imagen

* El atributo src
El atributo obligatorio srcespecifica la ruta (URL) a la imagen.

* El atributo alt
El altatributo required proporciona un texto alternativo para una imagen, en caso de que el usuario no pueda verla por algún motivo (debido a una conexión lenta, un error en el atributo src o si el usuario utiliza un lector de pantalla).

# Mapas de imágenes
La map etiqueta HTML define un mapa de imagen. Un mapa de imagen es una imagen con áreas clicables. Estas áreas se definen con una o más area etiquetas.

* ¿Cómo funciona?
La idea detrás de un mapa de imágenes es que puedas realizar diferentes acciones dependiendo del lugar de la imagen en el que hagas clic.

Para crear un mapa de imágenes necesitas una imagen y un código HTML que describa las áreas en las que se puede hacer clic.

# 17 Favicon
es una pequeña imagen que se muestra junto al título de la página en la pestaña del navegador.

# 18 tabla
* celdas tabla
Cada celda de la tabla se define mediante una etiqueta td y una /td etiqueta.

td significa datos de tabla.

* filas de la tabla
Cada fila de la tabla comienza con una etiqueta <tr>y termina con una </tr>etiqueta.

tr significa fila de mesa.

# 20 listas
* Listas de descripción HTML
HTML también admite listas descriptivas.

Una lista descriptiva es una lista de términos, con una descripción de cada término.

La dl etiqueta define la lista de descripción, la dt etiqueta define el término (nombre) y la dd etiqueta describe cada término

## Listas no ordenadas en HTML
La etiqueta HTML <ul>define una lista no ordenada (con viñetas).

Utilice el elemento HTML ol para definir una lista ordenada.
Utilice el typeatributo HTML para definir el tipo de numeración.
Utilice el li elemento HTML para definir un elemento de lista.
Las listas pueden estar anidadas.
Los elementos de la lista pueden contener otros elementos HTML.

Un elemento de nivel de bloque siempre comienza en una nueva línea y ocupa todo el ancho disponible.
Un elemento en línea no comienza en una nueva línea y solo ocupa el ancho necesario.
El div elemento es un elemento de nivel de bloque y se usa a menudo como contenedor para otros elementos HTML.
El spa elemento es un contenedor en línea que se utiliza para marcar una parte de un texto o una parte de un documento.

# 22 Elemento div
Por defecto, este div elemento es un elemento de bloque, lo que significa que ocupa todo el ancho disponible e incluye saltos de línea antes y después

# 23 class
El class atributo HTML especifica uno o más nombres de clase para un elemento.
CSS y JavaScript utilizan clases para seleccionar y acceder a elementos específicos.
Este classatributo se puede utilizar en cualquier elemento HTML.
El nombre de la clase distingue entre mayúsculas y minúsculas.
Diferentes elementos HTML pueden apuntar al mismo nombre de clase.
JavaScript puede acceder a elementos con un nombre de clase específico con el getElementsByClassName() método

# 24 Atributo id de HTML
El atributo HTML idse utiliza para especificar un identificador único para un elemento HTML.

No puede haber más de un elemento con el mismo ID en un documento HTML.

* Diferencia entre clase e ID
Un nombre de clase puede ser utilizado por varios elementos HTML, mientras que un nombre de ID solo debe ser utilizado por un único elemento HTML dentro de la página

Este id atributo se utiliza para especificar un identificador único para un elemento HTML.
El valor del id atributo debe ser único dentro del documento HTML.
Este id atributo es utilizado por CSS y JavaScript para dar estilo o seleccionar un elemento específico.
El valor del id atributo distingue entre mayúsculas y minúsculas.
Este id atributo también se utiliza para crear marcadores HTML.
JavaScript puede acceder a un elemento con un id específico con el getElementById() método

# 25 botones
Tipos de botones
El typeatributo define qué hace un botón al hacer clic. Hay tres tipos de botones:

type="button"- Un botón normal en el que se puede hacer clic (no hace nada por defecto).
type="submit"- Envía un formulario
type="reset"- Restablece todos los campos del formulario


