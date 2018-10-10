---
layout: null
title: Career
---
## Career

<ul class="timeline">
{% for post in site.posts %}
<li>
    <h2>{{ post.title }}</h2>
    <h3>{{ post.location }}</h3>
    <small>{{ post.start }} - {{ post.end }}</small>
    <p>{{ post.content }}</p>
</li>
{% endfor %}
</ul>
