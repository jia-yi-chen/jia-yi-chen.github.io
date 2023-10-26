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


### Master's Thesis:

Time: 03/2017 – 08/2018

Advisor: Xuguang Lan, Nanning Zheng

Affiliation: Institute of Artificial Intelligence and Robotics @ Xi'an Jiaotong University


### Title: Spatially-rational Knowledge-guided Neural Stylization

The reseach aims to leverage human knowledge to improve neural style transfer, focusing on enhancing the *Spatial Rationality* of generated images (i.e., an illusion of spatial logic and ordering). There are 2 target tasks, where traditional methods fail to produce robust spatial rationality:
- Task 1: 3D model non-photorealistic rendering
- Task 2: Low-quality Image non-photorealistic enhancement

To address these tasks, this project aims to *simulates how artists harness skills to understand and reproduce a 3D scene*. For example, we can consider the underlying geometric structures or the human knowledge of disentangled lighting & shallow layers in the target 3d scene or image scene.  We proposed an *illumination-guided deep alignment* method, which leverages *Lighting Path Expression* and *PatchMatch* into CNN architecture to achieve the goals.

### Data Creation:

I manually created a small 2D-to-3D dataset for this project. The dataset includes 
- 3D models rendered by multiple types of lighting (created using Maya)
- 2D photos annotated by lighting and segmentation (created using Photoshop and Matlab), and 
- Hand-drawn stylistic material examples (drawn using CorelPainter)

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


### Related Skills
- Keras, Tensorflow
- Python
- Multimedia SKills: Unity3D, Photoshop, Maya, CorelPainter



### Some Results:



<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/mythesis_3d.jpg" title="3d-to-2d Art dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/mythesis_2d.jpg" title="3d-to-2d Art dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/mythesis2.jpg" title="3d-to-2d Art dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

