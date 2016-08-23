---
layout: default
title:  {{ site.name }}
---

## Intro
Hi, I'm Michael Viveros. I am a passionate programmer, incredibly inconsistent golfer and sarcastically subtle joker.

<p align="center"> <img src="../images/Me.jpg" width="450" height="450"></p>
<br>

## Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Projects

### BirdieStats
BirdieStats is an application used by golfers to track their stats. Users can input scores from a round on their phone and view all their scores on the website. Upcoming features include tracking stats like Handicap or Avg. Score on Par 3s.

----|----|----|----|
[Website](http://www.birdiestats.com) | [Android App](https://play.google.com/store/apps/details?id=com.michaelviveros.BirdieStats&hl=en) | [Code](https://github.com/MichaelViveros/BirdieStats) | [Doc](https://github.com/MichaelViveros/BirdieStats/tree/master/doc)

<p align="center"> 
  <img src="../images/Screenshot2.png" hspace="50" style="vertical-align: middle;">
  <img src="../images/BirdieStats_Architecture.png" hspace="50" style="vertical-align: middle;">
</p>

### CollageCreator
CollageCreator is a plugin for GIMP which automatically generates collages, given a folder of pictures. It was written in the functional programming language Scheme. GIMP is a GNU Image Manipulation Program, essentialy an open-source version of PhotoShop. 

[Code](https://github.com/MichaelViveros/CollageCreator)

<table>
<tr>
<td>
<pre lang="scheme">
(while (< i num-rows)
(set! y (* i pic-height))
(set! j 0)
(while (< j num-cols)
  ; get random pic and update pics-list
  (set! x (* j pic-width))
  (set! retvals
    (get-random-pic pics-list num-pics-left))
  (set! num-pics-left (- num-pics-left 1))
  (set! pic (car retvals))
  (set! pics-list (cadr retvals))

  ; open pic and check if portrait
  ...
</pre>
</td>
<td><img src="../images/DREAMS_2x2_2.jpg" width="450" height="310"></td>
</tr>
</table>

## Music
I have been playing the trumpet for over 8 years. As a member of the McMaster Marching Band, I played in many parades including the Toronto Santa Clause Parade and the Montreal St. Patrick's Day Parade.

<br>
<p align="center">
  <iframe src="http://www.youtube.com/embed/kTiLrF7Tfoc" width="354" height="300"></iframe>
  <img src="../images/MMB.jpg" alt="Collage" width="40%" height="100%" hspace="50">
</p>
<br>

## Volunteer

### Hamilton Code Club
I teach programming to a class of 20 middle-school kids as part of the [Hamilton Code Club](http://www.hamiltoncodeclub.com/). The language they learn is Scratch, a free visual programming language.

<p align="center"> <img src="../images/HamiltonCodeClub.jpg"></p>
<br>

### D.R.E.A.M.S
Also, I participated in 3 humanitarian trips to the Dominican Republic through D.R.E.A.M.S - Dominican Republic Education and Medical Support. I got to experience life in a 3rd World country and really enjoyed talking and laughing with the local Dominicanos.

<br>
<p align="center"> <img src="../images/DREAMS_3x3_1.jpg" width="800" height="533"></p>  
