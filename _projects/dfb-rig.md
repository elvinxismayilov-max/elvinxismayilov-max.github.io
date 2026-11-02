---
layout: page
title: Dual fluidized bed rig
description: A cold flow rig I built from scratch to study how solids circulate between two reactors.
img: assets/img/dfb-rig/rig-front.jpg
importance: 1
---

<!-- Case study for the MS rig. Photos live in assets/img/dfb-rig/.
     Method and Results sections get added after the invention disclosure is filed. -->

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dfb-rig/rig-front.jpg" title="Dual fluidized bed rig" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The cold flow dual circulating fluidized bed rig.
</div>

## Problem

Chemical looping combustion and some clean hydrogen processes move solid particles in a loop between two connected fluidized beds. The solid circulation rate is a key operating variable in these systems. Measuring it continuously, without disturbing the flow, is hard. That was the goal of my MS research.

## What I built

I built a cold flow dual circulating fluidized bed rig from scratch. Cold flow means it runs on air at room temperature, so the solids can be watched through the clear columns and measured safely. Gary Stowe helped me build the reactor, and Jeff McCaskill helped me get the circulation materials.

I set up data acquisition with pressure and flow sensors in LabVIEW, and wrote the Python code that turns the raw signals into final figures. I ran a series of steady-state tests with different sands, bed inventories and air flowrates.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/rig-with-elvin.jpg" title="Elvin with the rig" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Me with the rig.
</div>

### Some of the materials

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/sand-2.jpg" title="Sand sample" class="img-fluid rounded z-depth-1" caption="Sand sample." %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/sand-4.jpg" title="Sand sample" class="img-fluid rounded z-depth-1" caption="Another sand sample." %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/3d-printed-part.jpg" title="3D printed part" class="img-fluid rounded z-depth-1" caption="3D printed part with steel wool and mesh layers." %}
    </div>
</div>

### Some of the instruments

A few of the instruments on the rig. The full setup includes more equipment that is not shown here.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/daq.jpg" title="Data acquisition device" class="img-fluid rounded z-depth-1" caption="Data acquisition device." %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/mass-flow-meter.jpg" title="Mass flow meter" class="img-fluid rounded z-depth-1" caption="Mass flow meter." %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/flow-meter.jpg" title="Flow meter" class="img-fluid rounded z-depth-1" caption="Gas flow meter." %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dfb-rig/compressor.jpg" title="Air compressor" class="img-fluid rounded z-depth-1" caption="Air compressor." %}
    </div>
</div>

## Method and results

The measurement method is covered by an invention disclosure under review at the University of Oklahoma. The method, equations and results will be added here once it is filed. A paper on this work is in preparation with Dr. Baharak Sajjadi.
