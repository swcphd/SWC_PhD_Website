---
layout: archive
title: Events
url: https://swcphd.github.io/SWC_PhD_Website/events

share: false
---

The SWC PhD society will organise several social and scientific events throughout the year. 
If you have an awesome idea for an event you would like for us to organise, get in touch! 


## Future events:

<div class="tiles-square">
{% for post in site.posts %}
  {% if post.categories contains 'events' %}
	{% include post-grid-square.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles --> &nbsp;



<div class="tiles-square">
{% for post in site.posts %}
  {% if post.categories contains 'events-archived' %}
	{% include post-grid-square.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles --> 


