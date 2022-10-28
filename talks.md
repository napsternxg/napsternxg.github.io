---
title: Talks
layout: home
---


<ul>
{% for member in site.data.talks %}
  <li>
    <a href="{{ member.url }}">
      {{ member.name }}
    </a> at {{ member.venue }} - [<a href="{{ member.slides }}">Slides</a>]
  </li>
{% endfor %}
</ul>