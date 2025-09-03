---
layout: home
title: "My ITSM Journey"
---

{% for post in site.posts %}
  <div class="post-container">
    <ol>
      <li>
        <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt }}</p>
      </li>
    </ol>
  </div>
{% endfor %}
