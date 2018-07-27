---
layout: media
permalink: 
title:
share: false
url: https://swcphd.github.io/SWC_PhD_Website/


---

#### Consectetur adipiscing elit. Ut sodales lacus nec orci feugiat varius. Donec venenatis metus velit, eu tempus quam finibus vitae.   

Sed vel lorem in lectus lobortis feugiat et eu tortor. Etiam semper justo nec ex volutpat, eget porta est aliquet. Sed molestie metus vitae orci tempus, a gravida nulla accumsan. Donec vitae metus ligula. Nam fringilla venenatis aliquet. Curabitur tristique neque at facilisis sagittis. Duis et posuere ante. Maecenas egestas sit amet enim ut feugiat.


[Test link](https://google.com)  


![wideimg](images/swc.jpg)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sodales lacus nec orci feugiat varius. Donec venenatis metus velit, eu tempus quam finibus vitae. Sed vel lorem in lectus lobortis feugiat et eu tortor. Etiam semper justo nec ex volutpat, eget porta est aliquet. Sed molestie metus vitae orci tempus, a gravida nulla accumsan. Donec vitae metus ligula. Nam fringilla venenatis aliquet. Curabitur tristique neque at facilisis sagittis. Duis et posuere ante. Maecenas egestas sit amet enim ut feugiat.


<div style="height:100px;"> </div>

# Events coming up!
<div class="tiles">
  {% for post in site.posts %}
    {% if post.categories contains 'events' %}
    {% include post-grid.html %}
    {% endif %}
  {% endfor %}
</div><!-- /.tiles -->


