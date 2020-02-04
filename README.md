## Murió Claudio Bonadío: esto se dijo en redes sociales
### por Rodolfo Pardo - Analista de Datos


El juez federal Claudio Bonadio murió este **martes a las 6:20 en su casa de Belgrano**, según confirmaron desde su entorno a Infobae. El magistrado había cumplido 64 años hace tres días, el 1° de febrero. 

En este artículo, analizaremos las repercusiones en Twitter de la noticia.
Se analizaron un total de 12.566 tuits, 4311 usuarios y 5728 conversaciones obtenidas mediante una conexión realizada con Python a la API de Twitter.

## Cuentas populares

Se puede observar como los medios de comunicación como Radio 10, Clarín, Todo Noticias, Infobae, Big Bang News y Perfil se apoderaron de las conversaciones rápidamente saliendo a comunicar la noticia y todas sus notas relacionadas. 
![](https://www.datocms-assets.com/21842/1580841584-descarga-2-1.png)

## Geolocalización de tuits emitidos

A pesar que muchas cuentas de Twitter opten por no publicar la geolocalización de los mismos, podemos analizar los cuatro lugares más preponderantes de la muestra identificados por la red social por su gps. 

![](https://www.datocms-assets.com/21842/1580841647-descarga-3.png)

## Frecuencia de palabras

Se analizaron 2.065.805 palabras lo cual arrojó como resultado esta nube de palabras en el cual su tamaño varía por la frecuencia en los tuits emitidos. 

Se puede observar como Claudio Bonadío, Cristina Kirchner, juez, muerte, política, kirchnerismo entre otras palabras son las más frecuentes del estudio. 

![](https://www.datocms-assets.com/21842/1580842463-descarga-5.png)


## Sentimientos en Twitter ante la muerte de Bonadío

Se recopila una muestra representativa de 800 tuits que incluyeron en sus textos a la palabra "Bonadío" para realizar un análisis de sentimiento en Twitter y descifrar la expresión de los argentinos ante semejante noticia.

El algoritmo,basado en TextBlob,analiza cada tuit y arroja un número decimal; si es menor a 0.0 es negativo, si es mayor a 0.0 es positivo. Los puntos ubicados en el 0.0 son neutrales.
![](https://www.datocms-assets.com/21842/1580841899-descarga-1.png)

El resultado es claro: -2%. Los argentinos se expresaron en forma negativa en redes sociales ante la noticia de la muerte de Claudio Bonadio. 

## Relación entre Bonadio y Cristina Kirchner

Dejo este dato de color para el final. Cristina Kirchner y Gregorio Dalbón, su abogado, son las cuentas más mencionadas en Twitter junto a medios digitales.

![](https://www.datocms-assets.com/21842/1580842041-captura-de-pantalla-2020-02-04-a-la-s-15-09-10.png)

## Los hashtags más utilizados 

> #ClaudioBonadio, #QEPD, y #HabraConsecuencias son los que más se destacan. 

![](https://www.datocms-assets.com/21842/1580842134-captura-de-pantalla-2020-02-04-a-la-s-15-11-13.png)

## Horario de las conversaciones 

Al estudiar los horarios y frecuencias, se observa como la noticia explota en redes sociales en un rango que oscila entre las 08 y 09 con un gran crecimiento exponencial. 

![](https://www.datocms-assets.com/21842/1580842254-descarga-6.png)


Posteriormente, después de las 12, la noticia queda en el olvido (pero sólo para redes) 

Fuente del estudio: Twitter API / Python (TextBlob)
Autor: Rodolfo Pardo, Analista de Datos 
Código fuente: [Murió Claudio Bonadío: análisis](https://github.com/rodolfopardo/analisis_muerte_claudio_bonadio)
