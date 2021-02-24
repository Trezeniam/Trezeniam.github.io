---
layout: post
title:  "Lets Look Inside"
date:   2021-02-22 22:34:26 +0000
categories: jekyll update
lounge1: /assets/images/lounge1.jpg
---


{% for post in site.posts %}
<p><h1>{{ post.title }}</h1></p>
<img src="{{ post.lounge1 | prepend: site.baseurl }}" alt="{{ post.title }}" title="{{ post.title }}">
{% endfor %}