---
layout: media
title: The society
url: https://swcphd.github.io/SWC_PhD_Website/society
share: false
---

The SWC PhD society aims to represent the PhD students of the Sainsbury Wellcome Centre PhD program and
of the Gatsby Computational Neuroscience Unit PhD program. 

Our goals include gathering resources useful for current and future students, oganising social
events to facilitate collaboration across students of different disciplines as well as organising
scientific events and symposia. 

To achieve these goals, we have put together a team of highly motivated and talented PhD students. 
For any issue, idea or question that may concern the society, get in touch with Federico (our head of 
communication). 



<div class="tiles-square" style="height: 700px;">
{% for post in site.posts %}
    {% if post.categories contains 'members' %}
	    {% include post-grid-square.html %}
    {% endif %}
{% endfor %}
</div><!-- /.tiles -->

