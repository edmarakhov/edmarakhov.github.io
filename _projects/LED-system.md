---
name: Cyanobacteria Growth LED System - UBC Hallam Lab
tools: [Hardware, Embedded C, JavaScript]
image: /assets/img/hallam-2.jpg
description: Wireless LED driver system with remote scheduling for high-throughput biological experiments.
---

### Situation
The existing LED system required manual brightness tuning and lacked scheduling control, leading to limited throughput and high experimental errors.

### Action
* Designed an LED driver system using ESP32 for wireless scheduling and brightness control of 48V panels.
* ![LED Driver and Control Circuit Prototype](/assets/img/hallam-2.jpg)
* Programmed embedded firmware in C for PWM dimming and network communication.
* Built a web/mobile interface in HTML/JavaScript hosted on the ESP32 for remote control
* ![Web/Mobile Control](/assets/img/hallam-1.jpg).

### Result
Expanded capacity 5x to 13,860 cultures per experiment run. It is now the lab standard high-throughput system and is featured in a forthcoming peer-reviewed publication.
* ![Completed LED System](/assets/img/hallam-3.jpg).