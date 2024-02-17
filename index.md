---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home

excerpt: I'm Jorge Antonio García Galicia, this is my personal website. You can find info about me, like projects, curriculum vitae and publications.

seo_title: Nemediano

seo_description: I'm Jorge Antonio García Galicia, this is my personal website. You can find info about me, like projects, curriculum vitae and publications.


last_modified_at: 2024-02-16

---

![Dr. Jorge García]({{ site.baseurl }}/static/images/nemediano.jpg "Dr. Jorge García")

{% if 'en' == site.active_lang %}

Hello, I am Jorge Antonio García Galicia (a.k.a nemediano).
I currently work at [Google](https://about.google/){:target="_blank" rel="noreferrer noopener"} as a Software Engineer.
I studied my doctorate at [Purdue University](https://www.purdue.edu/){:target="_blank" rel="noreferrer noopener"}, but I consider [UNAM](https://www.unam.mx/){:target="_blank" rel="noreferrer noopener"} my alma mater.

My professional interests are divided into two: as a mathematician I like Geometry (analytic, modern, computational, algebraic), and as a computer scientist I love Computer Graphics.
My [Erdos number]({{ site.baseurl }}/static/pdf/ErdosNumber.pdf){:target="_blank" rel="noreferrer noopener"} is four.

Even though my professional training is technical and scientific, I come from a family of artists which contributed to developing a great appreciation for the arts and humanities.

On a more personal note, I'm a real geek. I enjoy: reading comics (especially non-superhero ones), novels, mathematics, art, video games, television series, sports, music and cartoons.

I was born and raised in Mexico city, but now I live with my wife and our two cats in Silicon valley.

{% else %}

Hola, soy Jorge Antonio García Galicia (a.k.a nemediano).
Actualmente trabajo en [Google](https://about.google/){:target="_blank" rel="noreferrer noopener"} como Ingeniero de Software.
Estudié mi doctorado en [Purdue University](https://www.purdue.edu/){:target="_blank" rel="noreferrer noopener"}, pero considero a la [UNAM](https://www.unam.mx/){:target="_blank" rel="noreferrer noopener"} mi alma mater.

Mis intereses profesionales están divididos en dos: como matemático me gusta la geometría (analítica, moderna, computacional, algebraica), y como computólogo me encantan las Gráficas por Computadora.
Mi [número de Erdos]({{ site.baseurl }}/static/pdf/ErdosNumber.pdf){:target="_blank" rel="noreferrer noopener"} es cuatro.

Aún cuando mi formación profesional es técnica y científica, provengo de una familia de artistas lo cual contribuyó a que desarrollara una gran apreciación por las artes y las humanidades.

De manera más personal, soy un verdadero geek. Disfruto de: leer cómics (especialmente, los que _no son_ de superhéroes), las novelas, las matemáticas, el arte, los videojuegos, las series de televisión, los deportes, la música y las caricaturas.

Nací y crecí en la Ciudad de México, pero ahora vivo con mi esposa y nuestras dos gatitas en Sillicon Valley.

{% endif %}
