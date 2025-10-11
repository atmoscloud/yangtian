---
layout: page
title: Multiscale Cloud-Environment Interactions
description: Process-level physics from a Lagrangian perspective
img: assets/img/DKRZ.de.jpeg
image_width: 1600
importance: 1
category: work
related_publications: true
---

### Cold pool dynamics

Cold pools can trigger new convection mechanically, through lifting by the gust fronts, or thermodynamically, by accumulation of moisture around the edges of cold pools, but the relative importance is unknown. 

<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/cold_pool.png"
       caption="LES simulations of cold pool"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>

By releasing Lagrangian particles into the simulated cloud field, we explictly track the life cycle of cold pool, and diagnose the relative contribution from dynamic and thermodynamic forcing {% cite torri2015coldpools %}.

<div class="row align-items-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/cold_pool_forcing.png"
       caption="Buoyancy and mechanical forcing"
       class="img-fluid rounded shadow-sm"
    %}
  </div>

  <div class="col-md-4 d-flex align-items-center justify-content-center">
    <p class="text-center">
      $$\nabla^{2}P_{M} = -\nabla \cdot (\rho\vec{v} \cdot \nabla\vec{v})$$
      $$\nabla^{2}P_{B} = \partial_{z}(\rho B) $$
    </p>
    <p class="small text-muted text-center">Pressure gradient force decomposition</p>
  </div>
</div>

Both mechanical forcing due to gust front lifting and thermodynamic forcing due to MSE anomaly play roles in triggering convection, but they are important at different stages of convective development, with mechanical forcing more important close to the surface. 

Cold pools tend to be relatively young when they lift triggered particles and that a large number of triggered particles reach their LFC without residing in a cold pool.

<br><br>

### Entrainment mixing

Short blurb tying your LES + theory to macroscale outcomes. One crisp sentence linking to parameterization implications {% cite tian2016entrainment %}.

<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/entrainment_schematic.jpg"
       caption="Entrainment mixing schematic"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>
To disentangle the controlling factors of entrainmnent mixing, we designed a linear response framework by adding a horizontal temperature perturbation in the simulated cloud field, and compared control-perturbed pairs. 
<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/entrain1.png"
       caption="Horizontally uniform temperature perturbation"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>
The difference in the figure shows the impacts of temperature perturbation on relevant variables, grouped by detrainment heights of Lagrangian particles. 
<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/entrain2.png"
       caption="Cloud properties from a Lagrangian perspective"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>
The linear response theory reveals a new entrainment formula as $$ \epsilon = \frac{\alpha}{wd}$$
<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/entrain3.png"
       caption="Linear responses in entrainment and other factors"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>

<br><br>


### Updraft momentum

The abovementioned pressure gradient forces do not only play important roles in triggering convection due to cold pool, but also affect the updraft momentum evolution significantly. However, they are poorly represented in current convection parameterization. We designed a deterministic cartoon model to include these important terms. 

<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/updraft_model2.png"
       caption="A simple cartoon model for updraft momentum"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>

With the simple cartoon model, we have explicitly calculated the virtual mass coefficient and dynamical pertur- bation pressure, which could be useful in parameterizing vertical velocity in convective schemes

<div class="row justify-content-center my-3">
  <div class="col-md-8 text-center">
    {% include figure.liquid
       path="assets/img/publication_preview/updraft_model1.png"
       caption="Cloudy updraft dynamics simple model"
       class="img-fluid rounded shadow-sm"
    %}
  </div>
</div>
<br><br>
