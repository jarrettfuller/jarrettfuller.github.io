---
layout: playlist-index
title: Playlists
permalink: /playlists/
---

{% for playlists in site.playlists reversed %}
    <div class="playlist-cover">
      <a href="{{ playlists.url }}">
          <img src="{{ playlists.image}}">
          {{ playlists.title }}</a>
    </div>
  {% endfor %}

