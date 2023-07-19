{% include core.md %}

## This only serves as my playground with github pages.

## Posts:

{% for post in site.posts %}

- [{% for category in post.categories %}\[{{ category }}\]{% endfor %} {{ post.title }}]({{ site.baseurl }}{{ post.url }})

{% endfor %}

