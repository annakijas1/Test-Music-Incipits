---
layout: page
title: Backer-Grøndahl, Agathe (1847-1907)
category: incipits
permalink: /backer-grondahl/
---

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Backer-Grøndahl, Agathe" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>