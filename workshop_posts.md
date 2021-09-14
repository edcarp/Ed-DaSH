---
layout: default
title: Workshop posts
theme: Workshop_posts 
permalink: /workshop_posts/
--- 



<h3>Upcoming and past workshops</h3>
<ul class="post-list">
    {% for post in site.posts %}
    {% if post.type == 'workshop_announcement' %}
    <li> 
         <a class="post-link" href="{{ post.website }}" target="_blank">{{ post.when }}, {{ post.title }}</a>
    </li>
    {% endif %}
    {% endfor %}
</ul>

<!--a class="post-link" href="{{ post.website }}" target="_blank">{{ post.when }}, {{ post.title }}</a-->
