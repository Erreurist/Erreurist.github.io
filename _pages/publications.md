---
layout: archive
title: "作业视频"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<video id="video" controls="" preload="none" style="width:480px;height:270px;">
      <source id="mp4" src="http://Erreurist.github.io/files/1.mp4" type="video/mp4">
</video> 
