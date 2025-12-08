---
layout: project
title: Modified Torque Wrench
description: Cornell MAE 3270 Modified Torque Wrench
technologies: [MATLAB, Fusion 360, Ansys, Git]
image: /assets/images/cubesat.jpg
order: 7
---

---

I designed a non-ratcheting, 3/8-inch drive instrumented torque wrench rated for 600 in-lbf and performed finite element analysis to evaluate its performance. The wrench will measure torque via strain gauges mounted on its sides, and my primary design goal is to maximize voltage output (mV/V) at the rated torque, with a minimum requirement of 1.0 mV/V at 600 in-lbf; higher output improves sensitivity and the signal-to-noise ratio. My design must satisfy multiple mechanical constraints: it must not fail under static loading, crack growth, or fatigue, and it must sustain a fully reversed torque of ±600 in-lbf for 10^6 cycles. Safety factors are specified as X₀ = 4 for yield, XK= 2 for crack growth from an assumed initial crack depth of 0.04 inches (1 mm), and XS = 1.5 for fatigue stress. The material choice is limited to steel, aluminum, or titanium alloys, and the design is optimized to maximize strain gauge output while meeting all structural and fatigue requirements. Here is my design!


<figure style="text-align:center; margin: 1em 0;">
  <figcaption style="font-size:0.9em; margin-bottom: 0.5em;">1U CubeSat mechanical layout and image processing telemetry:</figcaption>
  <img src="{{ '/assets/images/guano.png' | relative_url }}" alt="CubeSat model" style="width:50%; display:inline-block;">
</figure>


---
---

