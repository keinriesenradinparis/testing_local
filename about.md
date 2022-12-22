---
layout: page
title: About me
example: Example Text
---

## Who am I

I am a financial analyst trying to establish my own blog where I would like to share personal notes across various themes.

I learnt how to build Github from [this blog/wordshop](https://evanwill.github.io/go-go-ghpages-b/) and from [this documentation](https://jekyllrb.com/docs/).

The variable "title" is {{ site.title }}.

Now the variable "example" is embedded as {{ page.example }}.

To uses the `_include` folder, one can write {% include big-cat.html %}.

To use the `data` folder, one can write
  {% for animal in site.data.animal_list %}
  - The {{ animal.name }} is a {{ animal.size }} animal.
  {% endfor %}


