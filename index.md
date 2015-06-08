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
    
    div {
    position: relative;
    }

  .inner-image {
  position: absolute;
  top: 15px;
  right: 30px;
}
    
    
}
</style>

My attempt to make a Blog
<img src="/assets/images/blake.jpg" alt="Blake">   


<div>
  <img src="/assets/images/blake.jpg" alt="" class="inner-image"/>
  <img src="http://p1.pichost.me/i/45/1685510.jpg" alt="" />
</div>


List of posts 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



