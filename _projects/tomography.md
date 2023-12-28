---
layout: page
title: DIY Tomography 
description: Development of an infrarred tomography and reconstruction of its images for image processing
img: assets/img/1.png
importance: 2
category: 2023
giscus_comments: true
---

Advanced biomedical imaging techniques have proven to be in increasing demand. Alongside new methods like artificial intelligence and machine learning we built the prototype of a non-ionizing tomograph. This machine is built out of a pair stepper motors, wooden platforms, 9 infrared leds and 9 photoreceptors. 

The objective of this project was to get a hands on experience on how imaging devices work and furthermore learn processing techniques acuired with the same device. icantly impact educational strategies, offering a more tailored learning experience based on individual cognitive profiles.

We were able to refine the processing technique to reconstruct images with limited software. Throughout this process we were able to determine parameters such as Edge Spread Function (ESF), Line Spread Function (LSF), and Full Width at Half Maximum (FWHM) of our tomograph. The reconstruction of the images were achieved using interpolation, Fourier & Radon transforms, and filtering techniques such as Canny or Sobel. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eeg_pca.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eeg_subject.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eeg_zoom.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, we see an image of the PCA components observed in the acquired EEG waves of one subject, this was one of the main processes to clean the signals. On the center we see one of the subjects wearing the Emotiv Epoc headset performing one of the tasks. Finally, on the right, we see one of the subjects final filtered where the power density of the signal can be observed. In this case, in blue we see the activity during the visual task, and in the red the activity during the reading task. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eeg_experiment.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image depicts the breakdown of the experiemnt in relation to the EEG signal. The experiment consisted of one minute of calibration task for the visual portion. Followed by three trials of visual tasks. Then one minute of calibration for the reading task, followed by another three trials for a reading task. The total duration was of 30 min, without set-up.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/eeg_procedure.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Visualization of the signal processing for this experiment. 
</div>

This project was done in collaboration with Paulina Orozco, Ana P. García, Ana P. Aranda, Myrna A. López, and Natalia Gamboa.