---
layout: page
title: Coupled Earth-System Feedbacks and Resilience
description: Linking clouds, land, and biosphere processes in Earth’s climate system
img: assets/img/publication_preview/amazon_deforestation.gif
importance: 3
category: work
---

Amazon plays a key role in regulating the global hydrological cycle, but the feedback between clouds, land and biosphere over this region is poorly constrained, we used observation, LES, and climate models to investigate this complicated feedback mechanisms. 


<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/ARM_AMF.jpg"
       caption="DOE ARM GoAmazon deployment"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
  <div class="col-md-4 d-flex align-items-center justify-content-center">
    {% include video.liquid
     path="assets/video/deep_ani.mov"
     autoplay=true
     loop=true
     muted=true
     playsinline=true
     caption="A suite of instruments to identify various convective regimes"
    %}
  </div>
</div>

Based on GoAmazon observations, we identified a "double-pulse" phenomenon of afternoon precipitation, and investigated the underlying mechanism. The first round of precipitation occurs around 1300 LST and the second one occurs two hours later.

<div class="row justify-content-center my-3">
  <div class="col-md-9 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/double_pulse1.png"
       caption="Single and double pulse of afternoon precipitation"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>

The first round of convection features mostly randomly scattered deep convection, whereas the second round is more organized. 

<div class="text-center my-3">
  {% include video.liquid
     path="assets/video/grl_2025.mp4"
     autoplay=true
     loop=true
     muted=true
     playsinline=true
     max-width="75%"
     caption="LES simulation of diurnal cycles"
  %}
</div>

The mechanism behind double-pulse of precipitation is closely related to cumulus congestus clouds.

<div class="row justify-content-center my-3">
  <div class="col-md-9 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/double_congestus.png"
       caption="LES simulations of cold pool"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>

<div class="row justify-content-center my-3">
  <div class="col-md-9 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/GRL_2022.png"
       caption="LES simulations of cold pool"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>

We use the same initial and boundary conditions to force high resolution E3SM simulations

<div class="row justify-content-center my-3">
  <div class="col-md-9 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/e3sm_bias.png"
       caption="Comparison between LES and high-res E3SM simulation"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>

Even at 250m, the E3SM-SCREAM cannot reproduce the second pulse of precipitation, and denoted by a lacking of congestus clouds. 

<div class="row justify-content-center my-3">
  <div class="col-md-9 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/BAMS.png"
       caption="High-res South America simulation"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>


