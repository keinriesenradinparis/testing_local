---
# layout: page_light
title: 法语启蒙
page_category: "法语启蒙"
if_print_post_list: false
---

## 启蒙20

<!-- [课程大纲]({{ site.baseurl }}/2023/01/18/法语启蒙20-大纲.html) -->

{% assign posts = site.tags["NdC20"] %}
{% include print_posts_simple.html content=posts %}

## 零基础

### Cahier 音频:

- [05]({{ site.baseurl }}/assets/audio/05 Pista 5.mp3)
- [06]({{ site.baseurl }}/assets/audio/06 Pista 6.mp3)
- [11]({{ site.baseurl }}/assets/audio/11 Pista 11.mp3)
- [12]({{ site.baseurl }}/assets/audio/12 Pista 12.mp3)
- [23]({{ site.baseurl }}/assets/audio/23 Pista 23.mp3)
- [26]({{ site.baseurl }}/assets/audio/26 Pista 26.mp3)
- [34]({{ site.baseurl }}/assets/audio/34 Pista 34.mp3)

### 知识点总结

{% assign posts = site.posts | where:"tags", "NdC0" %}
{% include print_posts_simple.html content=posts %}
