---
name: Laser Projector - UBC Coursework
tools: [Simulink, SOLIDWORKS, Control Systems]
image: /assets/img/laser-1.jpg
description: 2-DOF laser projection system featuring PID control and 3D-printed housing.
---

### Situation
Required a laser to project a static image onto a flat surface through high-speed movement.

### Action
* ![Simulink Controls Diagram](/assets/img/laser-2.jpg)
* Designed and 3D printed a 2-DOF system in SOLIDWORKS to control laser direction.
* Modeled system dynamics and tuned PID controllers using Simulink.
* Integrated a PID Controller, Motor Transfer Function, and Derivative Weighted Sum Filter to optimize trajectory tracking.
* Implemented Feedback Weighted Sum Filters and Sensor Gains to minimize error.
<div style="display: flex; justify-content: space-between; gap: 10px; margin-bottom: 15px;">
  <div style="flex: 1; text-align: center;">
    <img src="/assets/img/laser-1.jpg" alt="System Assembly" style="width: 100%; border-radius: 8px; border: 1px solid #333;">
    <small>Final System Assembly</small>
  </div>
  <div style="flex: 1; text-align: center;">
    <img src="/assets/img/laser-3.jpg" alt="Exploded View" style="width: 100%; border-radius: 8px; border: 1px solid #333;">
    <small>Exploded View - Internal Components</small>
  </div>
</div>

### Result
Achieved stable laser positioning with low overshoot and accurate tracking [cite: 146-148].