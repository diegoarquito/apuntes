# APUNTES XML 03/11/2023

<h1>CCS - Hojas de estilo para dar formato a HTML </h1>

<h3>¿Qué es?</h3>

Es un lenguaje de diseño gráfico para definir y crear la presentación de un documento estructurado escrito en un lenguaje de marcado.​
<ol>
    <li>Si no queremos afectar a solo uno, sino a todos, lo pondremos en el head, para que todos se vean afectados.
    <li>Para modificar una tabla entero pondremos (style="color:red;"), dentro de head en la tabla. Si quieres definir mejor los bordes ponemos dentro de las comillas (text-align:center) este es para quede centrado, pero podemos poner "right" "left". Si queremos afectar a solo un elemento lo ponemos dentro del codigo de solo una fila.
    <li>Dentro de body para solo afectar a las filas y rellenarlos con color, ponemos (style="background-color: rgb(104, 104, 13);")
</ol>
Para editar colores tenemos que modificar los numeros RGB, signfica rojo verde y azul, mezclando los colores primarios conseguiremos colores. Dentro del head para editar todos los valores ponemos la declarion de style y dentro de style ponemos tbody[color:#0000ff], para que solo afecte al body.
<br>
<br>

Por ejemplo:Para añadir estilos en CSS ponemos la etiqueta style

```
<DOCTYPE html>
<html>
<head>
    <title>color apuntes</title>
    <style="color:red;">
</head>
<body>
<ol>
    <p>Este es un ejemplo de una página web simple.</p> <style="background-color:rgb(104,104,13);">
</ol>
</body>
</html>
```

Esto sirve para ir mas rapido y poder editar de manera mas rapida.

Para poder afectar a elementos particulares, tenemos que definir esa etiqueta, y ponerle un atributo de identificación (id="primerafila"), y para asignar una etiqueta y afectar un identificador ponemos # dentro de head.

Una clas es un conjunto de elemntos que agrupamos apra que tengan la mismas caracteristicas, con la etiqueta class (class="textoazul"). Y en el head ponemos #textoazul[color:#0000ff].

```
<DOCTYPE html>
<html>
<head>
    <title>color apuntes</title>>
 <style>
    textozul[color:#00000ff]
</style>
</head>
<body>
<ol>
    Este es un ejemplo de una página web simple. <style="background-color:rgb(104,104,13);">

    Hola <class="textoazul">

</ol>
</body>
</html>
```