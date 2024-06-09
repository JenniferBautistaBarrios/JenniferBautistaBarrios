
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

Ejemplo Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto Texto Texto</ins> Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto Texto Texto</ins> Texto Texto Texto Texto Texto Texto

# Integradora-Practica03
Continuamos con los comandos básicos de Git y GitHub para el maquetado de la documentación

### 5. Cuadros para códigos o reseñas (BLOCKQUOTES)
Estos elementos son utilizados para resaltar instrucciones especificas para la instalación, configuración y/o inicialización o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (/>)

EJEMPLO:
Para listar las carpetas y archivos desde una terminal de sistemas operativos Windows debemos ingresar el comando: c:dir Después oprimimos la tecla "Enter".

> Aquí se ingresa un conjunto de instrucciones para explicar al usuario, como instalar el software que hemos diseñado.

También podemos ingresar textos multilínea

Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el caracter - dentro del texto a documentar.

Ejemplo: Pasos para Instalar la Base de Datos

> - Descargar MySQL Server del Sitio Oficial
> - Instalar el Sistema Gestor de Bases de Datos, definiendo el puerto y contraseña para el usuario root
> - Descargamos el archivo de respaldo de la base de datos (.sql)
> - Restauramos la Base de Datos Usando el comando *MySQL *
> - c:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password<respaldo.sql

### 6. Listas Ordenadas y Listas Desordenadas
Si en nuestra documentación necesitamos incluir información en modo de lista, un elemneto tras otro, podemos hacerlo utilizando los números con un punto decimal si las deseamos ordenadas con un guión medio - si solo queremos una viñeta.

Ejemplo: 
Para crear tu primer repositorio en GitHub deberás:

1. Contar con cuneta HitHub.
2. Dar click en el boton: *Nuevo repositorio
3.Asignarle un Nombre a tu repositorio, por ejemplo: practica03-3b
4. Asignarle un nivel de privacidad entre}
    - Públuico: Si quieres que esté disponible para todos los usuarios.
    - Privado: Si deseas que solo a quien tu decidas puedan y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripción llamado : READNE.md
6. Definir si habrá exclusiones de archivo a través del archivo .gitgnore
7. Guardar los cambios.

### 7. Ligas(Hipervínvulos)
Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y que se maquetan utilizando los corchetes [], inmediatamente despues pondrémos la liga de referencia entre parentesis ().

Ejemplo: 
Mi buscador favorito es: [Google](https://www.google.com/).

Pero si deseamos poner solo las ligas directas o un correo electrónico podemos utilizar los simbolos < >

Ejemplo: 
Documentación creada por: _**Jennifer Bautista Barrios**_

<230317@utxicotepec.edu.mx>

### 8. Imágenes
Puede mostrar una imágen agregando ! y ajustar el texto alternativo en [ ]. El texto alternativo es un texto corto equivalente a la información de la imágen. Luego escribe el vinculo de la imágen entre paréntesis ().
![Imagen demostrativa](https://i.pinimg.com/736x/91/93/b1/9193b1011e9954b3f062181a6829351e.jpg)

GitHub admite la inserción de imágenes en incidencias, solicitudes de incorporación de cambios, debates, comentarios y archivos .md. Puedes mostrar una imagen desde tu repositorio, agregar un enlace a una imagen en línea o cargar una imagen. Para obtener más información, consulte "Carga de recursos".

