---
layout: default
title: Library
permalink: /library
---


<div class="about-intro">
        <p>As both a designer and writer, my library is important to me. Below are a selection of my all-time favorite books, the ones I find myself returning to the most. Some I love for the content, others for their formal qualities, but I recommend them all.</p>

</div>

<div id="playlist-container">
{% for library in site.library %}
      <div class="playlist-cover">
                <a href="{{ library.amazon }}">
        <figure>
            <img src="{{ library.image}}" alt="image"/>
            <figcaption>
           <h1>{{ library.title }}</h1>
            <h2>{{ library.author }}</h2></figcaption>
        </figure>
          </a>
        </div>
  {% endfor %}
    </div>
