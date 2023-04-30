---
layout: page
title: sports
description: 
img: assets/img/12.jpg
importance: 1
category: 
---
Sports has been a big part in my life. I started playing since the age of five with baseball and ultimately got into soccer and basketball as well. I played in organized league and was on travel teams for baseball and soccer. On of my coolest memories was playing a soccer tournament at Giants Stadium (now called Metlife Stadium, home of the New York Giants and Jets). In high school, I was on my school's varsity team, and played for the basketball team freshman year. Though I stopped playing in organzied leagues after high school, I play basketball with my friends at the local courts.

Aside from playing sports, I also watch it all year round. Ever since little me looked over my TV screen when my dad was watching sports, I started to become a fan of sports like basketball, baseball, soccer, and football, and developed interest in teams while calling myself a diehard fan.

These are the teams I am a fan of:

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

## New York Knicks
My dad was a huge fan of basketball. He occasionally went to New York Knicks games after work and his favorite player is Michael Jordan. Therefore, it was natural for me to pick up watching this sport and be a fan of the Knicks. I have been to a few games, the most recent visit being last season. The team has not shown a lot of success while I was a fan, but has been doing well recently and qualifying for the playoffs that is going on now.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/knicks.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

## New York Yankees
Baseball was the first sport I played and living in the New York metropolitan area, being a fan of the Yankees was a no brainer. I wanted to field like Derek Jeter and hit like Alex Rodriguez. I still remember watching the 2009 World Series when the Yankees was playing their championship clinching game. The game was lasting past midnight and 10 year old me was struggling to stay up, but the Yankees inching closer to the win was the driving force in keeping me awake. My favorite player now is Aaron Judge. I try to see the Yankees game at least once a season wearing my Judge jersey.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/yankees.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

## Seattle Seahawks
The Seahawks is the only team I support that is not a team based in my hometown. It was 2006 when my dad was watching the Superbowl in which the Seahawks were going against the Pittsburgh Steelers. He was supporting the Steelers because there was a half-Korean player Hines Ward who ended up being the MVP of that game. Being six years old, I was too young to know anything about the sport, but I did know that the Seahawks logo was way cooler than the opposition's. That is how I became a fan of the team and experienced a Superbowl win and many seasons of success with them. I have yet to go watch a Seahawks game, let alone an NFL game, but I hope to go soon.

## Tottenham Hotspur
Growing up, watching soccer matches in England was almost impossible. Personally, I believe that I was the best at playing soccer. Trying to get better, I went to YouTube to search up skills and plays that professional soccer players were doing to emulate their plays. This is when I came across Gareth Bale of Tottenham, who was really fast at dribbling and had an accurate and powerful shot. Thanks to the advancement of technology and streaming servies, it is a lot easy to watch games that are not show on US TV channels. In 2018, I had an unforgetable experience going to a Tottenham game while on a vacation to London with my family.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tottenham.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
