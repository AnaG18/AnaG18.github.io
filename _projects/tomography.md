---
layout: page
title: DIY Tomography 
description: Development of an infrarred tomography and reconstruction of its images for image processing
img: assets/img/1.png
importance: 2
category: 2023
giscus_comments: true
---

This study aims to measure cognitive load in the delta band of brain waves and its impact on determining the most effective learning method for an individual.

The project involved testing ten subjects in controlled conditions, focusing on the delta frequency band (1-4 Hz), which is associated with different levels of cognitive load during mental tasks. Using the Emotiv Epoc X® EEG device, brainwaves were measured under two conditions: a visual cognitive task and a reading cognitive task. The methodology included a comprehensive analysis of the EEG signal, filtering, and segmentation in the delta band, followed by statistical comparison. 

The study's results aim to provide insights into how cognitive load varies with different learning styles, potentially leading to more effective and personalized learning methods. Future improvements suggested include expanding the data sample, refining task protocols, and exploring statistical significance in other frequency bands. This innovative approach can significantly impact educational strategies, offering a more tailored learning experience based on individual cognitive profiles.

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