---
layout: project
title: MAE 3270 Torque Wrench
description: Cornell MAE 3270 Modified Torque Wrench
technologies: [MATLAB, Fusion 360, Ansys]
image: assets/images/torque.png
order: 1
---

I designed a non-ratcheting, 3/8-inch drive instrumented torque wrench rated for 600 in-lbf and performed finite element analysis to evaluate its performance. The wrench will measure torque via strain gauges mounted on its sides, and my primary design goal is to maximize voltage output (mV/V) at the rated torque, with a minimum requirement of 1.0 mV/V at 600 in-lbf; higher output improves sensitivity and the signal-to-noise ratio. My design must satisfy multiple mechanical constraints: it must not fail under static loading, crack growth, or fatigue, and it must sustain a fully reversed torque of ±600 in-lbf for 10^6 cycles. Safety factors are specified as X₀ = 4 for yield, XK= 2 for crack growth from an assumed initial crack depth of 0.04 inches (1 mm), and XS = 1.5 for fatigue stress. The material choice is limited to steel, aluminum, or titanium alloys, and the design is optimized to maximize strain gauge output while meeting all structural and fatigue requirements. Here is my design:

<iframe 
  src="https://drive.google.com/file/d/1A9vRW8zwNwK4mO437xxOAILcDzvHvLFx/preview" 
  width="100%" 
  height="800px" 
  style="border:0;">
  This browser does not support embedded PDFs — 
  <a href="https://drive.google.com/file/d/1A9vRW8zwNwK4mO437xxOAILcDzvHvLFx/view?usp=sharing">Download the PDF</a>.
</iframe>
