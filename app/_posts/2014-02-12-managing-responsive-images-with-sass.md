---
layout: post
title:  "Managing Responsive Image Display with Sass"
time:   6:30pm
venue:  "Canvas Coworking Space"
link:   "http://canvas.co/work"
addy1:  "1203 19th St. NW, 3rd Floor"
addy2:  "Washington, DC 20036"
map:    "http://maps.google.com/maps?q=1203+19th+St+NW,+Washington,+DC+20036"
nvit: "nvite.com/sassydc/feb2014"
---

<header>
  <h2>{{ page.title }}</h2>
  <time>{{ page.date | date_to_string }} at {{ page.time }}</time><br>
  <a href="{{ page.link }}">{{ page.venue }}</a><br>
  <a class="linkalt" href="{{ page.map }}"><span>{{ page.addy1 }}</span><br><span>{{ page.addy2 }}</span></a>
</header>

Sass can't help you swap out image sources, but it can be incredibly helpful in managing display variations across different screen sizes. Using real life examples from building the redesign of National Geographic Magazine we'll work our way from assessing the challenges to how using variables, mixins, and placeholder classes will keep your source code organized, extensible, and—most importantly—manageable.

Visit [{{page.nvit}}](http://{{page.nvit}}) to sign up!
