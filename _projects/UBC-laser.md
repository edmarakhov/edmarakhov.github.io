---
weight: 9
name: Laser Projector - UBC Coursework
tools: [Engineering, Simulink, SOLIDWORKS, Control Systems]
image: /assets/img/laser-1.jpg
description: 2-DOF laser projection system featuring PID control and 3D-printed housing.
---

### Situation
* Required a laser to project a static image onto a flat surface through high-speed movement.

### Action
<div style="display: flex; justify-content: flex-start; gap: 15px; margin-bottom: 20px;">
  <img src="/assets/img/laser-2.jpg" alt="Simulink" style="width: 48%; border-radius: 4px; border: 1px solid #1c1c9e;">
  <div style="flex: 1; font-size: 0.95rem;">
    <p><strong>Simulink Controls Diagram</strong></p>
    <ul>
      <li>Designed and 3D printed a 2-DOF system in SOLIDWORKS to control laser direction.</li>
      <li>Modeled system dynamics and tuned PID controllers using Simulink.</li>
      <li>Integrated a PID Controller, Motor Transfer Function, and Derivative Weighted Sum Filter to optimize trajectory tracking.</li>
      <li>Implemented Feedback Weighted Sum Filters and Sensor Gains to minimize error.</li>
    </ul>
  </div>
</div>

<div style="display: flex; justify-content: space-between; gap: 10px; margin-bottom: 15px;">
  <div style="flex: 1; text-align: center;">
    <img src="/assets/img/laser-1.jpg" alt="System Assembly" style="width: 100%; border-radius: 4px; border: 1px solid #1c1c9e;">
    <small>Final System Assembly</small>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/assets/img/laser-3.jpg" alt="Exploded View" style="width: 100%; border-radius: 4px; border: 1px solid #1c1c9e;">
    <small>Exploded View - Internal Components</small>
  </div>
</div>

### Result
* Achieved stable laser positioning with low overshoot and accurate tracking.