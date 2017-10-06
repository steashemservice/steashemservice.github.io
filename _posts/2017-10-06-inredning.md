---
layout: post
title: 3 RUM & KÖK | 70  KVM | BROMMA / BECKOMBERGA
description: Inredning för Visning
image: assets/images/objekt_1/pic7.jpg
permalink: objekt_1.html
---
# array: [1,2,3,4,5,6,8,9,10,11,12,13]
{% for item in array %}
<span class="image main">
    ![test image]({{ site.url | absolute_path}}/assets/images/objekt_1/pic{{ item }}.jpg)
 </span>   
{% endfor %}
<span class="image main">
![test image]({{ site.url | absolute_path}}/assets/images/objekt_1/pic1.jpg)
</span>
