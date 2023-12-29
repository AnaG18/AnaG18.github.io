---
layout: page
title: hands-on data
description: Developing the foundations of a haptic mouse for digital navigation
img: assets/img/handson_mouse.png
importance: 3
category: 2023
---

Currently available devices for blind computer users rely heavily on audio feedback, braille translation making
digital interactions complex and time consuming. In this paper we propose a new approach to enhance interpretability of digital data visualization for individuals with visual impairments. Our approach is to leverage haptic feedback and repurpose the computer mouse into an inclusive resource that allows blind users to navigate graphical data easily. The inherent points of contact on the hand facilitated by the mouse provide the means to overcome limitations encountered by existing haptic devices, enabling exploration of multiple sensory modalities while promoting kinesthetic exploration. By integrating haptic feedback into a common handheld device, we pave the way for a more equitable digital experience, enabling efficient extraction of essential information from graphics.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/handson_delta.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/handson_schematic.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, we can we the first prototype of the delta mechanism highlighting the 3 DC motors, links, joints and end-effector. On the right, a schematic diagram of the communication protocol that controls the feedback of the mouse. 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/handson_gui.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Performance of the linear performance of the actuated motor through the serial communication protocol established between the Arduino IDE and the Processing IDE.
</div>

This project was done in collaboration with the Social Haptics Robotics and Education Laboratory at Carnegie Mellon University under the supervision of Songwei Fan and Dr. Melisa Orta Martinez. 