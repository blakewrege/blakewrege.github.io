---
layout: page
title: Blake Wrege
tagline: Computer Programmer
---
{% include JB/setup %}

<style>
img {
    display: block;
    max-width:360px;
    max-height:480px;
    width: auto;
    height: auto;
    margin-left: auto;
    margin-right: auto
}

</style>




My attempt to make a Blog
<img src="/assets/images/blake.jpg" alt="Blake">   




List of posts 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



