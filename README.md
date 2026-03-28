# Adaptive vs. Static Robot-to-Human Handover: A Study on Orientation and Approach Direction

This repository contains the project page for the paper:

> **Adaptive vs. Static Robot-to-Human Handover: A Study on Orientation and Approach Direction**
> Federico Biagi, Dario Onfiani, Simone Silenzi, Cristina Iani, Luigi Biagiotti
> *IEEE RO-MAN 2026*

## Overview

This work presents a novel adaptive handover framework that dynamically adjusts the object's delivery pose in real-time based on the user's hand position and orientation, while aligning the object according to the specific downstream task. The system combines AI-based hand pose estimation (MediaPipe and FrankMocap) with smooth B&eacute;zier curve trajectories, parameterized by a limited-jerk fifth-order polynomial. A comprehensive user study with 14 participants compares the adaptive approach against a static baseline using both subjective metrics (NASA-TLX, Human-Robot Trust Scale) and objective physiological data (blink rate from wearable eye-trackers).

## Key Contributions

- **Dynamic Kinematic Control:** Real-time position and orientation adaptation using AI pose estimation, cubic B&eacute;zier trajectories, and SLERP interpolation.
- **Comparative Experimental Validation:** Multimodal evaluation combining subjective questionnaires with objective physiological measurements (eye-tracking blink rate).

## Repository Structure

```
.
├── index.html              # Project page (GitHub Pages)
└── static/                 # Website assets
    ├── css/
    ├── js/
    └── images/             # Converted PNG figures
```

## Acknowledgments

This work was partially supported by:
- The Italian National Recovery and Resilience Plan (PNRR), PRIN Project **I-SHARM**: Intelligent SHared Autonomy for Robotic Manipulation Systems (Project ID 2022NTZRFM)
- The University of Modena and Reggio Emilia FAR project **ROBIN3**

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />The project page is based on the <a href="https://github.com/eliahuhorwitz/Academic-project-page-template">Academic Project Page Template</a> and is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
