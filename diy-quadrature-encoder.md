---
title: Quadrature Encoder Design & Control
description: Mechatronic implementation of a 2-channel encoder with custom signal processing for DC motor control.
image: assets/images/pic04.jpg
layout: page
---

## Project Overview
To demonstrate the fundamental principles of quadrature encoding and closed-loop control, I designed and built a low-cost, 2-channel quadrature encoder from the ground up. Unlike off-the-shelf optical encoders, this system utilized a custom-patterned concentric encoder disc and photoresistors (LDRs) to track the angular position and direction of a DC motor shaft.

### Key Engineering Skills Applied
* **Mechatronics & Sensor Integration:** Integrated a dual-channel LDR array with an Arduino microcontroller to create a feedback loop for motor actuation.
* **Signal Phase Alignment:** Physically positioned the sensors to generate a precise 90-degree phase shift between Channel A and Channel B. This allowed the logic controller to determine directionality (Channel A leading indicates clockwise rotation, Channel B leading indicates counter-clockwise). * **Signal Processing & Noise Mitigation:** Because LDRs produce noisy analog voltage fluctuations rather than clean digital pulses, I developed threshold-based software logic to convert the analog inputs into stable, reliable digital states, filtering out ambient light interference.

### The Results
The project successfully validated the hardware-software synchronization, allowing for real-time tracking and precise angular control of the motor. Beyond the functional success, building the sensor from scratch provided deep, hands-on experience with signal processing and the critical importance of pre-project systems mapping.

---

### View the Technical Files
To view the technical report detailing the circuit architecture, encoder disc geometry, and complete mechatronic design analysis, visit the repository below.

<ul class="actions">
    <li><a href="https://github.com/josephwmarsh/DIY-Quadrature-Encoder-Design-and-Analysis" target="_blank" class="button next">View GitHub Repository</a></li>
</ul>
