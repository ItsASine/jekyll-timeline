---
layout: null
---
<ul class="timeline">
{% for post in site.posts %}
<li>
  <span class="dot"></span>
  <div class="event">
    <p class="job">
      {{ post.title }}{% if post.location %} @ {{ post.location }}{% endif %}
    </p>
    <p class="duration">{{ post.start }} - {{ post.end }}</p>
    <p class="content">{{ post.content }}</p>
  </div>
</li>
{% endfor %}
</ul>
