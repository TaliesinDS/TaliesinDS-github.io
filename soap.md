---
permalink: /soap/
title: "Handgemaakte Zeep"
layout: single
author_profile: true
---
![zeep verpakkingen](/assets/images/zeep1.jpg "mooie zeepjes")
informatie over de zeep die ik maak.

{% for tag in site.tags %}

{% if tag[0] == "zeep" %}

<ul>

{% for post in tag[1] %}

<li><a href="{{ post.url }}">{{ post.title }}</a></li>

{% endfor %}

</ul>

{% endif %}

{% endfor %}

