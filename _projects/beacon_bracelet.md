---
layout: page
title: Beacon Bracelet
description: Prototype of bracelet system using Bluetooth modules and electronic beacons to help visually impaired individuals navigate public transportation routes and stops more easily.
img: assets/img/beacon_prototype.png
importance: 1
category: 2021
---

Project aimed at assisting the School for Blind Children in Jalisco. It involves the creation of a bracelet and a system using Bluetooth modules and electronic beacons to help visually impaired individuals navigate public transportation routes and stops more easily. The proposal includes a two-component system: a wearable accessory (bracelet or watch) for the user and a device that can be securely and practically attached to a bus. This project is designed to address two key issues faced by the blind community: difficulty in identifying which bus to board and when to disembark.

The bracelet design is based on a smartwatch model, featuring buttons for volume control, a section for the Arduino Nano and Bluetooth module, and a speaker. The materials for the prototype include flexible polymer for the bracelet and various electronic components. The project also contemplates the use of beacons installed in buses and at stops, which the bracelet can detect and inform the user about their proximity to a bus stop or route. The aim is to provide visually impaired children with greater independence and ease in using public transportation, ultimately improving their quality of life.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/beacon_circuit.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/beacon_draw.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, we see the diagram of the first circuit for the prototype. This includes the connection of a small speaker and an RFID module into an Arduino Uno. On the right, we see the initial design of the bracelet. 
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/beacon_video.mp4" title="example video" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    In this video you can see a simple representation of what the objective of the project is. During this video we only show how the text-to-speech portion of the bracelet reacts in the desired scenerio. 
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/beacon_pseudo.png" title="pseudo code" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    In this image we break down the pseudo code for the implementation of the first prototype. 
</div>

In collobaration with Diego Gatica Murrieta, Javier Ramírez Robles, José Avir Gariel Guerrero,
 Oscar Osvaldo García de la Fuente. 
