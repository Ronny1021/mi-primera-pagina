#  Mi primera pagina

Este apartado contiene el desarrollo teórico sobre las tecnologías fundamentales de la web (HTML, CSS, JavaScript) y el uso de herramientas de desarrollo.

1.	¿Qué es HTML y cuál es su función en la web?

HyperText Markup Language (Lenguaje de Marcado de Hipertexto), es el código estándar utilizado para estructurar y organizar el contenido de las páginas web. Funciona mediante etiquetas que indican al navegador cómo mostrar elementos como textos, imágenes, enlaces y vídeos. Es la base estructural de toda web, trabajando junto a CSS (diseño) y JavaScript (interactividad).

2.	¿Qué es una etiqueta HTML y menciona las etiquetas más comunes?

Una etiqueta HTML es un código especial, encerrado entre corchetes (< >), que estructura y define cómo el navegador debe interpretar y mostrar el contenido (texto, imágenes, enlaces) en una página web.

Etiquetas HTML más comunes:
html: Define la raíz del documento.
head: Contiene metadatos, título y enlaces a estilos.
<title>: Establece el título de la página en la pestaña del navegador.
<body>: Contiene todo el contenido visible de la web.
<h1> a <h6>: Definen encabezados, siendo <h1> el de mayor importancia.
<p>: Define un párrafo de texto.
<a>: Crea hiperenlaces.
<img>: Inserta imágenes.
<div>: Agrupa bloques de contenido.
<span>: Define contenido en línea.
<ul>, <ol>, <li>: Crean listas desordenadas, ordenadas y elementos de lista, respectivamente.
<strong>: Indica texto importante (generalmente negrita).
<br>: Produce un salto de línea.

3.	¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?

Un atributo HTML es una propiedad o información adicional definida dentro de la etiqueta de apertura de un elemento (ej. <tag atributo="valor">) que modifica su comportamiento, apariencia o funcionalidad.

Atributos HTML más comunes:
class: Asigna una o más clases CSS para dar estilo al elemento.
id: Identifica de forma única un elemento en la página.
href: Especifica la URL destino en enlaces (<a>).
src: Define la ruta de origen para imágenes (<img>) o scripts.
alt: Proporciona texto alternativo para imágenes.
style: Permite añadir estilos CSS directamente en el elemento.
title: Muestra información extra al pasar el ratón sobre el elemento.
lang: Especifica el idioma del contenido.
target: Indica dónde abrir un enlace (ej. _blank para nueva pestaña).

4.	¿Qué es CSS y cómo se utiliza para el diseño web?

Cascading Style Sheets (Hojas de Estilo en Cascada), es el lenguaje de diseño utilizado para estilizar y maquetar documentos estructurados con HTML. Define colores, fuentes, tamaños, espaciados y el posicionamiento de los elementos, permitiendo que las páginas web sean atractivas y responsivas en distintos dispositivos.

5.	¿Qué es una propiedad en CSS y menciona las propiedades más comunes?

Una propiedad CSS es un parámetro o aspecto específico (como color, tamaño o posición) que se define dentro de una regla para aplicar estilo a elementos HTML.

            Propiedades CSS más comunes:
Color y Fondo: color (color de texto), background-color (fondo).
Tipografía: font-family, font-size, font-weight, line-height.
Modelo de Caja: width (ancho), height (alto), margin (espacio exterior), padding (espacio interior).
Bordes: border, border-radius (esquinas redondeadas).
Alineación y Posición: text-align, display (flex, grid, block), position.

6.	¿Qué es un selector en CSS y cuales tipos existen?

Es un patrón utilizado para seleccionar y asignar propiedades de estilo a uno o varios elementos HTML específicos en una página web. Actúa como el puente entre la estructura HTML y la apariencia definida en las hojas de estilo. 

Selector Universal (*): Apunta a todos los elementos del documento.
Selector de Tipo/Etiqueta (p, div, h1): Selecciona elementos basados en el nombre de la etiqueta HTML.
Selector de Clase (.nombre-clase): Selecciona elementos que tienen un atributo class específico.
Selector de ID (#nombre-id): Selecciona un único elemento basado en su atributo id único.
Selector de Atributo ([attr=valor]): Apunta a elementos que contienen un atributo específico.
Selectores Combinadores: Definen relaciones entre elementos (descendiente div p, hijo div > p, hermano adyacente div + p, hermano general div ~ p).
Pseudo-clases y Pseudo-elementos: Seleccionan elementos basados en estados (:hover, :visited) o partes específicas de un elemento (::before).

7.	¿Qué es JavaScript y cómo añade la interactividad a las páginas web?

Es un lenguaje de programación interpretado, orientado a objetos y dinámico, pilar fundamental de la web (junto a HTML y CSS) que se ejecuta en el navegador del usuario. Aporta interactividad al permitir modificar el contenido, estilos y estructura del DOM en tiempo real, manejando eventos como clics, animaciones y solicitudes de datos sin recargar la página. 

¿Cómo añade interactividad a las páginas web?
Manipulación del DOM (Document Object Model): JavaScript puede cambiar, añadir o eliminar elementos HTML y estilos CSS dinámicamente.
Manejo de Eventos: Reacciona a acciones del usuario como clics de botones, movimientos del ratón, envíos de formularios o pulsaciones de teclado.
Actualizaciones en tiempo real (AJAX/Fetch): Permite enviar y recibir datos de un servidor en segundo plano, actualizando partes de la página sin recargarla (ej. redes sociales o mapas).
Animaciones y Efectos Visuales: Crea menús desplegables, carruseles de imágenes, modales y juegos 2D/3D directamente en el navegador.
Validación de Formularios: Comprueba que los datos introducidos sean correctos antes de enviarlos al servidor.

8.	¿Cuáles son los tipos de datos primitivos en Javascript?

Los datos primitivos son aquellos que están definidos de forma básica en el lenguaje y, lo más importante, son inmutables (su valor no se puede cambiar, aunque la variable que los contiene sí).

string: Representa datos textuales, por ejemplo, 'Hola' o "Mundo".
number: Representa valores numéricos, incluyendo enteros y números de coma flotante (como \(3.14\) o \(42\)).
boolean: Representa un valor lógico, true (verdadero) o false (falso).
null: Denota un valor nulo o la ausencia intencional de valor.
undefined: Representa una variable que ha sido declarada pero aún no se le ha asignado un valor.
bigint: Utilizado para representar números enteros muy grandes que superan el límite seguro de number.
symbol: Representa un identificador único.

9.	¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en Javascript?

Las estructuras de control de flujo en JavaScript (if, else, switch, bucles) permiten alterar la ejecución lineal del código para tomar decisiones o repetir tareas. Usan condiciones booleanas (true/false) para ejecutar bloques de código específicos. if/else gestiona ramas lógicas, switch evalúa múltiples casos, y los bucles (for, while) automatizan iteraciones.

10.	¿Por qué es importante usar nombres significativos para variables y métodos?

El uso de nombres significativos para variables y métodos es crucial porque mejora la legibilidad, facilitando que otros desarrolladores (o tú mismo en el futuro) entiendan el propósito del código sin necesidad de comentarios adicionales. Esto aumenta la mantenibilidad, reduce el tiempo de depuración y previene errores al hacer el código autodocumentado y claro. 

11.	¿Qué es una variable de entorno y por qué son importantes para Javascript o la programación en general?

Las variables de entorno son pares clave-valor configurados fuera del código fuente, utilizados para almacenar configuraciones dinámicas y datos sensibles (como contraseñas o claves API). Son cruciales para separar la lógica de la aplicación de su configuración, permitiendo cambiar el comportamiento entre entornos de desarrollo y producción sin editar el código.

12.	¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?

Las Herramientas para desarrolladores de Chrome (Chrome DevTools) son un conjunto de herramientas de desarrollo web integradas directamente en el navegador Google Chrome. Permiten inspeccionar, depurar y modificar sitios web en tiempo real, facilitando el análisis del HTML, CSS, JavaScript y el rendimiento de la red, siendo accesibles con F12, Ctrl+Shift+I (Windows/Linux) o Cmd+Option+I (Mac). 

13.	¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?

El panel Elements es la herramienta más utilizada de las DevTools. Es el lugar donde puedes inspeccionar y manipular en tiempo real la estructura de una página web sin modificar el archivo original.

14.	¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil?

El panel "Console" en las herramientas de desarrollo del navegador es una herramienta fundamental para depurar, probar e interactuar con sitios web en tiempo real. Permite visualizar errores, advertencias y registros (logs) de JavaScript, ejecutar código JS directamente sobre la página actual y manipular el DOM, siendo crucial para el desarrollo frontend.

¿Cómo abrirla?
En Windows / Linux
Presiona: F12 O Ctrl + Shift + I
Luego haz clic en la pestaña: Console
También puedes abrir directamente: Ctrl + Shift + J

¿Para qué sirve?
Sirve principalmente para detectar problemas y probar código sin modificar el archivo HTML.

En desarrollo web, la consola te permite:
Encontrar errores
Ver si el código funciona
Probar instrucciones JavaScript
Inspeccionar datos
Depurar programas

15.	¿Qué información se puede obtener del panel "Network" y por qué es importante?

El panel "Network" (Red) de las herramientas de desarrollo del navegador es crucial para monitorizar, analizar y optimizar el rendimiento de sitios web. Permite visualizar qué recursos (imágenes, scripts, CSS) se cargan, su tamaño, tiempos de respuesta, códigos de estado (200, 404, 500) y cuellos de botella en tiempo real. 
