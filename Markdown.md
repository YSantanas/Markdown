# Markdown
Markdown desde cero

## ¿Qué es Markdown?

Es un lenguaje de marcado, markdown puede convertirse en HTML.
Existen herramientas que hacen esta conversión, como es el caso de dillinger.

[Enlace](https://dillinger.io/)

En dicha herramienta tendremos la pantalla dividida en dos, a la izquierda tendremos nuestro codigo en Markdown, y a la derecha tendremos ese código convertido con las etiquetas propias de HTML.

![Texto alternativo](img/img1.png "Captura de pantalla del ejemplo.")

![Texto alternativo](img/img2.png "Captura de pantalla del ejemplo con etiquetas.")  

Cuando seguimos escribiendo en el siguiente renglón, en realidad estamos haciendo  un ``<br>``, entonces si queremos un cambio de párrafo se debe dar dos saltos.

## Sintaxis
Markdown tiene su propia sintaxis, para lograr tener ciertas etiquetas, como es el caso de los encabezados.

### Encabezados

h1 -> #
h2 -> ##
h3 -> ###
h4 -> ####

Markdown entiende que esos titulos tendran id, como veremos en la captura siguiente:

![Texto alternativo](img/img3.png "Id generados automaticamente por Markdown.")  

### Listas
Las listas tambien tienen su propia sintaxis, hay que recordar que en HTML, una lista desordenada se representa con ``<ul> </ul>``.


![Texto alternativo](img/img4.png "Listas.")  

Como podemos notar, si dejamos espacio entre el * (asterisco) y el inicio del texto, podremos anidar dicha lista.

![Texto alternativo](img/img5.png "Captura del Markdown en HTML.")  

Si quisieramos listas ordenadas su sintaxis es bastante sencilla, solo tendriamos que colocar los numeros que deseamos.

![Texto alternativo](img/img6.png "Lista ordenada en Markdown.")  

![Texto alternativo](img/img7.png "Lista ordenada en HTML.")  

### Imagenes

La sintaxis para las imagenes varian bastante con lo visto con anterioridad.

``![Texto ALT](Enlace)``

El texto alternativo debemos recordar que es una buena práctica colocarlo.  

![Texto alternativo](img/img8.png "Mostrar imagenes con Markdown.")  

Mientras que en el código HTML, se mostrara lo siguiente.

![Texto alternativo](img/img9.png "Captura del HTML.")  

### Enlaces

La forma de colocar enlaces es muy similar, solamente se elimina el signo de explamación.

``[titulo que se muestra](ENLACE)``

![Texto alternativo](img/img10.png "Enlace en Markdown.")  

Como podemos ver, es bastante sencillo colocar un enlace.  

![Texto alternativo](img/img11.png "Código en HTML.")  

Hay atajos para poder poner enlaces de manera consecutiva y para ello solo debemos poner corchetes en aquellas palabras, que deseamos que nos retorne a un enlace y posteriormente, en un parrafo aparte, hacer una asignación.


Ejemplo:

``[Pelicula] : enlace.com``

![Texto alternativo](img/img12.png "Enlaces consecutivos en un parrafo.")  

En este caso se guarda unicamente en el Markdown, sin verse repetido. Se puede hacer de manera analoga con la imagen para los enlaces.

![Texto alternativo](img/img13.png "Atajo para la imagen.")  

### Código

Para insertar código se debe usar palabas reservadas, como es el caso de las variables  se pone entre comillas.

![Texto alternativo](img/img14.png "Uso de variables.")  

Para un bloque de codigo completo se utiliza las mismas comillas  pero serian tres de abertura y tres de cierre, además se puede aclarar el lenguaje del que se trata.

![Texto alternativo](img/img15.png "Inserción de código.")  


Cuando se coloca el lenguaje concreto que tenemos en el bloque, podemos ver  una mejor presentación.

![Texto alternativo](img/img16.png "Visualización del código.")  

El código de este bloque queda de la siguiente forma:

![Texto alternativo](img/img17.png "Código en HTML del bloque.")  

Una libreria recomendada es la siguiente:

[Enlace para colorear código](https://prismjs.com/)  


Esto se usa para poder colorear el código de markdown, para ello se utiliza el css y js.


### Estilo del texto

Para escribir en negrita, se utiliza doble asterisco al inicio y al final. 


#### Negrita

![Texto alternativo](img/img18.png "Poner el texto en negrita.")  


![Texto alternativo](img/img19.png "Código en HTML del texto en negrita.")  

Para colocar el texto en estilo italica, se necesita tres astericos de abertura y otros tres de cierre.

#### Italica

![Texto alternativo](img/img20.png "Texto en italica.")  


![Texto alternativo](img/img21.png "Código de italica en HTML.")  

#### Citas

Para realizar citas unicamente se usa el simbolo de "mayor que", como se muestra en la siguiente imagen.

![Texto alternativo](img/img22.png "Colocando Citas en Markdown.")  

![Texto alternativo](img/img23.png "Código en HTML de la misma cita.")  

