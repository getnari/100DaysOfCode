
## Mission Statement

Complete mission statement here.

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/100DaysOfCode/{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
