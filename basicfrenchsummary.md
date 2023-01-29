---
# layout: page_light
title: 法语启蒙
page_category: "法语启蒙"
if_print_post_list: false
---

1. Table of contents
{:toc}

## 启蒙20

This is[^1] HTML


[^1]: asdfg
{:id: #id-of-this}

Link to [?](#id-of-this).

*[comment]: this is comment and will not be showed.

*[HTML]: this is for the author, a comment that explains the abbreviation "HTML".



<!-- [课程大纲]({{ site.baseurl }}/2023/01/18/法语启蒙20-大纲.html) -->

{% assign posts = site.tags["启蒙20"] %}
{% include print_posts_simple.html content=posts %}

## 零基础

### 讲义

- [01]({{ site.baseurl }}/assets/doc/NdCS6/01 - compl.pdf)
- [02]({{ site.baseurl }}/assets/doc/NdCS6/02 - compl.pdf)
- [03]({{ site.baseurl }}/assets/doc/NdCS6/03 - compl.pdf)
- [05]({{ site.baseurl }}/assets/doc/NdCS6/05 - compl.pdf)
- [06]({{ site.baseurl }}/assets/doc/NdCS6/06 - compl.pdf)
- [07]({{ site.baseurl }}/assets/doc/NdCS6/07.pdf)
- [09]({{ site.baseurl }}/assets/doc/NdCS6/09.pdf)
- [10]({{ site.baseurl }}/assets/doc/NdCS6/10.pdf)
- [11]({{ site.baseurl }}/assets/doc/NdCS6/11.pdf)
- [12]({{ site.baseurl }}/assets/doc/NdCS6/12 - compl.pdf)
- [13]({{ site.baseurl }}/assets/doc/NdCS6/13.pdf)

### Cahier 音频

- [05]({{ site.baseurl }}/assets/audio/05 Pista 5.mp3)
- [06]({{ site.baseurl }}/assets/audio/06 Pista 6.mp3)
- [11]({{ site.baseurl }}/assets/audio/11 Pista 11.mp3)
- [12]({{ site.baseurl }}/assets/audio/12 Pista 12.mp3)
- [23]({{ site.baseurl }}/assets/audio/23 Pista 23.mp3)
- [26]({{ site.baseurl }}/assets/audio/26 Pista 26.mp3)
- [34]({{ site.baseurl }}/assets/audio/34 Pista 34.mp3)

### 知识点总结

{% assign posts = site.posts | where:"tags", "零基础" %}
{% include print_posts_simple.html content=posts %}


## 其他资料

B站[【【上海外国语大学】新公共法语初级 李沁 吴贤良（全167讲）】](https://www.bilibili.com/video/BV1PB4y1D7vM/)，全长九个多小时

公共法语（老版）上册音频：[第1-20课]({{ site.baseurl }}/assets/audio/gonggongfayushang1.zip)，[第21-36课]({{ site.baseurl }}/assets/audio/gonggongfayushang2.zip)
