---
layout: post
title: "Bienvenido"
date: 2024-06-02 13:32:44
image: '/assets/img/'
description: 'First steps to use this template'
tags:
- jekyll  
categories:
- I love Jekyll
twitter_text: 'Bienvenido'
---

Esta es la primera entrada de un blog creado utilizando Jekyll y GitHub pages. 

Para conseguirlo he seguido las instrucciones de [Barry Clark](https://github.com/barryclark/jekyll-now) y usado un tema creado por [@willian_justen](https://twitter.com/willian_justen)

## Pros y Contras

Las principales ventajas de este sistema:

- Rapidez, pues carece de base de datos.
- Disponibilidad, pues se encuentra hospedado en GitHub.
- Seguridad.
- Precio.

  
Las principales desventajas de este sistema:

- Curva de aprendizaje.

## ¿Cómo publico?

Para crear una nueva entrada he de crear un archivo de texto, debiendo empezar por la información básica de categorización:

{% highlight ruby %}
---
layout: post
title: "How to use"
date: 2015-08-03 03:32:44
image: '/assets/img/post-image.png'
description: 'First steps to use this template'
tags:
- jekyll 
- template 
categories:
- I love Jekyll
twitter_text: 'How to install and use this template'
---
{% endhighlight %}

Finalmente, el texto se escribe siguiendo las reglas de [Markdown](https://www.markdownguide.org/).

Lo siguiente será intentar utilizar un editor, para ver si facilita esta tarea.
