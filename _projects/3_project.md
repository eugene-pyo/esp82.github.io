---
layout: page
title: travel
description: 
img: assets/img/7.jpg
importance: 3
category: 
---

I have been fortunate to be able to travel and I enjoy it so much!
I have visited many places in America and also abroad. I try to go to South Korea every two years to go see my relatives. I will share some of my favorite vacations below.

## Europe 2018
I went to Europe with my family. We first went to London and visited the Big Ben, Buckingham Palace, Tower Bridge, and a Tottenham Hospur soccer match. I had a great time shopping on Bond Street and eating foods like fish and chips. The next part of the itinerary was to the capital of France. We visited world-reknowned landmarks like Notre Dame Cathedral, Eiffel Tower, Louvre Museum, and the Arc de Triomphe. We also ate signature foods like escargot and macarons. I had such a great time and hope to go back to these cities again.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/europe2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/europe1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/europe3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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

## Japan 2018
I took a quick four day stop at Japan before going to South Korea. With one of my closest friends, I went to the cities of Osaka and Kyoto. The two cities have big contrasts and it was nice to experience them both: Osaka is filled with entertainment as Kyoto is a historic city. We went to Osaka Castle, Osaka Aquarium, Nara deer park, Arashimaya bamboo forest, and Fushimi Inari-taisha Shrine. Food was a highlight of the trip as I ate great ramen, sushi, udon, and soba noodles.

## Hawaii 2019
This was a spring break trip with members of a dance crew I was invovled in during college. We had a local Hawaiian go with us, so we were able to go to the local spots. We snorkeled at shark cove, sun bathed at Waikiki beach, and went hiking. We also went to Dole pineapple farm and ate local foods like pokebowls. This trip made me experience the natural beauties I have never seen before.

## Seattle 2021
I went with a group of high school friends because we had another friend staying there over the summer. We hiked at Mt. Rainier, walked around Pike Place Market, and walked by the Amazon headquarters.

## California 2022
The first stop was to Los Angeles. I went to Universal Studios, Holleywood Walk of Fame, Koreatown, and Santa Monica Beach. I then flew to San Francisco to visit two college friends. We went to the Golden Gate Bridge, Google campus, and by the pier to see wild sea lions.

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

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


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
