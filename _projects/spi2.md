---
layout: page
title: Layout Design of Complex System
description:  
importance: 1
category: work
---
3D spatial packaging of interconnected systems with physical interactions (3D SPI2) problems are ubiquitous on compact engineered systems, such as power-dense batteries, spacecraft cooling systems, medical wearables, vehicles with more usable volume, and avionics and military electronic systems.
The complex goals of 3D SPI2 design include reducing the size of complex systems and the length of routing, avoiding components and routing overlapping, satisfying physics-related constraints (thermal, hydraulic, electromagnetic, etc.), and improving spatial accessibility to support safe and efficient manufacture and post-manufacturing processes. 

We build an integrated packing and routing optimization framework that considers packing, routing, and physics-related performance simultaneously. It is open to components with arbitrary shapes, and
can efficiently explore and converge to optimal solution with gradient-based optimization methods.

<div class="row justify-content-center align-content-center">
    <div class="col-md-12 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/projects/two_route_2d.gif" title="Optimize a 2D interconnected system" class="img-fluid rounded z-depth-1" %}
        <p>Optimize a 2D interconnected system in 2D space</p>
    </div>
</div>

<div class="row justify-content-center align-content-center">
    <div class="col-md-12 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/projects/two_route_2d_lift.gif" title="Optimize a 2D interconnected system in 3D space" class="img-fluid rounded z-depth-1" %}
        <p>Optimize a 2D interconnected system in 3D space</p>
    </div>
</div>


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[spi2=true]* %}
</div>
