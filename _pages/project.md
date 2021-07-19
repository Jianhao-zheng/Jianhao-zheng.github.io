---
layout: archive
title: "Projects"
permalink: /project/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Autonomous Navigation and Landing for Crazyflie
<p float='left'>
	<img src="https://jianhao-zheng.github.io/images/crazy_flie.png" width="600"/> 
</p>

We programed based on Crazyflie 2.1 to find and precisely land on a platform with height of 10 cm by utilizing z reading from flow deck. Additionally, We also utilized sensor readings from multi-ranger deck to avoid the obstacles presented in the environment.
[[Video](https://youtu.be/RP4-SlhOIUk)] [[Code](https://github.com/Jianhao-zheng/Crazyflie-Auto-navigation-and-landing)] [[Slides](https://drive.google.com/file/d/1vY_UMflVXOcUSOASHkGHsSTXCBmwrVhK/preview)]