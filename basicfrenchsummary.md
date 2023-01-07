---
# layout: page_light
title: 法语启蒙（总结）
page_category: "法语启蒙"
if_print_post_list: false
---

## Cahier audio:

－ [05]({{ site.baseurl }}/assets/audio/05 Pista 5.mp3)
－ [06]({{ site.baseurl }}/assets/audio/06 Pista 6.mp3)
－ [11]({{ site.baseurl }}/assets/audio/11 Pista 11.mp3)
－ [12]({{ site.baseurl }}/assets/audio/12 Pista 12.mp3)
－ [23]({{ site.baseurl }}/assets/audio/23 Pista 23.mp3)
－ [26]({{ site.baseurl }}/assets/audio/26 Pista 26.mp3)
－ [34]({{ site.baseurl }}/assets/audio/34 Pista 34.mp3)


## 最新：

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
