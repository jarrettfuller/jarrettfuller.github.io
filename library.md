---
layout: library-index
title: Library
<!--permalink: /library-->
---

{% for library in site.library %}
    <div class="library-cover">
      <a href="{{ library.amazon }}">
          <img src="{{ library.image}}">
          {{ library.title }}</a>
    </div>
  {% endfor %}

