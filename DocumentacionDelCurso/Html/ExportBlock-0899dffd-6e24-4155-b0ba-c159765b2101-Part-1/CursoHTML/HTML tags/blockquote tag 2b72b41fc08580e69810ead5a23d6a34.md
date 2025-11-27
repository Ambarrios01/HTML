# blockquote tag

Sobre la etiqueta `<blockquote>` en HTML.

La etiqueta **`<blockquote>`** define una sección de texto que está **citada de otra fuente**.

Normalmente, el navegador **indenta** (deja un margen hacia la derecha) el contenido de `<blockquote>` para mostrar visualmente que es una cita larga.

---

### Sintaxis básica

```html
<blockquote cite="URL-de-la-fuente">
  Aquí va el texto citado de otra página o autor.
</blockquote>

```

- **`<blockquote>`**: envuelve el texto que estás citando.
- **`cite`**: es un **atributo opcional** donde colocas la URL de la página de donde sacaste la cita.

Ejemplo (como en tu texto):

```html
<blockquote cite="https://www.goodreads.com/">
  I do not believe in taking the right decision. I take a decision and make it right.
</blockquote>

```

Al guardar y ver en el navegador:

- Verás la frase sangrada (con margen).
- El atributo `cite` no se ve directamente en la página, pero ayuda a los **navegadores y a los motores de búsqueda** a saber de dónde proviene la cita.

> Nota: Al final del texto dicen “code tag”, pero en realidad se están refiriendo a la blockquote tag.
>