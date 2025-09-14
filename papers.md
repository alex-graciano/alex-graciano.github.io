---
layout: page
title: Papers
subtitle: A selection of my research papers
permalink: /papers/
---
<ul class="list-posts">
    {% for paper in site.papers %}
        <li class="post-teaser">
            <a href="{{ paper.url | prepend: site.baseurl }}">
                <span class="post-teaser__title">{{ paper.title }}</span>
                <span class="post-teaser__date">{{ paper.date | date: "%B %Y" }}</span>
            </a>
        </li>
    {% endfor %}
</ul>
