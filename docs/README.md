### Hi there 👋
I'm currently learning NodeJS + React + a lot of new things !

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{% post_url {{ post.title }} %}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>