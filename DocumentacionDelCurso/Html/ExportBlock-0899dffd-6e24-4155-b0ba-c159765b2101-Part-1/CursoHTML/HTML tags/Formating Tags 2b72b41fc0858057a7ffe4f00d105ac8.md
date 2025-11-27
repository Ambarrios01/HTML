# Formating Tags

Sobre las etiquetas de formato (formatting tags).

Las etiquetas de formato fueron diseñadas para mostrar tipos especiales de texto.

En este tema veremos las siguientes etiquetas:

- Etiquetas **`<b>`** y **`<strong>`**
- Etiquetas **`<i>`** y **`<em>`** (énfasis)
- Etiqueta **`<mark>`**
- Etiqueta **`<small>`**
- Etiquetas **`<del>`** y **`<ins>`**
- Etiquetas **`<sub>`** y **`<sup>`**

---

### `<b>` y `<strong>`

Empecemos con la etiqueta **`<b>`**.

Si escribo `<b>` y luego presiono Tab, se crea la etiqueta `<b>...</b>`. Se usa para crear **texto en negrita**.

Ejemplo de texto:

> I am a bold text
> 
> 
> (Soy un texto en negrita)
> 

Si guardo con **Ctrl + S** y abro la página en el navegador, verás el texto en negrita.

Si uso la etiqueta **`<strong>`** y escribo:

> I am a strong text
> 
> 
> (Soy un texto importante)
> 

Al actualizar la página, también se muestra en negrita.

Hago un salto de línea usando la etiqueta `<br>`.

Puedes ver:

- I am a bold text
- I am a strong text

Visualmente **no hay diferencia** entre estas dos líneas: ambas se ven en negrita.

La diferencia es semántica:

- La etiqueta **`<b>`** solo indica **negrita**, sin importancia extra.
- La etiqueta **`<strong>`** indica que el texto tiene **fuerte importancia**. El contenido dentro de `<strong>` normalmente se muestra en negrita, pero además los buscadores y el navegador lo interpretan como texto importante.

---

### `<i>` y `<em>`

Pasemos al texto enfatizado.

Creamos texto en cursiva usando **`<i>`** o **`<em>`**.

Por ejemplo:

- Con `<i>`: *I am italic text* (estoy en cursiva).
- Con `<em>`: *I am emphasize text* (estoy enfatizado).

Al actualizar la página, se ve:

- Texto en cursiva con `<i>`
- Texto en cursiva con `<em>`

No hay diferencia visual entre estas dos líneas: las dos se ven en **cursiva**.

La diferencia es semántica:

- La etiqueta **`<i>`** indica solo un **estilo en cursiva**.
- La etiqueta **`<em>`** indica **énfasis**. Los lectores de pantalla suelen pronunciar el texto dentro de `<em>` con énfasis (mayor intensidad o presión en la voz).

---

### `<small>`

La siguiente etiqueta es **`<small>`**, que se usa para mostrar **texto más pequeño**.

Al actualizar la página, verás que el texto dentro de `<small>` se muestra con un tamaño de fuente más pequeño.

---

### `<mark>`

La siguiente etiqueta es **`<mark>`**.

Se utiliza para **resaltar texto**, normalmente con un fondo amarillo, como si fuera un marcador.

Ejemplo:

> <mark>This is highlighted</mark>
> 
> 
> Mostrará el texto resaltado con fondo amarillo.
> 

---

### `<del>` y `<ins>`

La etiqueta **`<del>`** define texto que ha sido **eliminado** de un documento.

El navegador normalmente muestra el texto con una **línea tachada**.

Ejemplo:

> <del>Old text</del>
> 
> 
> se mostrará tachado.
> 

La etiqueta **`<u>`** (en algunos ejemplos) se usa para **subrayar texto**, pero hoy en día se prefiere usar CSS para esto.

Existe también la etiqueta **`<ins>`**, que significa **inserted text** (texto insertado). Semánticamente indica texto nuevo agregado al documento. El navegador normalmente lo muestra **subrayado**. Visualmente puede verse igual que `<u>`, pero:

- `<del>` → texto eliminado (tachado)
- `<ins>` → texto insertado (subrayado)

Ejemplo práctico:

```html
<p>My favorite color is <del>blue</del> <ins>black</ins>.</p>

```

En la página se verá algo así:

> My favorite color is blue <u>black</u>
> 

Es decir, “blue” está eliminado y “black” está insertado. El lector entiende que ahora tu color favorito es **negro**.

---

### `<sub>` (subíndice)

La etiqueta **`<sub>`** define texto en **subíndice**.

El subíndice aparece un poco **por debajo** de la línea normal y a veces con una fuente más pequeña.

Se usa, por ejemplo, en fórmulas químicas, como:

- Escrito normal: `H2O`
- Con subíndice:

```html
H<sub>2</sub>O

```

Esto se verá como **H₂O** correctamente en la página.

---

### `<sup>` (superíndice)

La etiqueta **`<sup>`** define texto en **superíndice**.

El superíndice aparece un poco **por encima** de la línea normal y también puede ser más pequeño.

Se usa, por ejemplo, en potencias o notas al pie:

- `x<sup>2</sup>` → x²
- `Note<sup>1</sup>` → Note¹

---

Al final:

- `<b>` / `<strong>` → negrita (con o sin importancia semántica)
- `<i>` / `<em>` → cursiva (con o sin énfasis semántico)
- `<small>` → texto pequeño
- `<mark>` → texto resaltado
- `<del>` → texto eliminado (tachado)
- `<ins>` → texto insertado (subrayado)
- `<sub>` → subíndice
- `<sup>` → superíndice

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formating tags</title>
</head>
<body>
    Bold Tag: <b>I am a bold text.</b> <br>
    Strong Tag: <strong>I am a strong text.</strong> <br>

    Italic Text: <i>I am a italic text.</i><br>
    Emphasized Text: <em>I am a Emphasized text.</em> <br>

    Small Text: <small>I am a small text</small> <br>
    Marked Text: <mark>I am a marketed Text</mark> <br>

    Deleted Text: <del>I am a del text.</del> <br>

    Underline Text: <u>I am a underline text.</u> <br>
    Inserted Text: <ins>I am a inserted Text.</ins> <br>
    
<p>My favorite color is <del>blue</del> <ins>black</ins>. </p> <br>

Subscript Text: H<sub>2</sub>O <br>
Superscript Text: 10<sup>2</sup>

</body>
</html>
```

![image.png](Formating%20Tags/image.png)