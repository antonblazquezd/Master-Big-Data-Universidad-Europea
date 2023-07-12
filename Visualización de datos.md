 # Visualización de Datos 

Profesor: Sandra Becker


# Contenido del Curso

- Objetivos 
- Unidad 1. Introducción a la visualización de datos
    - Introducción a la visualización de datos
    - Tipos de visualizaciones
    - Visual Encoding
    - Percepción humana
- Unidad 2. Visualización de datos en la práctica
    - Hands on: Visualización dinámica
    - ¿Qué es una buena visualización?
    - Elementos de la interactividad
    - Animación en la visualización
- Unidad 3. Visualización dinámica Parte (I)
    - Introducción
    - Manipular y preparar datos
    - Análisis exploratorio de datos (EDA)
    - Conceptos principales
- Unidad 4. Visualización dinámica Parte (II)
    - Visualizaciones simples
    - Visualizaciones animadas
    - Visualizaciones interactivas
    - Visualizaciones avanzadas
- Unidad 5. Visualización de datos geolocalizados
    - Introducción
    - Opciones de styling & scaling
    - Location Intelligence a través del análisis
    - Interactividad con los widgets y publicación
- Unidad 6. Visual Storytelling en la practica
    - Introducción al mundo de Visual Storytelling
    - Creación de una historia visual
    - Lenguaje visual
    - Conceptos: Scrollytelling, Martini Glass Structure, Drill-down


# Objetivos

## Competencias específicas:
-  CE2. Aplicar las bases teórico-prácticas necesarias sobre Tecnologías de la Información y Comunicaciones de interés para el desarrollo e implantación de servicios de análisis y ex-tracción de modelos a partir de los datos en infraestructuras de altas prestaciones.
- CE4. Diseñar y ejecutar un proceso completo de descubrimiento de conocimiento, inclu-yendo las fases de almacenamiento, procesamiento y visualización de los datos.
- CE9. Evaluar las posibilidades de la gestión masiva de datos y la inteligencia artificial en el desarrollo del negocio en los diferentes sectores de aplicación (banca, salud, comunicacio-nes, gobierno, etc.).
- CE10. Investigar tendencias técnicas en tecnologías y procesos de descubrimiento de infor-mación y generación de conocimiento a partir de los datos.
- CE11. Aplicar las diferentes metáforas de visualización, analíticas visuales, y tecnología necesaria para mejorar la interpretación de los datos en el proceso de interacción hombre-máquina.
## Resultados de aprendizaje:
- RA1. Conocer las diferentes metáforas de visualización y tecnología necesaria para mejorar la interpretación de grandes volúmenes de datos.
- RA2. Diseñar visualizaciones en diversos dominios de aplicación.
- RA3: Conocer los procesos de diseño e implantación de soluciones en diferentes dominios.
- RA4: Diseñar soluciones que ayuden a la toma de decisiones.


# Unidad 1. Introducción a la visualización de datos

## Objetivos
Los objetivos que se pretenden alcanzar con este recursos son los siguientes: 
- Conocer el mundo y cómo se define la visualización de datos
- Aprender los objetivo sy el por qué de la visualización de datos. 
- Familiarizarse con el flujo de la creación a través de algunos ejemplos. 

## Intro

### ¿Qué significa la visualización de datos? 

![](/img/visualizacion/insights.png)

> El objetivos de la visualización es de elucidar a las personas. No es de entretener a ellos, no es de vender productos, servicios o ideas a ellos, es de informarles. Es tan fácil  y tan complicado como eso. - A. Cairo. 

### Flujo de la Creación 

![](/img/visualizacion/flujo_creacion.png)


¿Para qué necesitamos visualizar los datos? 

- Para entender los datos de manera sencilla
- Para tomar decisiones rápidamente.
- Proponer nuevas preguntas
- Conoctar ideas. 
- Responder a preguntas. 
- Mostrar patrones
- Descubrir los unknown unknowns. 


### Caso de uso: ¿Cómo ha cambiado el Big Data a la visualización de datos? 

- La compilación de muchos datos en pocas gráficas. 
- Le agrega complejidad, para la limpieza y el procesamiento de datos. 

> It's not what you look at what matters, it's what you see. - H. Thoreau

> The purpose of data visualization are insights, not pictures. - B. Schneidermann 

> Let my dataset change your mindset- H. Rosling

> The purpose of data visualizations is to englighten people. Not to entertain them, not to sell them products, services or ideas, but to inform them. It's as simple and as complicated as that. - A. Cairo

> Above all else, show the data. - E. Tufte

![](/img/visualizacion/big_data.png)

El big data nos permite hacer un zoom out enorme de nuestros datos para encontrar patrones, que con una cantidad de datos menor, no seríamos capaces de detectar. 

![](/img/visualizacion/big_data_2.png)


![](/img/visualizacion/big_data_3.png)


### Caso de uso: Predicción 

Las predicciones tienen mucho peso hoy en día, pero son naturalmente inciertas, lo cual se puede representar visualmente con la transparencia por ejemplo. 

Si vamos a generar predicciones, también tenemos que calcular la predicción de que ocurra dicha predicción. 

![](/img/visualizacion/big_data_4.png)

![](/img/visualizacion/pasos.png)

### Caso de uso: simulación 

![](/img/visualizacion/simulacion.png)


### Caso de uso: Storytelling

![](/img/visualizacion/stortytelleing.png)


### Caso de uso: algoritmo 

![](/img/visualizacion/algoritmo.png)

### Data Art

La visualización de datos también incluye un aspecto de belleza que a veces es la única razón para su creación y se llama "DataArt"

![](/img/visualizacion/art.png)


## Tipos de visualización de datos 

### Objetivos

- Conocer lso diferentes tipos de visualización 
- Aprender la importancia de elegir el tipo adecuado. 
- Entender cómo el uso de la interactividad puede influir el tipo de la visualización 

### Diferentes tipos de la visualización de datos

![](/img/visualizacion/un_conjunto_25_vis.png)


#### Un conjunto de datos, 25 visualizaciones

https://flowingdata.com/2017/01/24/one-dataset-visualized-25-ways/


#### Catálogos

[Data viz project](https://www.datavizproject.com)


[Data viz project. Muestra qué tipo de visualización se puede crear en función de la información](https://www.data-to-viz.com)

![](/img/visualizacion/catalogo)



### Spaguetti plot

![](/img/visualizacion/catalogo)

Con todas las líneas, coloes y puntos es muy difícil ver el comportamiento y los patrones de los datos. 


#### Highlighting

en el fondo siguen las líneas, pero con el highlighting reforzamos las líneas que que queremos que el usuario vea. 

![](/img/visualizacion/highlighting.png)

#### Filtering


![](/img/visualizacion/filtering.png)

#### Small Multiple

La idea es mostrar a lo largo del itempo varias visualizaciones a la vez. 

![](/img/visualizacion/small_multiple.png)

#### Filtering & Linked Highlighting

![](/img/visualizacion/filtering_linked_highlighting.png)

#### Small multiple, Filtering & Highlighting

![](/img/visualizacion/small_multiple_filtering_highlighting.png)

## Visual Encodings

### Objetivos

- Entender qué son los visual encodings y cómo se usan. 
- Presentar los diferentes tipos de visual encodings y su fiuncionamiento a través de diferentes ejemplos: colores y posición. 
- Demostrar el uso adecuado de los visual encodings. 

### ¿Qué es un visual encoding? 

#### Seeing = Understanding

![](/img/visualizacion/visual_encoding.png)



#### ¿Qué es un visual encoding? 

Un visual encoding es traducir cualquier información cuantitativa o categórica a un elemento visual, y por otro lado cuando la persona mira a la visualización, pueda descodificar esta información intuitivamente. 

![](/img/visualizacion/visual_encoding_2.png)


De acuerdo a los tipos: 

![](/img/visualizacion/visual_encoding_3.png)

Los más importantes son: 

- Color
- Posición 
- Saturación 
- Tamaño 



#### Los más adecuados 

![](/img/visualizacion/los_mas_adecuados.png)

### Color 



#### Color wheel

![](/img/visualizacion/color.png)



#### Herramientas online

![](/img/visualizacion/color_brewer.png)

![](/img/visualizacion/color_adobe.png)

![](/img/visualizacion/viz_palette.png)

#### Ejemplos

![](/img/visualizacion/ejemplo.png)

![](/img/visualizacion/ejemplo_2.png)

![](/img/visualizacion/ejemplo_3|.png)

## Percepción humana

- Transmitir las reglas básicas de la percepción humana. 
- Introducir diferentes conceptos y cómo pueden afectar a la comprensión de las visualizaciones. 
    - El concepto Weber's Law. 
    - El concepto Gestalt Principles
    - El concepto Cuarteto de Anscombee. 
    - Introducir diferentes conceptos y cómo pueden afectar a la comprensión de las visualizaciones. 
- Introducir la perspectiva del usuario y los conceptos relativos como por ejemplo evitar el chart junk, presentar la verdad y mostrar datos marginales. 


### Conceptos de la percepción 

> ¿ Por qué nos debería interesar la visualización? Porque el sistema visual humano es un buscador de patrones de enorme poder y sutileza. El ojo y la corteza visual del cerebro forman un procesador masivamente paralelo que proporciona el canal de mayor ancho de banda a los centros cognitivos humanos. En los niveles más altos de procesamiento, la percepción y la cognición están estrechamente relacionadas, por lo que las palabras "comprender" y "ver" son sinónimos. - *Information Visualization, Second Edition, Colin Ware, Morgan Kaufmann Publishers, 2004, page 21. 

#### Weber's Law

![](/img/visualizacion/weber's%20law.png)

![](/img/visualizacion/webers_law.png)


#### Gestalt's - formato vs. colores

Gesalt dice que los colores tienen un poder mucho más fuerte para distinguir diferentes clases que las formas. 

![](/img/visualizacion/gestalt.png)

![](/img/visualizacion/gestalt_2.png)

#### Cuarteto de Anscombee

![](/img/visualizacion/cuarteto_anscombee.png)

![](/img/visualizacion/cuarteto_anscombee.png)

## ¿Quién va a ser el usuario de la visualización? 

Cuando estemos haciendo visualizaciones 

- Para qué sirve este elemento. 
- Cuánto sirve
- Cuánto pesa (espacio visual, atención. )

### Evitar el chartjunk

![](/img/visualizacion/chart_junk.png)

### Presentar la verdad 

![](/img/visualizacion/presentar_verdad.png)

### Cómo presentar outliers 

Vemos un gráfico de áreas con diferentes categorías: cómo se mencionan diferentes temas a lo largo del tiempo. Haciendo un rescaling podemos ver los detalles y en valor absoluto con respecto al valor absoluto. 

![](/img/visualizacion/como_ver_outliers.png)


# Unidad 2






# Unidad 3. Visualización dinámica con D3.js/Observable - I

El objetivo de esta unidad es familiarizarse con el mundo de la programación y específicamente la librería de D3.js. Se muestra sobre todo el funcionamiento de las tecnologías fundamentales, en el entorno de D3.js. Después se explica cómo manejar los datos y los funciones principales de D3.js (selecciones, escalas y ejes).


## INTRO TO D3.JS

![Página web con los apuntes](https://observablehq.com/@sandraviz/html-css-intro?collection=@sandraviz/ue-visualizacion-dinamica-con-d3-js)

D3.js es una librería escrita en Javascript, pero afecta a la página, para hacer visualizaciones dinámicas. 

https://d3js.org/

![](/img/visualizacion/d3.png)


Como llevan algunos años, muchas visualizaciones encontradas en muchas páginas web, se basan en esta librería. Vamos a ver 3 ejemplos prácticos: 


[Visual Introduction to machine learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
[The unwelcomed](https://www.alhadaqa.com/wp-content/uploads/2019/11/the_unwelcomed_v2.html)
[Olympic Feathers](https://olympicfeathers.visualcinnamon.com/)


Estas visualizaciones son muy personalizadas, justo cuadran con el objetivo que pretenden lograr. 


### ¿Por qué D3? 

No solo porque D3.js sigue siendo la biblioteca más importante para las visualizaciones dinámicas basadas en la web, sino también porque muchas otras herramientas de visualización de datos se construyen sobre o junto con d3.js. Además, aprender d3 también significa aprender lo que realmente significa visualizar datos.

Flourish se basa en D3. 



### Qué es D3? 

> "Efficient manipulation of documents based on data."- Mike Bostock 

No solo es una librería de Javascript, sino que ahora es un ecosistema de visualizaciónnes Es un lenguaje de etiquetas definido por SVG que modifica páginas web (HTML y CSS).


![](/img/visualizacion/d3_2.png)

### Intro to HTML, SVG y CSS

HTML stands for HyperText Markup Language, which creates a structure to hold the content of your webpage; it does this using what it calls elements.

#### texto simple 

``` html 

<body>

<p>When <strong> a tree falls </strong> in the forest</p>
<p> there are <strong> other trees listening. </strong> </p>
  
</body> 

```

#### Listas 

``` html
<body>



<p>My cat <strong>Felicita</strong> is</p>
  
<ul> 
  <li>relaxed</li>
  <li>sweet</li>
  <li>always in the moment</li>
</ul>
  
</body> 

```

#### SVG

SVG stands for Scalable Vector Graphics and are an XML-based markup language for describing two-dimensional based vector graphics. When doing data visualisation, we use mainly the SVG TAGs listed below to draw the visual elements into our webpage. 

![](/img/visualizacion/svg.png)

``` html 

<svg width="950" height="170">
   <circle cx="150" cy="100" r=60 fill="#4DF772"></circle>  
   <circle cx="220" cy="100" r=60 fill="#3DC45A"></circle>
   <circle cx="100" cy="100" r=60 fill="#98F9AD"></circle>
   <circle cx="280" cy="100" r=60 fill="#257837"></circle>
</svg>

<style>
  
circle {
   opacity:0.4; 
}
  
</style>

```

## D3.js & Observable

![INTRO TO DATA IN JS](https://observablehq.com/@sandraviz/intro-to-data-in-js?collection=@sandraviz/ue-visualizacion-dinamica-con-d3-js)


29/05/23

1 notebook para la primera visualización
1 notebook para el gráfico de dispersión. 

 

 # StoryTelling

 El Data Storytelling es narrar los datos por medio de visualizaciones y una historia que las une a ellas para comunicar la importancia de los datos en sí y de su análisis/procesamiento .

El elemento más importante es la visualización en sí misma. 


 ¿Cuál es la diferencia con una presentación ordinaria? 

 - Tiene un inicio y un final
 - Contiene personajes.
 - Tiene una conexión temporal. 
 - Tiene un hilo de coherencia. 
 - Tiene momentos de tensión, acción que provocan emociones en el espectador. 
 - Se resuelve el momento de tensión 



Es una buena idea conectar los datos con un tema con la que la audiencia pueda sentirse conectada. 
Se puede introducir la humanización de los datos con data storytelling para sensibilizar algunos datos. 

Puedes utilizar recursos que las personas utilizan/saben con cotidianeidad. 

Podemos comenzar muy abstracto para generar una conexión emocional hablando de un caso particular o un ejemplo, y luego magnificar todo hablando sobre todos los datos. 

Recomendaciones

1. Poner en contexto. 
2. Utilizar un ejemplo particular que cause atención. Utilizar outliers para crear tensión. 
3. Crear tensión
4. Conclusiones


Análisis de un storytelling: elegimos un ejemplo
- estructura
- author-driven, viewer-driven. 

## Lenguaje visual 

En el storytelling utilizamos el color para lo más importante, normalmente en un storytelling lo más importante es los personajes: ciudades, marcas de teléfono, países, etc. 

Cuando casamos los colores con sus personajes, ya no es necesario colocar la leyenda todo el tiempo porque el observador va a asociar ambos conceptos indistintamente. 

No obstante, a veces usamos los colores para marcar cambios o eventos con íconos y patrones para historias. 

## Creación de un Data Storytelling

1. Poner en contexto el tema: hacer una introducción.
2. Poner en contexto la visualización. 
3. Empezar con un incidente que es muy fácil de entender para poner en perspectiva al autor. Queremos conectarnos con la audiencia y debemos utilizar una instancia digerible para que puedan entrar a la historia sin mucho esfuerzo.
4. Utilizamos datos marginales o un aumento de la complejidad para incrementar la tensión. 
5. Se relaja la historia por medio de una recapitulación o una solución a la tensión. 
6. Se permite al usuario interactuar con los datos y recrear su propia historia. 


## Conceptos: Scroll-y-telling, Martini Glass Structure, Drill-Down

![](/img/visualizacion/author_driven.png)

![](/img/visualizacion/viewer_driven.png)

- **Scroll-y-telling:** 
- **Martini Glass Structure**: El inicio es author-driven y luego se abre a una posibilidad de encontrar su propia historia. 
- **Drill-Down**:




# Clase 10/07

Podemos llevar un storytelling propio.  

## Tips
- No repitamos el texto. 


1. PErspectiva del autor: author-driven, viewer-driven
2. Dar ejemplos, está introduciendo. No nos da el ejemplo de los cortes al principio para crear interés y suspenso. 
3.  Tras ver el gráfico de duración, podemos ver que las categorías que tienen más frecuencia son las relacionadas con sexo, LGBT y faltas de respeto hacia China. 
4. Es poco interactivo, claramente definido por el autor, quiere convencerte de su punto de vista. 

# Cómo se crea el desarrollo de la historia

1. La portada del la historia: aplica una censura sobre el título para dar una introducción visual a lo que vamos a hablar. Se utilizan imágenes que ejemplifican 
2. Él aplica un ejemplo particular personal para apelar a la cercanía y facilitar la conexión. "Se usa la forma de un ejemplo personal para identificarse con el lector para introducirte el efecto censura, para que el espectador sienta que un programa tan familiar como Big Bang fue censurado". 
2. Te exponen ejemplos particulares para que compares y las evalúes moralmente, y te sientas involucrado. Luego el autor pasa de esos ejemplos particulares a una perspectiva panorámica, con lo cual se aleja en detalle pero continúa o magnifica la tensión hacia el espectador para que entienda de que existe una gran cantidad de momentos como los que juzgó anteriormente en toda la muestra tomada. 
3. La gráfica de barcode empieza vacía y no tiene ejes, esto provoca expectativa porque el espectador sabe que no va a quedarse así. 
4. Se relaja la tensión y continúa con el hilo de la historia. Se produce interés intuitivo por medio de imágens y frases cortas. 
5. Vuelve a introducir ejemplos, que para el espectador puede generar un poco de hastío o aburrimiento, pero estos ejemplos son los más absurdos de censura para que al espectador le llame la atención que la censura es bastante subjetiva. 
6. Vuelve a generarse tensión y provocación porque el autor expone otra idea que es exponiendo películas locales comparando escenas  que fueron censuradas con otras similares del programa. Las imágenes son muy explícitas y visuales y mantienen la atención del lector. 
7. Termina con una reflexión personal, sin visualizaciones. Hace un resumen, a manera más de generar una reflexión en los espectadores. La anulación de visualizaciones produce un desenlace y relajación ene l espectador. 
8. La línea de coherencia de la historia es un poco desordenada, trae muchos ejemplos en diferentes partes, trae 


¿Cuáles son los lenguajes visuales que se utilizan? 

https://pudding.cool/2022/08/censorship/


- Es un gráfico de barcode 
- Los colores representan las categorías y es fácil recordar las etiquetas que representan porque son solo 3 colores. Los colores contrastan muy bien con el fondo. Los colores son poco representativos para los temas que hablan, pero existe una tendencia actualmente de utilizar colores neutrales para descontextualizar los temas con otras historias y que los temas a traer a mención se centren únicamente en la información brindada dentro de la narrativa.  
- La duración es fácil de identificar, da una sensación de cuál largo o cuán corto es una categoría con respecto a otra y cuánto ocupa en el episodio completamente. 
- Utiliza mucho el verde, puede ser porque apela al tema más censurado que es el sexo pero en una parte que habla específicamente de "falta de respeto" que tenía asignado el color amarillo, el espectador esperaría esos colores y sin embargo, utilizó el amarillo. 
- 