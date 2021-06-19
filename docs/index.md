---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<nav role="navigation" aria-label="Main" id="site-nav">
    <h1 class="text-delta">Table of contents</h1>
    <ul>
    {% assign children_list = site.html_pages | where_exp:"item", "item.title != nil" | where_exp:"item", "item.parent != nil" %}
    {% for child in children_list %}
        {% if child.has_children == false %}
        {% else %}    
            <li>
                <a href="{{ child.url }}">{{ child.title }} - {{ child.parent }}</a>
            </li>
        {% endif %}
    {% endfor %}
    </ul>
</nav>
