---
layout: archive
title: "期末视频"
permalink: /final/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<video id="video" controls="" preload="none" poster="http://Erreurist.github.io/files/2.jpg" style="width:96%;height:54%;">
      <source id="mp4" src="http://Erreurist.github.io/files/2.mp4" type="video/mp4">
</video> 
