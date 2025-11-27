# Paragraph HTML

Sobre los párrafos.

La etiqueta `<p>` en HTML define un párrafo.

Un párrafo siempre comienza en una nueva línea y los navegadores agregan automáticamente un poco de espacio (un margen) antes y después de un párrafo.

Ahora empecemos con la parte de código. Para crear una etiqueta de párrafo (`p`), simplemente escribo `p` y luego presiono **Tab**, y se crean la etiqueta de apertura y la etiqueta de cierre.

Estoy escribiendo un texto:

> This is a paragraph.
> 
> 
> (Este es un párrafo).
> 

Estoy creando otro párrafo simplemente escribiendo `p` y después presionando el botón **Tab**.

Y luego escribo otro texto:

> This is a…
> 
> 
> (Este es un…).
> 

Guardo el archivo usando **Ctrl + S**.

Después abro este archivo en el navegador.

Entonces, este es un párrafo y este es otro párrafo.

Puedes ver que se crea un margen, un espacio antes y después del párrafo.

Y lo mismo puedes ver en el segundo párrafo: crea un espacio antes del párrafo y después del párrafo.

Si creo otro párrafo, comenzará en otra línea.

Esto significa que el párrafo es un **elemento de bloque**: siempre empieza en una nueva línea.

A veces no puedes estar seguro de cómo se mostrará HTML:

en una pantalla grande, en una pantalla pequeña, o al redimensionar la ventana, se pueden obtener resultados diferentes con el HTML.

No puedes cambiar la forma en que se muestra el texto añadiendo espacios extra o líneas extra en tu código HTML.

El navegador eliminará automáticamente cualquier espacio extra y líneas extra cuando se muestre el párrafo.

Por ejemplo, estoy creando otro párrafo con texto.

Aquí he creado otro párrafo con algunas palabras.

Empiezo algunas palabras en una nueva línea presionando la tecla **Enter**.

Vamos a revisar el resultado: puedes ver que el navegador elimina los espacios en blanco adicionales y las líneas nuevas.

Si coloco varios espacios y presiono **Ctrl + S**, verás que **no hay diferencia en el resultado**.

Entonces, si quieres forzar un salto de línea dentro de un mismo párrafo, ¿qué puedes hacer?

Aquí está la solución:

Puedes usar otra etiqueta, que es `<br>`, que significa **salto de línea**.

Si guardo el archivo y veo el resultado, verás que rompe la línea.

Así que usa siempre la etiqueta `<br>` (line break) cuando quieras empezar un texto en una nueva línea **sin crear un nuevo párrafo**.

Si quieres separar secciones, puedes usar otra etiqueta que es `<hr>`, la etiqueta de **regla horizontal**.

Si la creo aquí y reviso el resultado, verás que aparece una línea horizontal.

Aquí y aquí puedes ver la diferencia.

Ahora, hay un problema:

Si quiero escribir un poema usando la etiqueta de párrafo, al actualizar la página, mostrará todo el texto en una sola línea (respetando solo los párrafos, no los saltos manuales de línea del código).

Pero yo no quiero que se muestre en una sola línea, quiero que se muestre con el mismo formato (saltos de línea y espacios) que escribí en el código.

¿Cuál es la solución?

Hay una etiqueta muy útil: `<pre>`.

La etiqueta `<pre>` mostrará el texto **con el mismo formato** que tienes en el código fuente: respeta espacios, saltos de línea y tabulaciones.

Así que puedes verlo aquí.

Espero que hayas aprendido mucho en esta sección.

Sigue aprendiendo.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <p>this is a paragraph</p>
    <hr>
    <p>this is a paragraph</p>
    <hr>
    <p>
      this a paragraph containss a lot of lines <br />
      in the source code but the browser ingnores it.
    </p>
    <hr>
    <p>
     <pre>
             you do not do, you do not do
            Any more, black shoe 
            In whic I have lived like a foot
            For thirty years, Porr and white,
            barrely daring to breathe or achoo.
     </pre>
    </p>
  </body>
</html>

```

![image.png](Paragraph%20HTML/image.png)