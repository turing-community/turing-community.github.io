---
layout: default
---

{% for post in site.posts %}
  <div class="row-fluid">
    <div class="span12">
      <h2>{{ post.title }}</h2>
      <h4>{{ post.date | date: "%m-%d-%Y" }}</h4>
      <p>
        <a href="{{ post.url }}">Read</a>
      </p>
    </div>
  </div>
{% endfor %}
