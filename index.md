---
layout: page
title: "文章索引"
description: "青岛二中2018级理工MT"
header-img: "img/semantic.jpg"
---


<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <h4>{{ y }}</h4>
  {% endif %}
    <time style="font-family: Courier New, monospace" datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }} · </time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a><br> 
{% endfor %}
</ul>