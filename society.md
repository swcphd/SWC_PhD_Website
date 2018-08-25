---
layout: media
title: The society

share: false
---

### Description of society
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sodales lacus nec orci feugiat varius. Donec venenatis metus velit, eu tempus quam finibus vitae. Sed vel lorem in lectus lobortis feugiat et eu tortor. Etiam semper justo nec ex volutpat, eget porta est aliquet. Sed molestie metus vitae orci tempus, a gravida nulla accumsan. Donec vitae metus ligula. Nam fringilla venenatis aliquet. Curabitur tristique neque at facilisis sagittis. Duis et posuere ante. Maecenas egestas sit amet enim ut feugiat.


#### Goals and stuff
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sodales lacus nec orci feugiat varius. Donec venenatis metus velit, eu tempus quam finibus vitae. Sed vel lorem in lectus lobortis feugiat et eu tortor. Etiam semper justo nec ex volutpat, eget porta est aliquet. Sed molestie metus vitae orci tempus, a gravida nulla accumsan. Donec vitae metus ligula. Nam fringilla venenatis aliquet. Curabitur tristique neque at facilisis sagittis. Duis et posuere ante. Maecenas egestas sit amet enim ut feugiat.



### Get in touch
Ways to communicate with the society: email addresses and stuff

## Our Roles:
* Communication..
* Boss
* Events...
* bla bla bla...  with link to the people

<div class="tiles-square" style="height: 700px;">
{% for post in site.posts %}
    {% if post.categories contains 'members' %}
	    {% include post-grid-square.html %}
    {% endif %}
{% endfor %}
</div><!-- /.tiles -->

