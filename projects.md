---
layout: default
---

<main class="preview">
  {% for post in site.posts %}

        <a href="{{ site.baseurl }}{{ post.url }}">
        <div class="object">
            <div class="project">{{ post.title }}</div>
            <div class="type">{{ post.type }}</div>
            <div class="year">{{ post.year }}</div>
        </div>
            <img src="{{ post.image }}"></a>

    {% endfor %}

<section class="clear"></section>
