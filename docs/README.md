### Hi there 👋
I'm currently learning NodeJS + React + a lot of new things !

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl | append: post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
