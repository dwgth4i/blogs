---
layout: home
title: dwgth4i's blog
---

<div class="container">
    <h1>Welcome to My Blog</h1>
    <p>Latest posts:</p>
    <ul>
        {% for post in site.posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
        {% endfor %}
    </ul>
</div>
