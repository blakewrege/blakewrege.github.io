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

<div style="position: relative; left: 0; top: 0;">
  <img src="/assets/images/blake.jpg" style="position: relative; top: 0; left: 0;"/>
  <img src="/assets/images/duckling.gif" style="position: absolute; top: 30px; left: 70px;"/>
</div>



List of posts 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



