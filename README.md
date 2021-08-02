# 備忘録
坂出市在住  
備忘録として使って行こうと思います。  
jekyll でブログ公開してみようと思います  
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
