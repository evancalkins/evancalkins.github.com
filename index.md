---
layout: default
title: evancalkins.net
---
{% include JB/setup %}

{% for post in site.posts %}
  <article>
    <header>
  	  <h3><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h3>
  	  <h5>{{ post.date | date_to_string }}</h5>
  	</header>
  	{{ post.content }}
  </article>
{% endfor %}



