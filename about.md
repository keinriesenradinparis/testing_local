---
layout: page
title: About me
example: Example Text
---

## Who am I

I am a financial analyst trying to establish my own blog where I would like to share personal notes across various themes.

I learnt how to build Github from [this blog/wordshop](https://evanwill.github.io/go-go-ghpages-b/) and from [this documentation](https://jekyllrb.com/docs/).
Whitespace control could be learnt [here](https://shopify.github.io/liquid/basics/whitespace/).

The variable "title" is {{ site.title }}.

Now the variable "example" is embedded as {{ page.example }}.

To uses the `_include` folder, one can write {% comment %}{% include big-cat.html %}{% endcomment %}.
<img style="display:block; margin: 10px auto;" 
    src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Siberischer_tiger_de_edit02.jpg/640px-Siberischer_tiger_de_edit02.jpg" 
    alt="face of a big tiger" >

To use the `data` folder, one can write
  <!--Need white space control.-->
  {% for animal in site.data.animal_list %} 
  | {{ animal.name }} | {{ animal.size }} |
  {% endfor -%}
line



