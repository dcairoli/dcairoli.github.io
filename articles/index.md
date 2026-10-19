---
layout: default
title: Articles
---

# Articoli
<div>
    {% for p in site.posts %}
        {% include article_item.html url=p.url title=p.title
            description=p.description %}
    {% endfor %}
</div>