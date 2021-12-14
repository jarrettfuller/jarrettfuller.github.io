---
tag: "Art"
permalink: /painting/
layout: default
---

<div class="about-intro"><p>Painting Archive</p></div>


<div id="playlist-container">
    {% for post in site.tags[page.tag] %}
      <div class="playlist-cover">
            <a href="{{ site.baseurl }}{{ post.url }}">
        <figure>
            <img src="{{ post.image }}">
            <figcaption>
           <h1>{{ post.title }}</h1>
            <h2>{{ post.year }}</h2></figcaption>
        </figure>
          </a>
        </div>
  {% endfor %}
    </div>
