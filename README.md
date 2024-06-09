
# Integradora-Practica-3A

En esta practica aprenderemos a utilizar las herramientas de Git y Github para el control de Versiones, Documentacion, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la asignatura de Integradora I

## Comandos Básicos para la Documentación, utilizando el estandar se Markdown (md)
Markdown es el estandar utilizado por Git y Github, para maquetar la documentacion de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operacion del mismo

### 1. Encabezados o Titulos (Headers)
Para poder realizar una buena documentacion del proyecto debemos, distribuir correctamente el contenido, para poder delimitar o hacer enfasis (enfatizar), es deir resaltar las secciones importantes, podemos utilizar los siguientes:

EJEMPLOS:
# Encabezado de Nivel 1 - Similar a H1 en HTML
## Encabezado de Nivel 2 - Similar a H2 en HTML
### Encabezado de Nivel 3 - Similar a H3 en HTML
#### Encabezado de Nivel 4 - Similar a H4 en HTML
##### Encabezado de Nivel 5 - Similar a H5 en HTML
###### Encabezado de Nivel 6 - Similar a H6 en HTML
####### Encabezado de Nivel 7 - Solo 6 niveles son permitidos dentro de la sintaxis, a partir de este el maquetado sera ignorado

### 2. Separadores (SEPARATORS)
Si se desea marcar una separacion mas visual de contenidos podemos utilixarlos indicando tres caracteres de "-" continuos en el maquetado

EJEMPLO:
---

"Esto es similar a un tag de <HR> en HTML.

### 3. Párrafos (Paragraphs)
Son utilizafos para poder presentar grandes secciones de texto que describen deetalladamentelas secciones de la documentacion del proyecto

EJEMPLOS:

Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1.

<p>
Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2.  </p>

Lo que en una pagina utilizariamos la etiqueta < P >

tambien podemos aplicar estilos de alineacion:

<p align = left>
Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). 
Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). 
Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho). Este texto pretenece al Parrafo 1 (Derecho).  </p>

<p align = center>
Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado). Este texto pretenece al Parrafo 2 (Centrado).   </p>

<p align = right>
Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo). Este texto pretenece al Parrafo 3 (Izquierdo).  </p>

<p align = justify>
Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado). Este texto pretenece al Parrafo 4 (Justificado).  </p>

### 4. Texto Enfatizado (BOLD, ITALIC, BOLD/ITALIC)
Si el texto que deseamos enfatizar se encuentra en un parrafo podemos utilizar algunos trucos para ubicarlos en la documentación

#### Texto en negrita (BOLD)
Para poder poner el texto en negrita este debera ser encerrado entre dos *.

EJEMPLO:
Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

#### Texto en cursiva (ITALIC)
Para poder poner el texto en cursiva este debera ser encerrado entre dobles **.

EJEMPLO:
Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto **Texto** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto


#### Texto en negrita cursiva (BOLD/ITALIC)
Para poder poner el texto en negrita y ademas en cursiva este debera ser encerrado entre triples ***.

EJEMPLO:
Texto Texto Texto ***Texto*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

#### Subrayado (UNDERLINE)
Algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo estándar de HTMl usando el tag / y cerrando con /

Ejemplo Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto _Texto Texto Texto_ Texto Texto Texto Texto Texto Texto


