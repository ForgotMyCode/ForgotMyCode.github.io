# Hello world

{% for post in site.posts %}

- [
{% for category in post.categories %}
\[category\]
{% endfor %}
 {{ post.title }}]({{ site.baseurl }}{{ post.url }})

{% endfor %}
