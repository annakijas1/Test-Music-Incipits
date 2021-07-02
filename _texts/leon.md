---
layout: page
title: León, Tania (1943)
category: incipits
century: 20
permalink: /leon/
---
<a title="Photo by Michael Provost, CC BY-SA 3.0 &lt;https://creativecommons.org/licenses/by-sa/3.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Tania_Leon.jpg"><img width="128" alt="Tania Leon" src="https://upload.wikimedia.org/wikipedia/commons/f/f4/Tania_Leon.jpg"></a>

*Learn more about this composer at <a href="https://en.wikipedia.org/wiki/Tania_León" target="_blank">https://en.wikipedia.org/wiki/Tania_León</a>*
<br/>

### Works with Incipits
<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "León, Tania" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>
