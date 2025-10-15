---
layout: about
title: Yang Tian
permalink: /
subtitle: <a href='https://impacts.ucar.edu/en/persons/yang-tian'> NCAR scientist</a> 
img: /assets/img/DKRZ.de.jpeg
description: ytian@ucar.edu

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>ytian@ucar.edu</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

#announcements:
#  enabled: true # includes a list of news items
#  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
#  limit: 5 # leave blank to include all the news in the `_news` folder

#latest_posts:
#  enabled: true
#  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
#  limit: 3 # leave blank to include all the blog posts
---
*Cloud-Environment Interaction* · *Extremes & Resilience* · *Physics-Informed Machine Learning* 

I am a climate scientist studying the feedbacks between moist convection and the large-scale environment. I integrate theory, field observation, high-resolution modeling, climate modeling, and physics-informed machine learning to improve the fidelity of Earth system models.

My vision is to lead an interdisciplinary program that connects small-scale
convective physics to global climate risks and societal resilience.


<!-- ===========================
 RESEARCH THEMES
=========================== -->

<style>
.research-block {
  background: rgba(248, 248, 248, 0.75);
  border-radius: 12px;
  padding: 1.8rem 1.5rem;
  margin-bottom: 2.8rem;
  box-shadow: 0 3px 8px rgba(0,0,0,0.04);
  transition: transform 0.2s ease;
}
.research-block:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 12px rgba(0,0,0,0.08);
}
.research-block h4 {
  font-weight: 600;
  margin-bottom: 0.75rem;
}
.research-divider {
  border-top: 2px solid #e8e8e8;
  margin: 3rem 0;
}
</style>

<section class="research-themes py-5">
  <div class="container">
    <h2 class="text-start mb-5">Research Themes</h2>

    <!-- Theme 1 -->
    <div class="research-block">
      <div class="row align-items-center mb-3">
        <div class="col-md-7 text-center">
          {% include figure.liquid
             path="assets/img/publication_preview/linear_response2.gif"
             class="img-fluid rounded shadow-sm"
             alt="LES + Lagrangian particle tracking + Linear response functions"
             caption="LES + Lagrangian particle tracking + Linear response functions"
          %}
        </div>
        <div class="col-md-5">
          <h4 class="fw-semibold text-accent mb-2">Multiscale Cloud–Environment Interactions</h4>
          <p>Exploring cold-pool dynamics, entrainment, and updraft evolution through LES, Lagrangian analyses, and linear response functions to connect convective physics with the large-scale environment.</p>
        </div>
      </div>
    </div>

    <div class="research-divider"></div>

    <!-- Theme 2 -->
    <div class="research-block">
      <div class="row align-items-center flex-md-row-reverse mb-3">
        <div class="col-md-5 text-center">
          {% include figure.liquid
             path="assets/img/publication_preview/LES_congestus.png"
             class="img-fluid rounded shadow-sm"
             alt="LES + Lagrangian particle tracking + Piggybacking"
             caption="LES + Lagrangian particle tracking + Piggybacking"
          %}
        </div>
        <div class="col-md-7">
          <h4 class="fw-semibold text-accent mb-2">Cloud–Aerosol Interactions and Microphysics</h4>
          <p>Quantifying aerosol influences on droplet activation, precipitation efficiency, and convective transitions using field observations, cloud microphysics, and high-resolution modeling.</p>
        </div>
      </div>
    </div>

    <div class="research-divider"></div>

    <!-- Theme 3 -->
    <div class="research-block">
      <div class="row align-items-center mb-3">
        <div class="col-md-5 text-center">
          {% include figure.liquid
             path="assets/img/publication_preview/amazon_deforestation.gif"
             class="img-fluid rounded shadow-sm"
             alt="LES + Observation + Km-scale modeling"
             caption="LES + Observation + Km-scale modeling"
          %}
        </div>
        <div class="col-md-7">
          <h4 class="fw-semibold text-accent mb-2">Coupled Earth-System Feedbacks and Resilience</h4>
          <p>Investigating land–atmosphere coupling, moisture recycling, and climate tipping behavior to reveal the resilience limits of the Amazon and other ecosystems under warming.</p>
        </div>
      </div>
    </div>

    <div class="research-divider"></div>

    <!-- Theme 4 -->
    <div class="research-block">
      <div class="row align-items-center flex-md-row-reverse mb-3">
        <div class="col-md-5 text-center">
         {% include figure.liquid
             path="assets/img/publication_preview/dyamond_banner.jpg"
             class="img-fluid rounded shadow-sm"
             alt="LES + Observation + AI + Km-scale modeling + Climate modeling"
             caption="LES + Observation + AI + Km-scale modeling + Climate modeling"
          %}
        </div>
        <div class="col-md-7">
          <h4 class="fw-semibold text-accent mb-2">Toward Predictive Earth-System Intelligence</h4>
          <p>Integrating physics-based models and machine learning toward hybrid frameworks for process emulation and next-generation Earth-system predictability.</p>
        </div>
      </div>
    </div>

  </div>
</section>
