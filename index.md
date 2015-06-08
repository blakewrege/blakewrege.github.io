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
    div.background {width:500px; height:500px; display:block; margin-left:auto; 
    margin-right:auto;background-color:Black;}

    div.box { margin: 0 auto; position: relative; top: 125px; width:250px; height:250px;background-color:white;border:5px        dotted white; opacity:0.5;}
    
    
}
</style>

My attempt to make a Blog
<img src="/assets/images/blake.jpg" alt="Blake">   


<div class="background">
    <div class="box">
        <img src="/assets/images/blake.jpg" alt="Blake"> 
    <br />
</div>


List of posts 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



