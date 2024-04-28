---
title: GenAI Talk
layout: home
---


<p>
GenAI Talk is a talk series by Sudhanshu Mishra and Shubhanshu Mishra to explore different techniques in the world of Generative AI and Machine Learning. 
</p>

<ul>
{% for member in site.data.genai_talk %}
  <li>
    <a href="{{ member.url }}">
      {{ member.name }}
    </a> - [<a href="{{ member.slides }}">Slides</a>]
  </li>
{% endfor %}
</ul>