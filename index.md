---
layout: default
title: evancalkins.net
---
{% include JB/setup %}

{% for post in site.posts %}
  <article>
    <header>
  	  <h2>{{ post.title }}<a class="permalink" href="{{ BASE_PATH }}{{ post.url }}">∞</a></h2>
  	</header>
  	{{ post.content }}
  	<!--<h5>{{ post.date | date_to_string }}</h5>-->
  </article>
{% endfor %}



