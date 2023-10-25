---
layout: page
title: 3D Scene Neural Stylistic Rendering
time: 03/2017 – 08/2018
tag: Master's Thesis
description: 
img: assets/img/stylisticrend.png
importance: 4
category: Graphics/Vision
---


#### Master's Thesis:

Time: 03/2017 – 08/2018

Advisor: Xuguang Lan, Nanning Zheng

Affiliation: Institute of Artificial Intelligence and Robotics @ Xi'an Jiaotong University


#### Project: Knowledge-guided Neural Stylistic Rendering for 3D Scene Models

Studied human knowledge-guided neural style transfer, focusing on improving the illusion of space in generated images by simulating how artists harness skills to understand and reproduce a 3D scene--that is, leveraging geometric structures or the disentanglement of lighting and shallow layers. There are 2 target tasks:
- Task 1: 3D model non-photorealistic rendering
- Task 2: Low-quality Image non-photorealistic enhancement

We proposed an *illumination-guided deep alignment* method, which adaopts *Lighting Path Expression* and *PatchMatch* in CNN architecture to achieve the two tasks.

#### Data:

Created a 2D-3D dataset, including 3D models rendered by multiple types of lighting (by Maya), 2D photos annotated by lighting and segmentation (by Photoshop and Matlab), and a hand-drawn stylistic material for testing (CorelPainter).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/stylisticrend.png" title="3d-to-2d Art dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/mythesisdata.png" title="3d-to-2d Art dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### Some Results:

<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/mythesis2.jpg" title="3d-to-2d Art dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/mythesis.jpg" title="3d-to-2d Art dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>