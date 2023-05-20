---
layout: layout
---

[Rules](/rules/)

# Resources

https://linktr.ee/queer_consent_corner

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
