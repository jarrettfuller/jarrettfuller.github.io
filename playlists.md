---
layout: default
title: Playlists
permalink: /playlists/
---
<div class="about-intro"><p>Playlists</p></div>

<div id="playlist-container">
{% for playlists in site.playlists reversed %}
<div class="playlist-cover">
      <a href="{{ playlists.url }}">
              <figure>
          <img src="{{ playlists.image}}">
                  <figcaption>
          <h1>{{ playlists.title }}</h1>
        <h2>{{ playlists.season }}</h2>
                      </figcaption>
                    </figure>
          </a>
    </div>
  {% endfor %}
</div>
