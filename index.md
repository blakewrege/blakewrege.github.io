---
layout: page
title: Blake Wrege
tagline: Computer Programmer
---
{% include JB/setup %}

<style>


p.main {
    text-align: justify;
    width: auto;
}


</style>


<img src="/assets/images/blake.jpg" alt="Blake">   
	

<p class="main">Hello I'm Blake Wrege! I'm a full time Student at WMU and a part time computer technician for the College of Arts and Sciences. This website will forever be a work in progress as I am always striving to find ways to improve.</p>

List of posts 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



