---
layout: post
title: 3 RUM & KÖK | 70  KVM
description: Inredning för Visning
image: assets/images/objekt_1/pic7.jpg
permalink: objekt_1.html
---
{% for item in (1..6) %}
  <span class="image main">
    ![test image]({{ site.url | absolute_path}}/assets/images/objekt_1/pic{{ item }}.jpg)
  </span>   
{% endfor %}
{% for item in (8..13) %}
  <span class="image main">
    ![test image]({{ site.url | absolute_path}}/assets/images/objekt_1/pic{{ item }}.jpg)
  </span>   
{% endfor %}
