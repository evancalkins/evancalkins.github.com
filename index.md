---
layout: default
title: evancalkins.net
---
{% include JB/setup %}

{% for post in site.posts %}
  <article>
    <a class="permalink" href="{{ BASE_PATH }}{{ post.url }}">∞</a>
    <header>
  	  <h3>{{ post.title }}</h3>
  	</header>
  	{{ post.content }}
  	<!--<h5>{{ post.date | date_to_string }}</h5>-->
  </article>
{% endfor %}



