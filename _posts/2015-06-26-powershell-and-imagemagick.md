---
layout: post
title: "PowerShell and ImageMagick"
description: "Using PowerShell and ImageMagick to batch edit pictures"
category: PowerShell
tags: [powerShell, imagemagick, scripting]
---
<img style="display: block; margin-left: auto;margin-right:" auto  src="/assets/images/Imagemagick.jpg" alt="broke">
<p>I wrote this handy script last year while I was working on ticket reports for work. I was looking for a simple way to add captions to the bottem of every picture in a folder without opening each individually. Since I couldn't find any tools online the would perform this task. I wrote my own batch picture captioning script in PowerShell using 
<a href="http://www.imagemagick.org/script/binary-releases.php#windows">ImageMagick</a> command line tools. I modified it so that it has 3 options: label each picture picture with it's name, label each picture with a custom caption or caption a single picture in the folder. <a href="/assets/labeler.ps1">Download</a> </p>
<script type='text/javascript' src='//www.gistfy.com/github/gist/637235ed815f9e204218?slice=1:30&lang=powershell&style=monokai_sublime'></script>



{% include JB/setup %}
