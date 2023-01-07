---
# layout: page_light
title: 法语启蒙（总结）
page_category: "法语启蒙"
---

{% comment %} 
   This filters out the posts within the given category associated with the page.
{% endcomment %}
{% if site.paginate %}
   {% assign posts = paginator.posts | where:"categories", page.page_category %}
{% else %}
   <!--   {% assign posts = site.posts | where_exp:"post", "post.categories contains page_category" %} -->
   {% assign posts = site.posts | where:"categories", page.page_category %}
{% endif %}

{% include print_posts.html content=posts %}
