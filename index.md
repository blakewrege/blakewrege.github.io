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
}
</style>

My attempt to make a Blog
<img src="/assets/images/blake.jpg" alt="Blake">   

    <header>
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <img class="img-responsive" src="/assets/images/blake.jpg" alt="">
                    <div class="intro-text">
                        <span class="name">Start Bootstrap</span>
                        <hr class="star-light">
                        <span class="skills">Web Developer - Graphic Artist - User Experience Designer</span>
                    </div>
                </div>
            </div>
        </div>
    </header>


List of posts 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



