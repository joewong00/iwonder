---
layout: page
title: Browse
permalink: /browse/
---
<ul>
    {%- for post in site.posts -%}
    <li>
        <h4>
        <a class="browse-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
        </a>
        </h4>
    </li>
    {%- endfor -%}
</ul>
