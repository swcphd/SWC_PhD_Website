---
layout: article
title: A cool event!
date: 2018-07-25 18:47 +0100
category: events_template

image:
image:
  teaser: events_teaser.jpg
  feature: events_feature.jpg
  
share: true

excerpt: Here is where you put a brief description of the event KSGBJSKNGJEARNBGIAERNGKJ;RE

---

# Event title

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sodales lacus nec orci feugiat varius. Donec venenatis metus velit, eu tempus quam finibus vitae. Sed vel lorem in lectus lobortis feugiat et eu tortor. Etiam semper justo nec ex volutpat, eget porta est aliquet. Sed molestie metus vitae orci tempus, a gravida nulla accumsan. Donec vitae metus ligula. Nam fringilla venenatis aliquet. Curabitur tristique neque at facilisis sagittis. Duis et posuere ante. Maecenas egestas sit amet enim ut feugiat.

## Info [date/venue]
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sodales lacus nec orci feugiat varius. Donec venenatis metus velit, eu tempus quam finibus vitae. Sed vel lorem in lectus lobortis feugiat et eu tortor. Etiam semper justo nec ex volutpat, eget porta est aliquet. Sed molestie metus vitae orci tempus, a gravida nulla accumsan. Donec vitae metus ligula. Nam fringilla venenatis aliquet. Curabitur tristique neque at facilisis sagittis. Duis et posuere ante. Maecenas egestas sit amet enim ut feugiat.


## List of partecipants
<div class="tiles-square" style="height: 700px;">
  {% for post in site.posts %}
    {% if post.categories contains 'guests' %}
    {% include post-grid-square.html %}
    {% endif %}
  {% endfor %}
</div><!-- /.tiles -->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sodales lacus nec orci feugiat varius. Donec venenatis metus velit, eu tempus quam finibus vitae. Sed vel lorem in lectus lobortis feugiat et eu tortor. Etiam semper justo nec ex volutpat, eget porta est aliquet. Sed molestie metus vitae orci tempus, a gravida nulla accumsan. Donec vitae metus ligula. Nam fringilla venenatis aliquet. Curabitur tristique neque at facilisis sagittis. Duis et posuere ante. Maecenas egestas sit amet enim ut feugiat.




