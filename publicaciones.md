---
layout: page

title: Publicaciones

permalink: /publicaciones/

excerpt: Publicaciones en revistas arbitradas, mis trabajos de tesis y las veces que mi trabajo ha sido incluido en catálogos de arte.

seo_title: Publicactions - Dr. Jorge Antonio García Galicia.

seo_description: Publicaciones en revistas arbitradas, mis trabajos de tesis y las veces que mi trabajo ha sido incluido en catálogos de arte.

lang: es

locale: es_MX

page_id: publications

last_modified_at: 2024-01-13
---

1. TOC
{:toc}

## Articulos de Investigación

### Soportes inteligentes: generación de estructuras de soporte eficientes para la manufactura digital

![Clever support]({{ site.baseurl }}/static/images/articles/clever_supports.jpg "Clever support image")

Introducimos un marco de optimización para la reducción de las estructuras de soporte requeridas por las impresoras 3D basadas en la tecnología de modelado por deposición fundida (FDM).
Las impresoras necesitan conectar las salientes con las partes inferiores del objeto o con el suelo para poder imprimirlas.
Dado que el material de soporte debe imprimirse primero y desecharse después, optimizar su volumen puede generar ahorros de material y tiempo de impresión.
Presentamos un enfoque novedoso basado en la geometría que minimiza el material de soporte y al mismo tiempo mantiene suficiente soporte.
Utilizando nuestro método, el modelo 3D de entrada se orienta primero en la posición con un área mínima que requiere soporte.
Luego se detectan los puntos de esta zona que requieren soporte.
Para estos puntos, se construye la estructura de soporte progresivamente mientras se intenta minimizar su longitud total.
La estructura resultante tiene una forma de árbol que soporta eficazmente las salientes.
Hemos probado nuestro algoritmo en la impresora MakerBot® Replicator™ 2 y comparamos nuestra solución con la solución de software integrada en esta impresora y con el software Autodesk® Meshmixer™.
Nuestra solución redujo el tiempo de impresión en un promedio de 29,4% (entre 13,9% y 49,5%) y la cantidad de material en un 40,5% (entre 24,5% y 68,1%).


* [Link permanente](https://doi.org/10.1111/cgf.12437){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar el [artículo]({{ site.baseurl }}/static/pdf/articulos/CleverSupport.pdf){:target="_blank" rel="noreferrer noopener"}


```
@article{Vanek2014a,
    author   = {Vanek, J. and Galicia, J. A. G. and Benes, B.},
    title    = {Clever Support: Efficient Support Structure Generation for Digital Fabrication},
    journal  = {Computer Graphics Forum},
    volume   = {33},
    number   = {5},
    pages    = {117-125},
    keywords = {I.3.5 Computer Graphics: Computational Geometry and Object Modeling—,
                    I.3.8 Computer Graphics: Applications},
    doi      = {https://doi.org/10.1111/cgf.12437},
    url      = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.12437},
    eprint   = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/cgf.12437},
    year     = {2014}
}
```


### Espirales de Fermat conexas para la manufactura por capas

![Fermat Spirals]({{ site.baseurl }}/static/images/articles/fermat_spirals.jpg "Fermat Spirals image")

Desarrollamos un nuevo tipo de curvas que “llenan el espacio de manera compacta”, las Espirales de Fermat Conectadas y mostramos que poseen varias propiedades atractivas como  patrón de trayectoria de herramientas para la fabricación en capas.
A diferencia de las curvas clásicas que llenan el espacio, como las curvas de Peano o Hilbert, que se enrollan y unen constantemente para preservar la localidad, las Espirales de Fermat Conectadas están formadas principalmente por trayectorias largas y de baja curvatura.
Esta propiedad geométrica, junto con la continuidad, influye en la calidad y eficiencia para la fabricación en capas.
Dada una región 2D conexa, primero la descomponemos en un conjunto de subregiones, cada una de las cuales puede llenarse con una única espiral de Fermat continua.
Mostramos que siempre es posible comenzar y finalizar un relleno en espiral de Fermat aproximadamente en el mismo lugar en el límite exterior de la región rellena.
Esta propiedad especial permite que las Espirales de Fermat Conectadas se unan sistemáticamente mediante el recorrido de un grafo que representa la descomposición en subregiones.
El resultado es una curva globalmente continua.
Demostramos que imprimir capas 2D usando trayectorias de herramientas con Espirales de Fermat Conectadas conduce a una manufactura eficiente y de calidad, en comparación con los patrones de relleno convencionales.

* [Link permanente](https://doi.org/10.1145/2897824.2925958){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar el [artículo]({{ site.baseurl }}/static/pdf/articulos/FermatSpirals.pdf){:target="_blank" rel="noreferrer noopener"}


* [Haisen Zhao](https://haisenzhao.github.io/){:target="_blank" rel="noreferrer noopener"} quien es el autor principal, tiene una [página](https://haisenzhao.github.io/CFS/index.html){:target="_blank" rel="noreferrer noopener"} muy completa acerca de este artículo.

* Este artículo fue [presentado](https://www.youtube.com/watch?v=6rNcAVr-U4s){:target="_blank" rel="noreferrer noopener"} en el canal de youtube: [Two minute papers](https://www.youtube.com/@TwoMinutePapers){:target="_blank" rel="noreferrer noopener"}.

```
@article{Zhao2016,
    author     = {Zhao, Haisen and Gu, Fanglin and Huang, Qi-Xing and Garcia, Jorge
                     and Chen, Yong and Tu, Changhe and Benes, Bedrich and Zhang, Hao
                     and Cohen-Or, Daniel and Chen, Baoquan},
    title      = {Connected Fermat Spirals for Layered Fabrication},
    journal    = {ACM Trans. Graph.},
    issue_date = {July 2016},
    volume     = {35},
    number     = {4},
    month      = {jul},
    year       = {2016},
    issn       = {0730-0301},
    pages      = {100:1--100:10},
    articleno  = {100},
    numpages   = {10},
    url        = {http://doi.acm.org/10.1145/2897824.2925958},
    doi        = {10.1145/2897824.2925958},
    acmid      = {2925958},
    publisher  = {ACM},
    address    = {New York, NY, USA},
    link       = {https://youtu.be/Kh-41evJVjs}
}

```

### Packmerger: un optimizador del volumen para la impresión 3D

![ Packmerger ]({{ site.baseurl }}/static/images/articles/pack_merger.jpg "Packmerger image")

Proponemos un marco de optimización para impresión en 3D que busca ahorrar en el tiempo de impresión y el material de soporte necesario para imprimir piezas en 3D.
La tecnología de impresión tridimensional está madurando rápidamente y puede revolucionar la forma en que fabricamos objetos.
El coste total de la impresión, sin embargo, se rige por numerosos factores que incluyen no sólo el precio de la impresora sino también la cantidad de material y tiempo para fabricar la pieza.
Nuestro algoritmo: PackMerger convierte la malla sellada 3D de entrada en una cáscara ahuecando sus partes internas.
Luego, la cáscara se divide en segmentos.
La ubicación de las divisiones se controla en función de varios parámetros, incluido el tamaño de las áreas de conexión o el volumen de cada segmento.
Luego, las piezas se empaquetan de manera compacta mediante optimización.
La optimización intenta minimizar la cantidad de material de soporte y el volumen del envolvente de los segmentos empaquetados manteniendo al mismo tiempo el número de segmentos al mínimo.
La configuración final se puede imprimir con un ahorro sustancial de tiempo y material, al mismo tiempo permite la impresión de objetos que no cabrían en la impresora.
Hemos probado nuestro sistema en tres impresoras diferentes y muestra una reducción del 5 al 30 % del tiempo de impresión y, al mismo tiempo, ahorra entre el 15 y el 65 % del material de soporte.
El tiempo de optimización fue de aproximadamente 1 min.
Una vez impresos los segmentos, es necesario ensamblarlos.

* [Link permanente](https://doi.org/10.1111/cgf.12353){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar el [artículo]({{ site.baseurl }}/static/pdf/articulos/PackMerger.pdf){:target="_blank" rel="noreferrer noopener"}

* Este artículo también tiene un [video](https://www.youtube.com/watch?v=sBgSr7JItmo){:target="_blank" rel="noreferrer noopener"}.

```
@article{Vanek2014b,
    author   = {Vanek, J. and Galicia, J. A. Garcia and Benes, B. and Měch, R.
                    and Carr, N. and Stava, O. and Miller, G. S.},
    title    = {PackMerger: A 3D Print Volume Optimizer},
    journal  = {Computer Graphics Forum},
    volume   = {33},
    number   = {6},
    pages    = {322-332},
    keywords = {Digital Geometry Processing, Geometric Modeling, Computational Geometry Modeling,
                   Categories and Subject Descriptors I.3.5 Computer Graphics: Computational
                   Geometry and Object Modelling, I.3.8 Computer Graphics: Applications},
    doi      = {https://doi.org/10.1111/cgf.12353},
    url      = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.12353},
    eprint   = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/cgf.12353},
    year     = {2014}
}

```

### Mejora de la orientación para impresoras de Modelado por Deposición Fundida mediante el análisis de componentes conectados


![ Printing orientation ]({{ site.baseurl }}/static/images/articles/printing_orientation.jpg "Printing orientation image")

La orientación espacial de un objeto en la bandeja de impresión 3D contribuye significativamente a su tiempo de manufactura.
Por lo tanto, la velocidad del proceso de impresión 3D generalmente se puede aumentar aplicando orientaciones eficientes en el tiempo a los objetos.
Este artículo presenta un método novedoso para acelerar el procesos de impresión encontrando orientaciones de máxima eficiencia.
Este método encuentra una orientación para el objeto que minimiza el número de componentes desconectados y la distancia entre los componentes desconectados, minimizando así el tiempo necesario para que el cabezal de la impresora atraviese áreas vacías.
El método también considera la altura del objeto impreso, su volumen atrapado y la cantidad de componentes conectados en cada capa.
Nuestro novedoso algoritmo, considera los cuatro criterios, cada uno ponderado según parámetros específicos de la impresora y obtenidos experimentalmente.
Las pruebas preliminares demuestran que esta metodología puede reducir los tiempos de impresión en impresoras de deposición fundida hasta un 45% comparado con el de los algoritmos actuales.

* [Link permanente](https://doi.org/10.1016/j.addma.2018.06.007){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar el [artículo]({{ site.baseurl }}/static/pdf/articulos/printingOrientation.pdf){:target="_blank" rel="noreferrer noopener"}


```
@article{Garcia2018,
    title    = {Improving printing orientation for Fused Deposition Modeling printers by
                    analyzing connected components},
    journal  = {Additive Manufacturing},
    volume   = {22},
    pages    = {720-728},
    year     = {2018},
    issn     = {2214-8604},
    doi      = {https://doi.org/10.1016/j.addma.2018.06.007},
    url      = {https://www.sciencedirect.com/science/article/pii/S2214860417302555},
    author   = {Jorge A. {García Galicia} and Bedrich Benes},
    keywords = {Additive manufacturing, Optimization, Printing path planning},
}

```

### Aprendiendo gramáticas de grafos geométricos

![ Geometric Graph Grammars ]({{ site.baseurl }}/static/images/articles/graph_grammars.jpg "Geometric Graph Grammars image")

Introducimos gramáticas de grafos geométricas, demostramos cómo estas gramáticas pueden generar estructuras geométricas e introducimos un algoritmo para su aprendizaje automático (modelado procedural inverso).
Nuestro enfoque amplía el concepto de gramáticas de grafos para permitir codificar no solo datos topológicos, sino también geometría. El modelado directo genera grafos geométricos y considera varias estrategias para la conectividad de nodos.
El modelado procedural inverso realiza el aprendizaje de grafos geométricos, mediante el descubrimiento de estructuras repetidas y su conectividad.
Estas estructuras están codificadas en reglas de reescritura de la gramática de grafo geométrica.
Demostramos la usabilidad de nuestro enfoque en un ejemplo que utiliza redes urbanas.
El aprendizaje de los grafo es razonablemente rápido.
En nuestra implementación, el aprendizaje de una red de carreteras con 72k vértices y 100k aristas se realiza en menos de un minuto.

* [Link permanente](https://doi.org/10.1145/2948628.2948635){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar el [artículo]({{ site.baseurl }}/static/pdf/articulos/GraphGrammars.pdf){:target="_blank" rel="noreferrer noopener"}


```
@inproceedings{Fiser2016,
    author    = {Fi\v{s}er, Marek and Benes, Bedrich and Galicia, Jorge Garcia and
                     Abdul-Massih, Michel and Aliaga, Daniel G and Krs, Vojtech},
    title     = {Learning Geometric Graph Grammars},
    booktitle = {Proceedings of the 32Nd Spring Conference on Computer Graphics},
    series    = {SCCG '16},
    year      = {2016},
    isbn      = {978-1-4503-4436-4},
    location  = {Slomenice, Slovakia},
    pages     = {7--15},
    numpages  = {9},
    url       = {http://doi.acm.org/10.1145/2948628.2948635},
    doi       = {10.1145/2948628.2948635},
    acmid     = {2948635},
    publisher = {ACM},
    address   = {New York, NY, USA},
}

```

### Yturralde: generador de figuras imposibles

![ Yturralde: impossible figure ]({{ site.baseurl }}/static/images/articles/impossible_figures.jpg " image")

Esta investigación destaca la participación y las contribuciones más significativas de José María Yturralde al arte informático temprano de 1968 a 1973.
Yturralde colaboró con artistas y científicos para ampliar y redefinir su comprensión de las formas, y exploró formas en que la computadora mainframe podría usarse como herramienta para complementar sus prácticas artísticas.
Es conocido por desarrollar un modelo matemático con el que pudo crear un programa altamente sofisticado donde las geometrías de Penrose podían recombinarse algorítmicamente.
Sin embargo, existe evidencia y acceso limitado al código del software real.
El objetivo de los autores es comprender mejor la contribución de Yturralde desarrollando una resignificación de su modelo, lo que han logrado a través de una interpretación moderna de los manuscritos.

* [Link permanente](https://doi.org/10.1145/2810177.2810183){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar el [artículo]({{ site.baseurl }}/static/pdf/articulos/ImpossibleFigures.pdf){:target="_blank" rel="noreferrer noopener"}


```
@inproceedings{Bravo2015,
    author    = {Bravo, Esteban Garc\'{\i}a and Garc\'{\i}a, Jorge A.},
    title     = {Yturralde: Impossible Figure Generator},
    year      = {2015},
    isbn      = {9781450333238},
    publisher = {Association for Computing Machinery},
    address   = {New York, NY, USA},
    url       = {https://doi.org/10.1145/2810177.2810183},
    doi       = {10.1145/2810177.2810183},
    booktitle = {ACM SIGGRAPH Art Papers},
    pages     = {366–374},
    numpages  = {9},
    location  = {Los Angeles, California},
    series    = {SIGGRAPH '15}
}

```

## Catálogos de arte

### Galería del programa de artes IEEE VIS 2016 y 2017

![ Geode ]({{ site.baseurl }}/static/images/geode.jpg "Geode image")

Geode es una escultura video-mapeada desarrollada a partir de un análisis de la geometría improvisada en un espacio tridimensional.
El proyecto interroga el potencial estético de la geometría emotiva mediante la utilización de formas no ortogonales y modelos matemáticos basados en puntos y planos infinitos.
Geode lleva el arte neoconcreto a una nueva dimensión al integrar la geometría digital en respuesta a la síntesis de audio.
De esta forma conseguimos una forma cristalina que brilla como una geoda mineral.
Las variaciones de superficie son el resultado de la síntesis de sonido en tiempo real.
Visualizamos paisajes sonoros transformando señales analógicas en datos digitales en tiempo real.
La metamorfosis de la escultura se experimenta visualmente a través de geometrías generativas impulsadas por el sonido.
Geode es un esfuerzo colaborativo para fusionar escultura pública, paisaje sonoro y proyección visual en una experiencia inmersiva.

* [Link permanente](https://doi.org/10.1145/2810177.2810183){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar el [catálogo]({{ site.baseurl }}/static/pdf/ArtGalleryCatalog.pdf){:target="_blank" rel="noreferrer noopener"} completo.


```
@article{VIS-2016-2017Arts,
    author  = {Groß, Benedikt and Reimann, Raphael and Schmitt, Philipp and Bravo, Esteban Garcia and Carlson, Maxwell and Zernack, Aaron and Garcia, Jorge and Han, Yoon Chung and Tiwari, Shankar and Nagel, Till and Pietsch, Christopher and Stock, Mark J. and Shi, Weili and Westbrook, Jessica Parris and Trowbridge, Adam and Richison, Mike and Goodwin, Mitch and Fay, Clement and Lay, Sebastian and Vermeulen, Jo and Perin, Charles and Donovan, Eric and Dachselt, Raimund and Carpendale, Sheelagh and Heinicker, Paul and Offenhuber, Dietmar and Clark, Duncan and Houston, Robin and Smith, Tristan and Jenik, Adriene and Ribeiro, Clarissa and Lorusso, Mick and Rocha, Herbert and So, Wonyoung and Martino, Mauro and Strobelt, Hendrik and Cornec, Owen and Huang, Scottie Chih-Chieh and Huang, Yu-Chun and Lee, Inhye and Kim, Hyomin and Amelot, Pierre and Hwong, John and McManus, Kate and McGee, Ryan and Neubauer, Mary Bates},
    title   = "{IEEE VIS 2016 and 2017 Arts Program Gallery}",
    journal = {Leonardo},
    volume  = {53},
    number  = {1},
    pages   = {6-24},
    year    = {2020},
    month   = {02},
    issn    = {0024-094X},
    doi     = {10.1162/leon_a_01837},
    url     = {https://doi.org/10.1162/leon\_a\_01837},
    eprint  = {https://direct.mit.edu/leon/article-pdf/53/1/6/1579585/leon\_a\_01837.pdf},
}
```

### XV: espacios reactivos


![ XV: reactive spaces ]({{ site.baseurl }}/static/images/xv_points.jpg "XV: reactive spaces image")

Quince puntos (XV) es una proyección interactiva en el piso en la que se anima a los espectadores a moverse por el espacio y participar en la manipulación de la obra de arte.
Los espacios generados a través de estos quince puntos detectan el cuerpo del participante, doblando y distorsionando la arquitectura de la pieza.
Cuando ya no se detecta una presencia, las formas se restauran  a su estado original de forma autónoma con un estallido de energía, mientras un paisaje sonoro generativo orquesta toda la experiencia.

* [Link permanente](https://www.scienceopen.com/hosted-document?doi=10.14236/ewic/eva2015.46){:target="_blank" rel="noreferrer noopener"} en el sitio de publicación.

* Descargar la [entrada]({{ site.baseurl }}/static/pdf/XVReactiveSpaces.pdf){:target="_blank" rel="noreferrer noopener"} del catálogo.


```
@inproceedings{inproceedings,
    author    = {Garcia Bravo, Esteban and Garcia Galicia, Jorge and Zernack, Aaron},
    year      = {2015},
    month     = {07},
    publisher = {Association for Computing Machinery},
    booktitle = {Electronic Visualisation and the Arts 2015},
    title     = {XV: Reactive Spaces},
    doi       = {10.14236/ewic/eva2015.46}
}

```


## Tesis

### Optimización de la velocidad de impresión 3D minimizando los caminos vacíos

![ PhD thesis ]({{ site.baseurl }}/static/images/phd_thesis.jpg "PhD thesis image")

Aunque el campo de la impresión 3D ha experimentado una innovación sustancial desde sus inicios, la velocidad de impresión sigue siendo lenta.
La orientación espacial de una pieza sobre la bandeja de impresión contribuye significativamente a su tiempo de manufactura.
Presentamos una solución novedosa basada en la observación de que el cabezal de impresión debe iniciar y detener la deposición cuando viaja entre regiones separadas de cada capa a imprimir.
Nuestro método encuentra una orientación para el objeto que minimiza la distancia entre los componentes desconectados, minimizando así el tiempo necesario para que el cabezal de la impresora atraviese áreas vacías.
El método también considera la altura del objeto impreso, su volumen atrapado y la cantidad de componentes conectados en cada capa.
Proporcionamos una estrategia de optimización que considera los cuatro criterios, cada uno ponderado según parámetros específicos de la impresora y obtenidos experimentalmente.
Las velocidades de impresión en nuestra prueba mejoran hasta en un 45% al agregar el criterio de distancia de los componentes desconectados a la optimización.

* [Link permanente](https://docs.lib.purdue.edu/dissertations/AAI10615432/){:target="_blank" rel="noreferrer noopener"} en la biblioteca de Purdue.

* [Texto completo]({{ site.baseurl }}/static/pdf/tesis/thesisPHD.pdf){:target="_blank" rel="noreferrer noopener"}


```
@phdthesis{Garcia2017,
    title   = {3D Printing Speed Optimization by Minimizing Void Paths},
    author  = {Jorge A. {García Galicia}},
    year    = {2017},
    month   = {Augost},
    address = {West Lafayette, IN},
    note    = {Available at \url{https://docs.lib.purdue.edu/dissertations/AAI10615432/}},
    school  = {Purdue Univeristy},
    type    = {PhD thesis}
}
```

### Visualización suavizada de superficies obtenidas por rastreo de fronteras aplicado a volúmenes discretizados

![ Master thesis ]({{ site.baseurl }}/static/images/master_thesis.jpg "Master thesis image")

Este trabajo trata de cómo visualizar campos escalares que han pasado por un proceso de digitalización.
En particular se usa una técnica de graficación por computadora conocida como visualización por superficies o surface rendering.

Se asume que se tienen conjuntos digitales de datos que provienen de haber muestreado de manera uniforme el espacio en tres dimensiones.
Asumimos que este muestreo está hecho en una rejilla rectangular y por lo tanto tenemos una imagen digital en 3D o volumen.
Hacemos dos suposiciones importantes sobre el volumen.
Primero, que es una buena aproximación del campo escalar y segundo que no tenemos información de la manera como se realizó la digitalización.

Primeramente revisamos dos algoritmos de rastreo de superficies sobre volúmenes.
El algoritmo de Marching Cubes que es el más usado en la actualidad y el Algoritmo de Artzy cuya salida posee características deseables desde el punto de vista topológico.
Ambos algoritmos producen una malla poligonal que aproxima una superficie del campo escalar original.

El problema en adelante es visualizar correctamente estas mallas.
Se incluye una revisión de algunas técnicas de graficación por computadora para visualizar mallas.
En particular nos enfocamos a la iluminación con el modelo de Phong y a las técnicas basadas en mapas; tales como el mapeo de texturas y el mapeo de relieves (bump mapping).
Se explica también la creación de superficies implícitas o modelo blobby usado comúnmente en graficación para hacer modelado orgánico.
Se revisan algunas funciones base que se usan con este modelo.
Se presentan las funciones Kaiser-Bessel generalizadas también llamadas blobs.

El objetivo de este trabajo consiste en encontrar una forma de mejorar la visualización de la malla del Algoritmo de Artzy y hacerla equiparable con el algoritmo de Marching Cubes sin modificar la malla y usando solamente efectos de iluminación.
La principal aportación del trabajo es un algoritmo para encontrar una superficie implícita formada por blobs que envuelve la malla del Algoritmo de Artzy.
Por medio de esta superficie calculamos vectores normales que luego ponemos en los vértices de la malla y la usamos para iluminación.

Por último, se reportan resultados de algunos experimentos con esta técnica.
Primeramente se realizan experimentos en conjuntos de datos obtenidos por medio de técnicas de imagenología biomédica, estos resultados constituyen una prueba visual de que la técnica propuesta funciona.
Por último se hacen experimentos sobre campos escalares conocidos (phantoms) y se comparan las normales obtenidas por nuestro método con las normales analíticas de los phantoms.
En la última sección del trabajo se reportan las conclusiones y se proponen algunas líneas de investigación para trabajo futuro.

* [Link permanente](https://repositorio.unam.mx/contenidos/292221){:target="_blank" rel="noreferrer noopener"} en el sitio de bibliotecas de la UNAM.

* [Texto completo]({{ site.baseurl }}/static/pdf/tesis/tesisMaestria.pdf){:target="_blank" rel="noreferrer noopener"}.


```
@phdthesis{Garcia2012,
    title   = {Visualización suavizada de superfícies obtenidas por rastreo
                 de fronteras aplicado a volúmenes discretizados},
    author  = {Jorge A. {García Galicia}},
    year    = {2012},
    month   = {February},
    address = {Coyoacan, DF, México},
    note    = {Available at \url{https://repositorio.unam.mx/contenidos/292221}},
    school  = {Universidad Nacional Autónoma de México},
    type    = {Master thesis}
}
```

### Modelado Gráfico de un Cuerpo Neumático con OpenGL a Base de Ecuaciones Diferenciales

![ Bachelor thesis ]({{ site.baseurl }}/static/images/bachelor_thesis.jpg "Bachelor thesis image")

Este trabajo trata de cómo crear una simulación gráfica de un cuerpo flexible.
El cuerpo flexible, está construido –como es costumbre en graficación por computadora– por una malla tridimensional.
Además, en éste trabajo se asume que las aristas de la malla son resortes y que el cuerpo flexible está relleno de aire.

Para hacer una animación basada en Física, se definen un conjunto de fuerzas que actúan sobre los vértices de la malla.
Después, se usa la fuerza acumulada para integrar la ecuación de Newton y obtener las velocidades y posiciones de los vértices en la escena.
Las fuerzas aplicadas son: la gravedad, los resortes-amortiguadores y la fuerza de presión.
Esta última, es resultado de usar la ecuación del gas ideal.

Se describe a detalle, la creación de un programa que implementa todas estas ideas para hacer una animación interactiva.
La implementación se hizo en lenguaje C++ y se usa OpenGL como biblioteca para desplegar gráficos.

Se hacen un conjunto de pruebas para comprobar el correcto comportamiento cualitativo en la implementación.
Y por último, se hace un análisis del desempeño del programa; donde se estima que secciones son las computacionalmente más costosas.

* La tesis original fué presentada en 2008. Sin embargo, en 2019 decidí hacer una nueva edición usando solo Software Libre,  OpenGL moderno y reescribindo un parte del texto. Lo cual resulto en un [repositorio completo](https://github.com/nemediano/TesisLicenciatura){:target="_blank" rel="noreferrer noopener"} para este trabajo.

* [Link permanente](https://repositorio.unam.mx/contenidos/343984){:target="_blank" rel="noreferrer noopener"} en el sitio de bibliotecas de la UNAM.

* [Texto completo]({{ site.baseurl }}/static/pdf/tesis/tesisLicenciatura.pdf){:target="_blank" rel="noreferrer noopener"} de la nueva versión.



```
@phdthesis{Garcia2008,
    title   = {Modelado Gráfico de un Cuerpo Neumático con OpenGL
                  a Base de Ecuaciones Diferenciales},
    author  = {Jorge A. {García Galicia}},
    year    = {2008},
    month   = {Augost},
    address = {Acatlán, Edo de Mex, México},
    note    = {Available at \url{https://repositorio.unam.mx/contenidos/343984}},
    school  = {Facultad de Estudios Superiores Acatlán, UNAM},
    type    = {Bachelor thesis}
}
```
