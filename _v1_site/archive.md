---
layout: archive
title: Archive
permalink: /archive/
---
<div class="stacks">
  <div class="posts">
    {% for post in site.posts%}


      <article class="post">
          <h1><a href="{{ site.baseurl }}{{post.url}}">{{ post.title}}</a></h1>
          <div class="date">{{ post.date | date: "%m.%d.%Y" }}
          </div>
      </article>

    {% endfor %}
  </div>
</div>
