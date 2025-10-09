---
layout: page
title: Multiscale Cloud-Environment Interactions
description: From turbulent plumes to organized convection and climate variability
img: assets/img/DKRZ.de.jpeg
image_width: 1600
importance: 1
category: work
related_publications: true
---

<!-- HERO (optional video or still) -->
{% if page.hero_video %}
<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:12px;box-shadow:0 4px 14px rgba(0,0,0,.12);margin-bottom:1.25rem;">
  <iframe src="{{ page.hero_video }}" title="LES convection"
          loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen
          style="position:absolute;inset:0;width:100%;height:100%;border:0"></iframe>
</div>
{% endif %}

## Vision
We connect **process-level physics** (entrainment, cold pools, updraft momentum, organization) with to explain and improve fundamental understanding of moist convection.

## A. Entrainment & Convective Sensitivity
Short blurb tying your LES + theory to macroscale outcomes. One crisp sentence linking to parameterization implications.{% cite einstein1950meaning %}

<div class="row">
    <div class="col-md-7">
        {% include figure.liquid loading="eager" path="assets/img/DKRZ.de.jpeg" title="LES simulations" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

## B. Cold Pools & Mesoscale Organization
Explain role of density currents, gust fronts, secondary initiation, and timing.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>



You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
