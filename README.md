<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=180&section=header&text=Integradora%20I&fontSize=52&fontColor=ffffff&animation=fadeIn&desc=Pr%C3%A1ctica%203A%20%7C%20Git%20y%20GitHub%20%7C%20Markdown&descSize=18&descAlignY=72" alt="Encabezado Integradora I" width="100%"/>

<h1>📘 Integradora-Practica-3A</h1>

<p>
  <b>Control de versiones · Documentación · Desarrollo colaborativo · Respaldo del proyecto</b>
</p>

![Markdown](https://img.shields.io/badge/Markdown-Documentaci%C3%B3n-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Git](https://img.shields.io/badge/Git-Control%20de%20versiones-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Colaboraci%C3%B3n-181717?style=for-the-badge&logo=github&logoColor=white)

![Asignatura](https://img.shields.io/badge/Asignatura-Integradora%20I-6C63FF?style=flat-square)
![Pr%C3%A1ctica](https://img.shields.io/badge/Pr%C3%A1ctica-3A%20y%2003-2EA44F?style=flat-square)
![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-F5A623?style=flat-square)

</div>

---

## 🎯 Acerca de la práctica

En esta práctica aprenderemos a utilizar las herramientas de **Git** y **GitHub** para el **control de versiones**, la **documentación**, el **desarrollo colaborativo** y el **respaldo** del Proyecto Integrador de la asignatura **Integradora I**.

> [!NOTE]
> **Markdown** es el estándar utilizado por Git y GitHub para maquetar la documentación de los proyectos. Gracias a él, usuarios y colaboradores pueden entender fácilmente el contexto y la operación del proyecto.

---

## 📚 Contenido

| # | Sección | ¿Qué aprenderás? |
|:-:|:--------|:-----------------|
| 1 | [Encabezados](#encabezados) | Jerarquía de títulos del H1 al H6 |
| 2 | [Separadores](#separadores) | Divisiones visuales entre secciones |
| 3 | [Párrafos](#parrafos) | Bloques de texto y alineación |
| 4 | [Énfasis de texto](#enfasis) | Negrita, cursiva y subrayado |
| 5 | [Citas y bloques](#citas) | Resaltar instrucciones y código |
| 6 | [Listas](#listas) | Listas ordenadas y desordenadas |
| 7 | [Enlaces](#enlaces) | Hipervínculos y correos |
| 8 | [Tablas](#tablas) | Filas, columnas y celdas fusionadas |
| 9 | [Imágenes](#imagenes) | Insertar imágenes con texto alternativo |
| ⚡ | [Hoja de referencia rápida](#referencia) | Resumen de toda la sintaxis |

> **Práctica 3A** → secciones 1 a 4  ·  **Práctica 03** → secciones 5 a 9

---

# 🅰️ Práctica 3A

<a id="encabezados"></a>
## 1. Encabezados o Títulos (Headers)

Para documentar bien un proyecto hay que distribuir el contenido correctamente y **resaltar las secciones importantes**. Los encabezados se crean con el símbolo `#`: a más símbolos, menor jerarquía.

**Sintaxis:**

```markdown
# Encabezado de Nivel 1
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
##### Encabezado de Nivel 5
###### Encabezado de Nivel 6
```

| Nivel | Sintaxis | Equivalente en HTML |
|:-----:|:--------:|:-------------------:|
| 1 | `#` | `<h1>` |
| 2 | `##` | `<h2>` |
| 3 | `###` | `<h3>` |
| 4 | `####` | `<h4>` |
| 5 | `#####` | `<h5>` |
| 6 | `######` | `<h6>` |

> [!WARNING]
> Solo existen **6 niveles** dentro de la sintaxis. Con `#######` (7 símbolos) el maquetado será ignorado.

<a id="separadores"></a>
## 2. Separadores (Separators)

Para marcar una separación más visual entre contenidos se escriben **tres guiones continuos**. Es similar a la etiqueta `<hr>` de HTML.

**Sintaxis:**

```markdown
---
```

**Resultado:**

---

<a id="parrafos"></a>
## 3. Párrafos (Paragraphs)

Se utilizan para presentar grandes secciones de texto que describen de manera detallada las partes de la documentación. En Markdown basta con dejar una línea en blanco entre un párrafo y otro; también puede usarse la etiqueta HTML `<p>`.

**Sintaxis:**

```markdown
Este texto pertenece al párrafo 1.

<p>
Este texto pertenece al párrafo 2.
</p>
```

### Alineación de párrafos

También podemos aplicar estilos de alineación con el atributo `align`:

```html
<p align="left">Texto alineado a la izquierda</p>
<p align="center">Texto centrado</p>
<p align="right">Texto alineado a la derecha</p>
<p align="justify">Texto justificado</p>
```

**Resultado:**

<p align="left">
<b>Izquierda:</b> este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1. Este texto pertenece al párrafo 1.
</p>

<p align="center">
<b>Centrado:</b> este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2. Este texto pertenece al párrafo 2.
</p>

<p align="right">
<b>Derecha:</b> este texto pertenece al párrafo 3. Este texto pertenece al párrafo 3. Este texto pertenece al párrafo 3. Este texto pertenece al párrafo 3.
</p>

<p align="justify">
<b>Justificado:</b> este texto pertenece al párrafo 4. Este texto pertenece al párrafo 4. Este texto pertenece al párrafo 4. Este texto pertenece al párrafo 4. Este texto pertenece al párrafo 4. Este texto pertenece al párrafo 4.
</p>

<a id="enfasis"></a>
## 4. Texto enfatizado (Bold, Italic, Bold/Italic)

Si el texto que deseamos enfatizar se encuentra dentro de un párrafo, podemos utilizar estos recursos:

| Estilo | Sintaxis | Resultado |
|:-------|:---------|:----------|
| Cursiva (*italic*) | `*texto*` o `_texto_` | *texto* |
| Negrita (**bold**) | `**texto**` o `__texto__` | **texto** |
| Negrita y cursiva (***bold/italic***) | `***texto***` | ***texto*** |
| Tachado | `~~texto~~` | ~~texto~~ |
| Subrayado | `<ins>texto</ins>` | <ins>texto</ins> |

> [!TIP]
> Markdown **no tiene** un atajo para subrayar, por eso se utiliza la etiqueta estándar de HTML `<ins>texto</ins>`.

**Ejemplo en contexto:**

Texto texto texto **negrita** texto texto *cursiva* texto texto ***negrita y cursiva*** texto texto <ins>subrayado</ins> texto texto texto.

---

# 🅱️ Práctica 03

Continuamos con los comandos básicos de Git y GitHub para el maquetado de la documentación.

<a id="citas"></a>
## 5. Cuadros para códigos o reseñas (Blockquotes)

Se utilizan para resaltar instrucciones específicas de **instalación**, **configuración** o **inicialización**, o para mostrar secciones de código fuente. Se maquetan iniciando la línea con el símbolo de mayor que `>`.

**Sintaxis:**

```markdown
> Aquí se ingresa un conjunto de instrucciones para explicar al usuario
> cómo instalar el software que hemos diseñado.
```

**Resultado:**

> Aquí se ingresa un conjunto de instrucciones para explicar al usuario cómo instalar el software que hemos diseñado.

También podemos incluir **viñetas** dentro de la cita para enlistar pasos:

> **Pasos para instalar la base de datos**
>
> - Descargar MySQL Server del sitio oficial.
> - Instalar el Sistema Gestor de Bases de Datos, definiendo el puerto y la contraseña para el usuario `root`.
> - Descargar el archivo de respaldo de la base de datos (`.sql`).
> - Restaurar la base de datos con el comando `mysql`:
>   `"C:/Program Files/MySQL/MySQL Server 8.0/bin/mysql" -u root -p < respaldo.sql`

<details>
<summary>✨ <b>Extra: alertas de GitHub</b> (clic para ver)</summary>

<br>

GitHub permite resaltar las citas con alertas de colores:

```markdown
> [!NOTE]
> Información útil que el usuario debería conocer.

> [!TIP]
> Consejo para hacer las cosas mejor.

> [!IMPORTANT]
> Información clave para lograr el objetivo.

> [!WARNING]
> Contenido que requiere atención inmediata.

> [!CAUTION]
> Advierte sobre posibles riesgos o consecuencias negativas.
```

> [!NOTE]
> Información útil que el usuario debería conocer.

> [!TIP]
> Consejo para hacer las cosas mejor.

> [!IMPORTANT]
> Información clave para lograr el objetivo.

> [!WARNING]
> Contenido que requiere atención inmediata.

> [!CAUTION]
> Advierte sobre posibles riesgos o consecuencias negativas.

</details>

<a id="listas"></a>
## 6. Listas ordenadas y desordenadas

Si necesitamos presentar información como una lista, un elemento tras otro, usamos **números con punto** para listas ordenadas y un **guion medio** `-` para listas con viñetas.

**Sintaxis:**

```markdown
1. Primer paso
2. Segundo paso
   - Sub-elemento A
   - Sub-elemento B
```

**Ejemplo:** para crear tu primer repositorio en GitHub deberás:

1. Contar con una cuenta de GitHub.
2. Dar clic en el botón **Nuevo repositorio**.
3. Asignarle un nombre a tu repositorio, por ejemplo: `practica03-3b`.
4. Asignarle un nivel de privacidad:
   - **Público:** si quieres que esté disponible para todos los usuarios.
   - **Privado:** si deseas que solo quienes tú decidas puedan ver y colaborar en tu proyecto.
5. Definir si incluirá un archivo de descripción llamado `README.md`.
6. Definir si habrá exclusiones de archivos a través del archivo `.gitignore`.
7. Guardar los cambios.

<a id="enlaces"></a>
## 7. Ligas (Hipervínculos)

Las ligas vinculan elementos o referencias del proyecto, dentro o fuera del repositorio. Se maquetan con corchetes `[]` para el texto, seguidos inmediatamente de la dirección entre paréntesis `()`.

**Sintaxis:**

```markdown
[Texto de la liga](https://www.google.com/)

<https://www.google.com/>

<correo@ejemplo.com>
```

**Resultado:**

Mi buscador favorito es: [Google](https://www.google.com/).

Si deseamos poner solo la liga directa o un correo electrónico, usamos los símbolos `< >`: <https://github.com/> · <230317@utxicotepec.edu.mx>

<a id="tablas"></a>
## 8. Tablas

Podemos presentar información en filas y columnas. Se usa el carácter `|` para delimitar columnas y `-` para la línea de encabezado.

**Sintaxis:**

```markdown
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|:-------------|:------------:|-------------:|
| Izquierda    |   Centro     |      Derecha |
```

**Resultado:**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|:-------------|:-------------|:-------------|:-------------|
| Fila 1 Celda 1 | Fila 1 Celda 2 | Fila 1 Celda 3 | Fila 1 Celda 4 |
| Fila 2 Celda 1 | Fila 2 Celda 2 | Fila 2 Celda 3 | Fila 2 Celda 4 |
| Fila 3 Celda 1 | Fila 3 Celda 2 | Fila 3 Celda 3 | Fila 3 Celda 4 |

### Fusión de celdas

> [!IMPORTANT]
> Con Markdown puro **no se pueden fusionar** celdas. Para lograrlo se usa el estándar HTML con las etiquetas `<table>`, `<tr>`, `<th>` y `<td>`, junto con las propiedades **`colspan`** (fusionar columnas) y **`rowspan`** (fusionar filas).

<details>
<summary>🧩 <b>Ver el código HTML de la tabla</b></summary>

```html
<table>
  <tr>
    <th>Encabezado 1</th>
    <th>Encabezado 2</th>
    <th>Encabezado 3</th>
    <th>Encabezado 4</th>
  </tr>
  <tr>
    <td>Fila 1 Celda 1</td>
    <td>Fila 1 Celda 2</td>
    <td>Fila 1 Celda 3</td>
    <td>Fila 1 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 2 Celda 1</td>
    <td colspan="3" align="center">Fila 2 Celda 2 (colspan=3)</td>
  </tr>
  <tr>
    <td rowspan="3">Fila 3 Celda 1 (rowspan=3)</td>
    <td>Fila 3 Celda 2</td>
    <td>Fila 3 Celda 3</td>
    <td>Fila 3 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 4 Celda 2</td>
    <td>Fila 4 Celda 3</td>
    <td>Fila 4 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 5 Celda 2</td>
    <td>Fila 5 Celda 3</td>
    <td>Fila 5 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 6 Celda 1</td>
    <td>Fila 6 Celda 2</td>
    <td>Fila 6 Celda 3</td>
    <td>Fila 6 Celda 4</td>
  </tr>
</table>
```

</details>

**Resultado:**

<table>
  <tr>
    <th>Encabezado 1</th>
    <th>Encabezado 2</th>
    <th>Encabezado 3</th>
    <th>Encabezado 4</th>
  </tr>
  <tr>
    <td>Fila 1 Celda 1</td>
    <td>Fila 1 Celda 2</td>
    <td>Fila 1 Celda 3</td>
    <td>Fila 1 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 2 Celda 1</td>
    <td colspan="3" align="center">Fila 2 Celda 2 (colspan=3)</td>
  </tr>
  <tr>
    <td rowspan="3">Fila 3 Celda 1 (rowspan=3)</td>
    <td>Fila 3 Celda 2</td>
    <td>Fila 3 Celda 3</td>
    <td>Fila 3 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 4 Celda 2</td>
    <td>Fila 4 Celda 3</td>
    <td>Fila 4 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 5 Celda 2</td>
    <td>Fila 5 Celda 3</td>
    <td>Fila 5 Celda 4</td>
  </tr>
  <tr>
    <td>Fila 6 Celda 1</td>
    <td>Fila 6 Celda 2</td>
    <td>Fila 6 Celda 3</td>
    <td>Fila 6 Celda 4</td>
  </tr>
</table>

<a id="imagenes"></a>
## 9. Imágenes

Se muestra una imagen escribiendo `!` seguido del **texto alternativo** entre corchetes `[ ]` y, por último, el vínculo de la imagen entre paréntesis `()`. El texto alternativo es una descripción corta equivalente a la información de la imagen.

**Sintaxis:**

```markdown
![Texto alternativo](https://ruta-de-la-imagen.com/imagen.jpg)
```

**Resultado:**

<div align="center">

![Imagen demostrativa](https://i.pinimg.com/736x/91/93/b1/9193b1011e9954b3f062181a6829351e.jpg)

</div>

> [!NOTE]
> GitHub admite la inserción de imágenes en incidencias, solicitudes de incorporación de cambios (*pull requests*), debates, comentarios y archivos `.md`. Puedes mostrar una imagen desde tu repositorio, agregar un enlace a una imagen en línea o cargar una imagen directamente.

---

<a id="referencia"></a>
## ⚡ Hoja de referencia rápida

| Elemento | Sintaxis |
|:---------|:---------|
| Encabezado | `# Título` · `## Subtítulo` |
| Separador | `---` |
| Negrita | `**texto**` |
| Cursiva | `*texto*` |
| Negrita y cursiva | `***texto***` |
| Subrayado | `<ins>texto</ins>` |
| Cita | `> texto` |
| Lista con viñetas | `- elemento` |
| Lista numerada | `1. elemento` |
| Código en línea | `` `código` `` |
| Enlace | `[texto](url)` |
| Imagen | `![alt](url)` |

---

<div align="center">

## 👩‍💻 Autora

Documentación creada por **_Jennifer Bautista Barrios_**

[![Correo](https://img.shields.io/badge/Correo-230317%40utxicotepec.edu.mx-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:230317@utxicotepec.edu.mx)

<sub>Universidad Tecnológica de Xicotepec de Juárez · Integradora I</sub>

<br>

⭐ Si te sirvió este repositorio, ¡déjale una estrella! ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" alt="Pie de página" width="100%"/>

</div>
