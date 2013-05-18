---
layout: default
---
    {% for post in site.categories.blog limit:5 %}
            <h3>
            	<a href="{{ post.url }}">{{ post.title }}</a>
            </h3>
            <p>{{ post.description }}</p>
    {% endfor %}