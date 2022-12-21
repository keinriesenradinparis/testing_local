---
layout: page
title: About me
example: Example Text
---

![](images/rachel-pfuetzner-0fn7fxv1ewa-unsplash.jpg)

## Who am I

I am a financial analyst trying to establish my own blog where I would like to share personal notes across various themes.

I learnt how to build Github from [this website](https://evanwill.github.io/go-go-ghpages-b/).

The variable "title" is {{ site.title }}.

Now the variable "example" is embedded as {{ page.example }}.

To uses the `_include` folder, one can write {% include big-cat.html %}.

To use the `data` folder, one can write
  {% for x in site.data.animals %}
  - The {{ x.name }} is a {{ x.size }} animal.
  {% endfor %}


