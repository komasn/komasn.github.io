<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}_{ post.date }}</a>
    </li>
  {% endfor %}
</ul>
