---
layout: layout
date:   2023-05-19 17:42:55 -0700
---

[Rules](/rules/)

# Resources

[linktr.ee](https://linktr.ee/queer_consent_corner)

# Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
