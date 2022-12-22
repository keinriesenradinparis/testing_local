---
layout: defaut_light
title: title of test2
page_category: "法语启蒙"
---

{% comment %} 
   This filters out the posts within the given category associated with the page.
{% endcomment %}
{% if site.paginate %}
  {% assign posts = paginator.posts | where:"categories", categories contains "basicfrench" %}
{% else %}
<!--   {% assign posts = site.posts | where_exp:"post", "post.categories contains page_category" %} -->
<!--   {% assign posts = site.posts | where_exp:"item", "item.categories contains 'languages'" %} -->
   page_category == "法语启蒙"
<!--   {% assign posts = site.posts | where:"categories", "法语启蒙" %} -->
{% endif %}

{% include print_posts.html content=posts %}
