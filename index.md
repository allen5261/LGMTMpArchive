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
  <table style="border-collapse: collapse; width: 100%; border-style: none;" border="1">
<tbody>
<tr>
<td><time style="font-weight: bolder; font-family: Courier New, monospace" datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }} · </time></td>
<td><a href="{{ post.url | prepend: site.baseurl }}" title="{{ post.title }}" target="_blank">{{ post.title }}</a></td>
</tr>
</tbody>
</table>
    
    <br> 
{% endfor %}
</ul>