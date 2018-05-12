
## 100DaysOfCode Mission Statement

Complete mission statement here.

### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

<!-- ### About

Write my bio here. -->