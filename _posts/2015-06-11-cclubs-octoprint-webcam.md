---
layout: post
title: "Cclub's OctoPrint Webcam"
description: "Computer Clubs 3D Printer"
category: 3D Printing
tags: [3D printing, octoprint, arduino, raspberry pi ]
---
<div id="webcam_container">
<img id="webcam_image" data-bind="css: { flipH: settings.webcam_flipH(), flipV: settings.webcam_flipV() }" class="" src="http://t4ls.duckdns.org:1337/webcam/?action=stream?1434033917766">
</div>
<p>This is Computer Club's 3D Printer. Our 3D printer is a PRUSA I3 by Makerfarm with a 10 inch bed. The printer runs on an Arduino MEGA board and we use a Raspberry Pi to run OctoPrint as a web interface</p>
{% include JB/setup %}
