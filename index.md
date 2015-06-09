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

.bio.vertical-center {
  margin-bottom: 0; 
}

.vertical-center {
  min-height: 100%;
  min-height: 100vh; 
  display: -webkit-box;
  display: -moz-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex; 
  width: 100%;
  
         -webkit-box-pack : center;
            -moz-box-pack : center;
            -ms-flex-pack : center;
  	 -webkit-justify-content : center;
          justify-content : center;
}

}

</style>



My attempt to make a Blog
	<img src="/assets/images/blake.jpg" alt="Blake">   
<div class="bio vertical-center">
	<div class="container text-center">
<p class="text-center">Hello I'm Blake Wrege! I'm a full time Student at WMU and a part time computer technician for the College of Arts and Sciences. This website will forever be a work in progress as I am always striving to find ways to improve.</p>
	</div>
</div>


List of posts 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



