---
layout: default
---
{% for post in site.categories.blog %}
        <h3>
        	<a href="{{ post.url }}">{{ post.title }}</a>
        </h3>
        <p>{{ post.description }}</p>
{% endfor %}