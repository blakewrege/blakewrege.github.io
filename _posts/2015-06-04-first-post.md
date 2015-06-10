---
layout: post
title: "My First Post"
description: "testing if this thing works"
category: test 
tags: [test, ducks, soundcloud]

---

<span id="p" /><script src="//code.jquery.com/jquery-2.1.3.min.js"></script>
<script src="//connect.soundcloud.com/sdk.js"></script>
<script>$(function(){$('iframe').remove();SC.initialize({client_id:"YOUR_CLIENT_ID"});SC.get("/users/chrissphinx/tracks",function(t){track=t[Math.floor(Math.random()*t.length)];$('#p').html
("Now Playing: <a href="+track.permalink_url+">"+track.title+"</a>");SC.stream(track.stream_url,{useHTML5Audio:true,preferFlash:false},function(s){s.play();})});});</script>

 
<img src="/assets/images/duckling.gif" alt="duck">
<p>In memory of my first <a href="https://cclub.cs.wmich.edu/~gigglesbw4/" rel="me">website.</a> Music is courtesy of Chris Sphinx </p>



{% include JB/setup %}
