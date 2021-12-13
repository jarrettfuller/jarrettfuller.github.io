---
tag: "Design"
permalink: /design/
layout: default
---

<div class="about-intro"><p>I've worked as a graphic designer for over a decade, both collaboratively and independently. I still take on projects when times allows so if you'd like to work together, <a href="mailto:jarrettfuller@gmail.com">get in touch</a>.</p></div>


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
