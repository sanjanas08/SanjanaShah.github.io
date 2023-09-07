---
layout: page
title: United Mechanical Proxy Representation
description:  How do you check a cad and a mesh represent the same shape?
importance: 1
category: work
---

Traditionally, geometric processes are algorithms designed for specific applications and work on specific geometric representations. However, the evolution of computational design and manufacturing technologies results in numerous geometric representations that are often incompatible. To finish a mechanical design and manufacturing project, engineers ususally have to work across multiple systems.

This is a common challenge encountered by mechanical engineers. As depicted in the illustration below, when transitioning a CAD model into simulation software, determining the success of the conversion can be challenging, especially for highly intricate parts that defy visual inspection.
<div class="row justify-content-center align-content-center">
    <div class="col-md-12 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/projects/conversion_problem.png" title="conversion problem" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

We introduce a novel geometric representation called [Maximal Disjoint Ball Decomposition](https://www.sciencedirect.com/science/article/pii/S0010448520300439) (MDBD), which serves as a unique sphere packing approach applicable to any valid geometric representation of a given shape. As illustrated in the image below, we can employ MDBD as a proxy representation to assess whether two geometric models, represented using different methods, possess identical shapes.

<div class="row justify-content-center align-content-center">
    <div class="col-md-12 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/projects/mdbd_check.png" title="mdbd check" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[mdbd=true]* %}
</div>
