---
layout: page
title: Fast Thermal Simulation for Metal AM
description:  
importance: 1
category: work
---

The influence of temperature plays a pivotal role in various aspects of metal additive manufacturing (AM), including melt-pool dimensions, defect distribution, and microstructure formation. Consequently, understanding temperature dynamics provides valuable insights for part design, process planning, and control. However, physics-based models are computationally inefficient for inverse design and real-time applications. To overcome this, we utilize machine learning techniques to create surrogate models capable of real-time simulations while maintaining high fidelity across diverse scenarios.

<div class="row justify-content-center align-content-center">
    <div class="col-md-12 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/projects/simu.gif" title="Fast Thermal Simulation for Metal AM" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<!-- <div class="caption">
    Fast Thermal Simulation for Metal AM.
</div>
 -->


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[thermal_simu=true]* %}
</div>
