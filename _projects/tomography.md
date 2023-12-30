---
layout: page
title: DIY Tomography 
description: Development of an infrarred tomography and reconstruction of its images for image processing
img: assets/img/tomography_drawing.png
importance: 2
category: 2023
giscus_comments: true
---

Advanced biomedical imaging techniques have proven to be in increasing demand. Alongside new methods like artificial intelligence and machine learning we built the prototype of a non-ionizing tomograph. This machine is built out of a pair stepper motors, wooden platforms, 9 infrared leds and 9 photoreceptors. 

The objective of this project was to get a hands on experience on how imaging devices work and furthermore learn processing techniques acuired with the same device. icantly impact educational strategies, offering a more tailored learning experience based on individual cognitive profiles.

We were able to refine the processing technique to reconstruct images with limited software. Throughout this process we were able to determine parameters such as Edge Spread Function (ESF), Line Spread Function (LSF), and Full Width at Half Maximum (FWHM) of our tomograph. The reconstruction of the images were achieved using interpolation, Fourier & Radon transforms, and filtering techniques such as Canny or Sobel. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tomography_phantoms.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tomography_esf.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tomography_filter.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, imaging phantom and their reconstruction. In the center, ESF Curve of the reconstructed image showing. On the right, an image of the filtering process of the acquired image.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tomography_drawing.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Drawing of the first prototype for a 2 DOF tomography. 
</div>

This project was done in collaboration with Luis Gerardo Quezada Pérez, Francisco Santiago del Rio Escoto, Róger Antonio Gutiérrez Baldizón, Valeria Muñoz Rodríguez, Ana Paola Aranda Luelmo, and Ana Paula García Canales. 