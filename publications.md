---
layout: page

title: Publications

permalink: /publications/

excerpt: Jorge Antonio García Galicia’s personal website. In this section you will find my publications in journals, my dissertations and the times my work has been featured in an art catalog.

seo_title: Publicactions - Dr. Jorge Antonio García Galicia.

seo_description: Jorge Antonio García Galicia’s personal website. In this section you will find my publications in journals, my dissertations and the times my work has been featured in an art catalog.

last_modified_at: 2024-01-07
---

### Clever support: Efficient support structure generation for digital fabrication

![Clever support]({{ site.baseurl }}/static/images/articles/clever_supports.jpg "Clever support image")

We introduce an optimization framework for the reduction of support structures required by 3D printers based on Fused Deposition Modeling (FDM) technology.
The printers need to connect overhangs with the lower parts of the object or the ground in order to print them.
Since the support material needs to be printed first and discarded later, optimizing its volume can lead to material and printing time savings.
We present a novel, geometry-based approach that minimizes the support material while providing sufficient support. Using our approach, the input 3D model is first oriented into a position with minimal area that requires support.
Then the points in this area that require support are detected.
For these points the supporting structure is progressively built while attempting to minimize the overall length of the support structure. The resulting structure has a tree-like shape that effectively supports the overhangs.
We have tested our algorithm on the MakerBot® Replicator™ 2 printer and we compared our solution to the embedded software solution in this printer and to Autodesk® Meshmixer™ software.
Our solution reduced printing time by an average of 29.4% (ranging from 13.9% to 49.5%) and the amount of material by 40.5% (ranging from 24.5% to 68.1%).

* [Permanent link](https://doi.org/10.1111/cgf.12437){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/CleverSupport.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation
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


### Connected fermat spirals for layered fabrication

![Fermat Spirals]({{ site.baseurl }}/static/images/articles/fermat_spirals.jpg "Fermat Spirals image")

We develop a new kind of "space-filling" curves, connected Fermat spirals, and show their compelling properties as a tool path fill pattern for layered fabrication.
Unlike classical space-filling curves such as the Peano or Hilbert curves, which constantly wind and bind to preserve locality, connected Fermat spirals are formed mostly by long, low-curvature paths.
This geometric property, along with continuity, influences the quality and efficiency of layered fabrication.
Given a connected 2D region, we first decompose it into a set of sub-regions, each of which can be filled with a single continuous Fermat spiral.
We show that it is always possible to start and end a Fermat spiral fill at approximately the same location on the outer boundary of the filled region.
This special property allows the Fermat spiral fills to be joined systematically along a graph traversal of the decomposed sub-regions.
The result is a globally continuous curve. We demonstrate that printing 2D layers following tool paths as connected Fermat spirals leads to efficient and quality fabrication, compared to conventional fill patterns.

* [Permanent link](https://doi.org/10.1145/2897824.2925958){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/FermatSpirals.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation

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

### Packmerger: A 3d print volume optimizer

![ Packmerger ]({{ site.baseurl }}/static/images/articles/pack_merger.jpg "Packmerger image")

We propose an optimization framework for 3D printing that seeks to save printing time and the support material required to print 3D shapes.
Three-dimensional printing technology is rapidly maturing and may revolutionize how we manufacture objects.
The total cost of printing, however, is governed by numerous factors which include not only the price of the printer but also the amount of material and time to fabricate the shape.
Our PackMerger framework converts the input 3D watertight mesh into a shell by hollowing its inner parts.
The shell is then divided into segments.
The location of splits is controlled based on several parameters, including the size of the connection areas or volume of each segment.
The pieces are then tightly packed using optimization.
The optimization attempts to minimize the amount of support material and the bounding box volume of the packed segments while keeping the number of segments minimal.
The final packed configuration can be printed with substantial time and material savings, while also allowing printing of objects that would not fit into the printer volume.
We have tested our system on three different printers and it shows a reduction of 5–30% of the printing time while simultaneously saving 15–65% of the support material.
The optimization time was approximately 1 min.
Once the segments are printed, they need to be assembled.

* [Permanent link](https://doi.org/10.1111/cgf.12353){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/PackMerger.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation

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
                   Categories and Subject Descriptors I.3.5 Computer Graphics: Computational Geometry and
                   Object Modelling, I.3.8 Computer Graphics: Applications},
    doi      = {https://doi.org/10.1111/cgf.12353},
    url      = {https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.12353},
    eprint   = {https://onlinelibrary.wiley.com/doi/pdf/10.1111/cgf.12353},
    year     = {2014}
}

```

### Improving printing orientation for Fused Deposition Modeling printers by analyzing connected components

![ Printing orientation ]({{ site.baseurl }}/static/images/articles/printing_orientation.jpg "Printing orientation image")

The spatial orientation of an object on a 3D printing plate is a significant contributor to its printing time.
Thus, the speed of the 3D printing processes can generally be increased by using time-efficient object orientations.
This paper presents a novel method for speeding-up printing processes that employs maximally efficient orientations.
This method finds an orientation for the object that minimizes the number of disconnected components and the distance between the disconnected components that remain, thereby minimizing the time needed for the printer head to traverse empty areas. The method also considers the height of the printed object, its trapped volume, and the number of connected components in each layer.
Our novel algorithm considers all four criteria, each weighted according to printer-specific and experimentally-obtained parameters. Preliminary trials demonstrate that this methodology can decrease printing times on fused deposition printers to 45% of that of current state of the art algorithms.

* [Permanent link](https://doi.org/10.1016/j.addma.2018.06.007){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/printingOrientation.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation

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

### Learning geometric graph grammars

![ Geometric Graph Grammars ]({{ site.baseurl }}/static/images/articles/graph_grammars.jpg "Geometric Graph Grammars image")

We introduce geometric graph grammars, demonstrate how they can generate geometric structures, and introduce an algorithm for their automatic learning (inverse procedural modeling).
Our approach extends the concept of graph grammars to allow for coding not only topological data, but also geometry.
Forward modeling generates geometric graphs and considers various strategies for node connectivity.
Inverse procedural modeling performs learning of geometric graphs, by discovering repeated structures and their connectivity.
These structures are encoded into geometric graph grammar rewriting rules.
We demonstrate usability of our approach on an example using urban networks.
Graph learning is reasonably fast; in our implementation, learning of a road network with 72k vertices and 100k edges is performed in less than one minute.

* [Permanent link](https://doi.org/10.1145/2948628.2948635){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/GraphGrammars.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation

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

### Yturralde: impossible figure generator

![ Yturralde: impossible figure ]({{ site.baseurl }}/static/images/articles/impossible_figures.jpg " image")

This research highlights José María Yturralde's most significant involvement and contributions to early computer art from 1968 to 1973.
Yturralde collaborated with artists and scientists to expand and redefine his understanding of shapes, and explored ways that the mainframe computer could be used as a tool for complementing his art practices.
He is known for developing a mathematical model with which he was able to create a highly sophisticated program where Penrose geometries could be recombined algorithmically.
However, there is limited evidence and access to the code of the actual software.
The authors' goal is to further understand Yturralde's contribution by developing a re-significance of his model, which they have accomplished through a modern interpretation of manuscripts.

* [Permanent link](https://doi.org/10.1145/2810177.2810183){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/ImpossibleFigures.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation

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
## Dissertations

### 3D Printing Speed Optimization by Minimizing Void Paths

![ PhD thesis ]({{ site.baseurl }}/static/images/phd_thesis.jpg "PhD thesis image")

Though the field of 3D printing has seen substantial innovation since its inception, printing speeds remain slow.
The spatial orientation of a working piece on the building plate plate is a significant contributor to its printing time.
We present a novel solution based on the observation that the printing head must start and stop deposition when traveling between separate regions of a printed layer.
Our method finds an orientation for the object that minimizes the distance between the disconnected components, thereby minimizing the time needed for the printer head to traverse empty areas.
The method also considers the height of the printed object, its trapped volume, and the number of connected components in each layer.
We provide an optimization strategy that considers all four criteria, each weighted according to printer-specific and experimentally-obtained parameters.
Printing speeds in our trial are improved by up to 45% by adding the criterion of disconnected component distance to the optimization.

* [Permanent link](https://docs.lib.purdue.edu/dissertations/AAI10615432/){:target="_blank" rel="noreferrer noopener"}

* [Full text]({{ site.baseurl }}/static/pdf/tesis/thesisPHD.pdf){:target="_blank" rel="noreferrer noopener"}

#### Citation
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

### Visualización suavizada de superfícies obtenidas por rastreo de fronteras aplicado a volúmenes discretizados

![ Master thesis ]({{ site.baseurl }}/static/images/master_thesis.jpg "Master thesis image")

* [Permanent link](https://repositorio.unam.mx/contenidos/292221){:target="_blank" rel="noreferrer noopener"}

* [Full text]({{ site.baseurl }}/static/pdf/tesis/tesisMaestria.pdf){:target="_blank" rel="noreferrer noopener"}

#### Citation
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

* [Permanent link](https://repositorio.unam.mx/contenidos/343984){:target="_blank" rel="noreferrer noopener"}

* [Full text]({{ site.baseurl }}/static/pdf/tesis/tesisLicenciatura.pdf){:target="_blank" rel="noreferrer noopener"}

#### Citation
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
    type    = {Bacheor thesis}
}
```

## Art catalogs

### IEEE VIS 2016 and 2017 Arts Program Gallery

![ Geode ]({{ site.baseurl }}/static/images/geode.jpg "Geode image")

Geode is a video-mapped sculpture developed from an analysis of improvisational geometry in three-dimensional space.
The project interrogates the aesthetic potential of emotive geometry by utilizing nonorthogonal shapes and mathematical models based on points and infinite planes.
Geode takes neo-concrete art to a new dimension by inte grating digital geometry in response to audio synthesis.
In this way, we accomplish a crystal-like shape that glows like a mineral geode. The surface variations are the result of real-time sound synthesis. We visualize soundscapes by transforming analog signals into digital data in real time.
The sculpture’s metamorphosis is experienced visually by sound-driven generative geometries.
Geode is a collaborative effort to fuse public sculpture, soundscape and visual projection into one immersive experience.

* [Permanent link](https://doi.org/10.1145/2810177.2810183){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/ArtGalleryCatalog.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation

```
@article{VIS-2016-2017Arts,
    author   = {Groß, Benedikt and Reimann, Raphael and Schmitt, Philipp and Bravo, Esteban Garcia and Carlson, Maxwell and Zernack, Aaron and Garcia, Jorge and Han, Yoon Chung and Tiwari, Shankar and Nagel, Till and Pietsch, Christopher and Stock, Mark J. and Shi, Weili and Westbrook, Jessica Parris and Trowbridge, Adam and Richison, Mike and Goodwin, Mitch and Fay, Clement and Lay, Sebastian and Vermeulen, Jo and Perin, Charles and Donovan, Eric and Dachselt, Raimund and Carpendale, Sheelagh and Heinicker, Paul and Offenhuber, Dietmar and Clark, Duncan and Houston, Robin and Smith, Tristan and Jenik, Adriene and Ribeiro, Clarissa and Lorusso, Mick and Rocha, Herbert and So, Wonyoung and Martino, Mauro and Strobelt, Hendrik and Cornec, Owen and Huang, Scottie Chih-Chieh and Huang, Yu-Chun and Lee, Inhye and Kim, Hyomin and Amelot, Pierre and Hwong, John and McManus, Kate and McGee, Ryan and Neubauer, Mary Bates},
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

### XV: reactive spaces


![ XV: reactive spaces ]({{ site.baseurl }}/static/images/xv_points.jpg "XV: reactive spaces image")

Fifteen points (XV) is an interactive floor projection in which viewers are encouraged to move throughout the space and engage in the manipulation of the art piece.
The spaces generated through these fifteen points detect the body of the participant, bending and distorting the architecture of the piece.
When a presence is no longer sensed, the shapes are autonomously restored with a burst of energy to their original state, while a generative soundscape orchestrates the entire experience.


* [Permanent link](https://www.scienceopen.com/hosted-document?doi=10.14236/ewic/eva2015.46){:target="_blank" rel="noreferrer noopener"}

* [Article]({{ site.baseurl }}/static/pdf/articulos/XVReactiveSpaces.pdf){:target="_blank" rel="noreferrer noopener"}


#### Citation

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
