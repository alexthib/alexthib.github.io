---
layout: default
title: Enjoy Agile - scrum, kanban, bonheur au travail, environnements avec membres d'équipes engagés
---

<ul>
  {% for post in site.posts %}
    {% assign content = post.content %}
    <br/>
    <br/>
  	{% include post_detail.html %}
  {% endfor %}
</ul>
<!--
<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
-->